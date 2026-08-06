---
permalink: /
title: "Houcheng Su — Academic Homepage"
excerpt: "Ph.D. student at HKUST (Guangzhou) working on AI agents, AI for Science, computational genomics, and reliable machine learning."
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<span class="anchor" id="about-me"></span>

<section class="cv-section cv-intro" aria-labelledby="about-title">
  <h2 id="about-title">About Me</h2>
  <p>I am a Ph.D. student in <strong>Data Science and Analytics</strong> at the <strong>Hong Kong University of Science and Technology (Guangzhou)</strong>, advised by <a href="https://scholar.google.com/citations?user=1K76SCUAAAAJ" target="_blank" rel="noopener">Prof. Yanlin Zhang</a>.</p>

  <p>My primary research interest is <strong>AI agents for scientific workflows</strong>. I study how agents can plan analyses, use specialist tools, recover from execution errors, preserve intermediate evidence, and produce results that scientists can verify. I also work on <strong>AI for Science</strong>, especially computational genomics and biological foundation models, as well as domain adaptation and reliable machine learning.</p>

  <p>Previously, I received my M.Sc. in Data Science from the <strong>University of Macau</strong>, where I was advised by <a href="https://scholar.google.com/citations?user=uFUPIekAAAAJ" target="_blank" rel="noopener">Prof. Chi-Man Vong</a>, and my B.Eng. in Computer Science and Technology from <strong>Sichuan Agricultural University</strong>.</p>

  <p>I am always happy to discuss research ideas and potential collaborations. Please feel free to contact me by <a href="mailto:hsu638@connect.hkust-gz.edu.cn">email</a>.</p>

  <div class="research-focus" aria-label="Research focus">
    <h3>Research Interests</h3>
    <ul>
      <li><strong>Agentic AI:</strong> multi-agent systems, tool use, workflow planning, debugging, and verification.</li>
      <li><strong>AI for Science:</strong> computational genomics, biological sequence understanding, and scientific foundation models.</li>
      <li><strong>Reliable Machine Learning:</strong> domain adaptation, domain generalization, test-time learning, and medical vision.</li>
    </ul>
  </div>
</section>

<section class="cv-section" id="news" aria-labelledby="news-title">
  <div class="cv-heading">
    <h2 id="news-title">News</h2>
    <span>Selected updates</span>
  </div>
  <ul class="news-list">
    <li><time datetime="2026-07">2026.07</time><p><strong>BioMaster</strong> was published in <em>Patterns</em>.</p></li>
    <li><time datetime="2026-04">2026.04</time><p><strong>GenomeQA</strong> and <strong>PhageBench</strong> were published at ACL 2026 and Findings of ACL 2026.</p></li>
    <li><time datetime="2026-04">2026.04</time><p>We released <strong>PopGenAgent</strong>, an agent-mediated workflow for population genetics analyses.</p></li>
    <li><time datetime="2025-05">2025.05</time><p>One paper was accepted at <strong>ICML 2025</strong>.</p></li>
    <li><time datetime="2025-04">2025.04</time><p>One co-first-author paper was accepted at <strong>IJCAI 2025</strong>.</p></li>
    <li><time datetime="2025-03">2025.03</time><p><strong>MutBERT</strong> was accepted by the ISMB Proceedings track.</p></li>
    <li><time datetime="2024-08">2024.08</time><p>I started my Ph.D. study at HKUST (Guangzhou).</p></li>
  </ul>
</section>

<section class="cv-section" id="publications" aria-labelledby="publications-title">
  <div class="cv-heading cv-heading--publications">
    <div>
      <h2 id="publications-title">Selected Publications</h2>
      <p><sup>*</sup> denotes equal contribution. My name is shown in bold.</p>
    </div>
    <a href="https://scholar.google.com/citations?user=77x1NdQAAAAJ&hl=en" target="_blank" rel="noopener">Full list on Google Scholar →</a>
  </div>

  <h3 class="publication-group-title">Agentic Systems</h3>
  <div class="publication-list">
    {% for paper in site.data.publications %}{% if paper.topic == "agents" %}
    <article class="publication-entry">
      <div class="publication-entry__thumb">
        {% if paper.image %}<img src="{{ paper.image }}" alt="Figure for {{ paper.title }}" loading="lazy">{% else %}<span>{{ paper.venue }}</span>{% endif %}
      </div>
      <div class="publication-entry__content">
        <div class="publication-entry__meta"><span>{{ paper.venue }}</span><span>{{ paper.year }}</span></div>
        <h4><a href="{{ paper.url }}" target="_blank" rel="noopener">{{ paper.title }}</a></h4>
        <p class="publication-entry__authors">{{ paper.authors | replace: "Houcheng Su", "<strong>Houcheng Su</strong>" }}</p>
        <div class="publication-entry__links"><a href="{{ paper.url }}" target="_blank" rel="noopener">Paper</a>{% if paper.code %}<a href="{{ paper.code }}" target="_blank" rel="noopener">Code</a>{% endif %}</div>
      </div>
    </article>
    {% endif %}{% endfor %}
  </div>

  <h3 class="publication-group-title">AI for Science</h3>
  <div class="publication-list">
    {% for paper in site.data.publications %}{% if paper.topic == "science" %}
    <article class="publication-entry">
      <div class="publication-entry__thumb">
        {% if paper.image %}<img src="{{ paper.image }}" alt="Figure for {{ paper.title }}" loading="lazy">{% else %}<span>{{ paper.venue }}</span>{% endif %}
      </div>
      <div class="publication-entry__content">
        <div class="publication-entry__meta"><span>{{ paper.venue }}</span><span>{{ paper.year }}</span></div>
        <h4><a href="{{ paper.url }}" target="_blank" rel="noopener">{{ paper.title }}</a></h4>
        <p class="publication-entry__authors">{{ paper.authors | replace: "Houcheng Su", "<strong>Houcheng Su</strong>" }}</p>
        <div class="publication-entry__links"><a href="{{ paper.url }}" target="_blank" rel="noopener">Paper</a>{% if paper.code %}<a href="{{ paper.code }}" target="_blank" rel="noopener">Code</a>{% endif %}</div>
      </div>
    </article>
    {% endif %}{% endfor %}
  </div>

  <h3 class="publication-group-title">Reliable Machine Learning</h3>
  <div class="publication-list">
    {% for paper in site.data.publications %}{% if paper.topic == "learning" %}
    <article class="publication-entry">
      <div class="publication-entry__thumb">
        {% if paper.image %}<img src="{{ paper.image }}" alt="Figure for {{ paper.title }}" loading="lazy">{% else %}<span>{{ paper.venue }}</span>{% endif %}
      </div>
      <div class="publication-entry__content">
        <div class="publication-entry__meta"><span>{{ paper.venue }}</span><span>{{ paper.year }}</span></div>
        <h4><a href="{{ paper.url }}" target="_blank" rel="noopener">{{ paper.title }}</a></h4>
        <p class="publication-entry__authors">{{ paper.authors | replace: "Houcheng Su", "<strong>Houcheng Su</strong>" }}</p>
        <div class="publication-entry__links"><a href="{{ paper.url }}" target="_blank" rel="noopener">Paper</a>{% if paper.code %}<a href="{{ paper.code }}" target="_blank" rel="noopener">Code</a>{% endif %}</div>
      </div>
    </article>
    {% endif %}{% endfor %}
  </div>
</section>

<section class="cv-section" id="education" aria-labelledby="education-title">
  <div class="cv-heading"><h2 id="education-title">Education</h2></div>
  <div class="resume-list">
    <article><time>2024.08 — Present</time><div><h3>Ph.D. in Data Science and Analytics</h3><p>Hong Kong University of Science and Technology (Guangzhou)</p><p>Advisor: Prof. Yanlin Zhang</p></div></article>
    <article><time>2022.08 — 2024.06</time><div><h3>M.Sc. in Data Science</h3><p>University of Macau · Artificial Intelligence Applications</p><p>Advisor: Prof. Chi-Man Vong</p></div></article>
    <article><time>2018.09 — 2022.06</time><div><h3>B.Eng. in Computer Science and Technology</h3><p>Sichuan Agricultural University</p></div></article>
  </div>
</section>

<section class="cv-section" id="service" aria-labelledby="service-title">
  <div class="cv-heading"><h2 id="service-title">Academic Service</h2></div>
  <div class="service-list">
    <div><h3>Conference Reviewer</h3><p>ICLR · NeurIPS · CVPR · ACM Multimedia · IJCAI · ICASSP · IJCNN</p></div>
    <div><h3>Journal Reviewer</h3><p>Frontiers of Computer Science · The Journal of Supercomputing</p></div>
  </div>
</section>

<footer class="cv-footer">
  <p>© {{ 'now' | date: "%Y" }} Houcheng Su · Last updated August 2026</p>
</footer>
