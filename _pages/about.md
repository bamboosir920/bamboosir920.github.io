---
permalink: /
title: "Houcheng Su — Academic Homepage"
excerpt: "Ph.D. candidate at HKUST (Guangzhou), expected to graduate in June 2028, working on AI agents, AI for Science, computational genomics, and reliable machine learning."
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

{% assign agent_papers = site.data.publications | where: "topic", "agents" %}
{% assign science_papers = site.data.publications | where: "topic", "science" %}
{% assign learning_papers = site.data.publications | where: "topic", "learning" %}

<span class="anchor" id="about-me"></span>

<section class="cv-section cv-intro" aria-labelledby="about-title">
  <h2 id="about-title">😊 About Me</h2>
  <p>I am a <strong class="text-accent">Ph.D. Candidate</strong> in <strong>Data Science and Analytics</strong> at the <strong>Hong Kong University of Science and Technology (Guangzhou)</strong>, advised by <a href="https://scholar.google.com/citations?user=1K76SCUAAAAJ" target="_blank" rel="noopener">Prof. Yanlin Zhang</a>. I expect to graduate in <strong class="text-accent">June 2028</strong>.</p>

  <p>My primary research interest is <strong class="text-accent">AI agents for scientific workflows</strong>. I study how agents can plan analyses, use specialist tools, recover from execution errors, preserve intermediate evidence, and produce results that scientists can verify. I also work on <strong>AI for Science</strong>, especially computational genomics and biological foundation models, as well as domain adaptation and reliable machine learning.</p>

  <p>Previously, I received my M.Sc. in Data Science from the <strong>University of Macau</strong>, where I was advised by <a href="https://scholar.google.com/citations?user=uFUPIekAAAAJ" target="_blank" rel="noopener">Prof. Chi-Man Vong</a>, and my B.Eng. in Computer Science and Technology from <strong>Sichuan Agricultural University</strong>.</p>

  <p class="collaboration-note"><span aria-hidden="true">💬</span> I am always happy to discuss research ideas and potential collaborations. Please feel free to contact me by <a href="mailto:hsu638@connect.hkust-gz.edu.cn">email</a>.</p>

  <div class="research-focus" aria-label="Research focus">
    <h3>Research Interests</h3>
    <ul>
      <li><span class="interest-icon" aria-hidden="true">🤖</span><span><strong>Agentic AI:</strong> multi-agent systems, tool use, workflow planning, debugging, and verification.</span></li>
      <li><span class="interest-icon" aria-hidden="true">🧬</span><span><strong>AI for Science:</strong> computational genomics, biological sequence understanding, and scientific foundation models.</span></li>
      <li><span class="interest-icon" aria-hidden="true">🛡️</span><span><strong>Reliable Machine Learning:</strong> domain adaptation, domain generalization, test-time learning, and medical vision.</span></li>
    </ul>
  </div>
</section>

<section class="cv-section" id="news" aria-labelledby="news-title">
  <div class="cv-heading">
    <h2 id="news-title">🔥 News</h2>
  </div>
  <article class="featured-news" aria-labelledby="biomaster-cover-title">
    <div class="featured-news__eyebrow"><span>🎊 Cover Article</span><time datetime="2026-08">August 2026</time></div>
    <h3 id="biomaster-cover-title">Congratulations! BioMaster is the August cover article of <em>Patterns</em></h3>
    <p><strong class="text-accent">BioMaster 2.0</strong> has been extensively rebuilt through secondary development on top of <strong>OpenCode</strong>. The refactored system provides a cleaner, more extensible foundation for knowledge-guided bioinformatics workflow planning, execution, debugging, and checking.</p>
    <div class="featured-news__links">
      <a href="https://ai4nucleome.github.io/BioMaster/" target="_blank" rel="noopener">Explore BioMaster 2.0 →</a>
      <a href="https://doi.org/10.1016/j.patter.2026.101611" target="_blank" rel="noopener">Read the Paper</a>
      <a href="https://github.com/ai4nucleome/BioMaster" target="_blank" rel="noopener">View Code</a>
    </div>
  </article>
  <div class="scroll-window news-window" tabindex="0" aria-label="News updates; scroll to read older items">
    <ul class="news-list">
      <li class="news-list__featured"><time datetime="2026-08">2026.08:</time><p><span aria-hidden="true">🎊🎊</span> <a href="https://ai4nucleome.github.io/BioMaster/" target="_blank" rel="noopener"><strong>BioMaster 2.0</strong></a>, an extensive OpenCode-based refactor, is now online.</p></li>
      <li><time datetime="2026-07">2026.07:</time><p><span aria-hidden="true">🎉🎉</span> <a href="https://doi.org/10.1016/j.patter.2026.101611" target="_blank" rel="noopener"><strong>BioMaster</strong></a> was published in <em>Patterns</em>.</p></li>
      <li><time datetime="2026-04">2026.04:</time><p><span aria-hidden="true">🎉🎉</span> <a href="https://doi.org/10.18653/v1/2026.acl-long.1655" target="_blank" rel="noopener"><strong>GenomeQA</strong></a> and <a href="https://doi.org/10.18653/v1/2026.findings-acl.1432" target="_blank" rel="noopener"><strong>PhageBench</strong></a> appeared at ACL 2026.</p></li>
      <li><time datetime="2026-04">2026.04:</time><p><span aria-hidden="true">🚀🚀</span> We released <a href="https://doi.org/10.64898/2026.03.02.709209" target="_blank" rel="noopener"><strong>PopGenAgent</strong></a> for population genetics analyses.</p></li>
      <li><time datetime="2025-05">2025.05:</time><p><span aria-hidden="true">🎉🎉</span> <a href="https://proceedings.mlr.press/v267/wang25cq.html" target="_blank" rel="noopener"><strong>GraphCL</strong></a> was accepted at ICML 2025.</p></li>
      <li><time datetime="2025-04">2025.04:</time><p><span aria-hidden="true">🎉🎉</span> <a href="https://doi.org/10.24963/ijcai.2025/155" target="_blank" rel="noopener"><strong>ESBN</strong></a> was accepted at IJCAI 2025.</p></li>
      <li><time datetime="2025-03">2025.03:</time><p><span aria-hidden="true">🎉🎉</span> <a href="https://doi.org/10.1093/bioinformatics/btaf229" target="_blank" rel="noopener"><strong>MutBERT</strong></a> was accepted by the ISMB Proceedings track.</p></li>
      <li><time datetime="2024-08">2024.08:</time><p><span aria-hidden="true">📣📣</span> I started my Ph.D. study at HKUST (Guangzhou).</p></li>
    </ul>
  </div>
  <p class="scroll-hint" aria-hidden="true">↕ Scrollable</p>
</section>

<section class="cv-section" id="publications" aria-labelledby="publications-title">
  <div class="cv-heading cv-heading--publications">
    <div>
      <h2 id="publications-title">📝 Publications</h2>
      <p><sup>*</sup> Equal contribution · <sup>‡</sup> Student first author · <sup>✉</sup> Corresponding author · My name is shown in bold.</p>
    </div>
    <a href="https://scholar.google.com/citations?user=77x1NdQAAAAJ&hl=en" target="_blank" rel="noopener">Full list on Google Scholar →</a>
  </div>

  <h3 class="publication-group-title"><span>Agentic Systems</span><span class="publication-group-count">{{ agent_papers.size }}</span></h3>
  <div class="scroll-window publication-list publication-list--scroll" tabindex="0" aria-label="Agentic Systems publications">
    {% for paper in agent_papers %}
    <article class="publication-entry">
      <a class="publication-entry__thumb" href="{{ paper.url }}" target="_blank" rel="noopener" aria-label="Open {{ paper.title }}">
        {% if paper.image %}<img{% if paper.image_fit == "contain" %} class="publication-entry__image--contain"{% endif %} src="{{ paper.image }}" alt="{% if paper.image_alt %}{{ paper.image_alt }}{% else %}Figure for {{ paper.title }}{% endif %}" loading="lazy" decoding="async">{% else %}<span>{{ paper.venue }}</span>{% endif %}
      </a>
      <div class="publication-entry__content">
        <div class="publication-entry__meta"><span>{{ paper.venue }}</span><span>{{ paper.year }}</span>{% if paper.impact_factor %}<a class="publication-entry__impact" href="{{ paper.impact_url }}" target="_blank" rel="noopener" title="{{ paper.impact_year }} Journal Impact Factor">{{ paper.impact_year }} IF {{ paper.impact_factor }}</a>{% endif %}{% if paper.highlight %}<span class="publication-entry__highlight">{{ paper.highlight }}</span>{% endif %}</div>
        <h4><a href="{{ paper.url }}" target="_blank" rel="noopener">{{ paper.title }}</a></h4>
        <p class="publication-entry__authors">{{ paper.authors | replace: "Houcheng Su", "<strong>Houcheng Su</strong>" }}</p>
        <div class="publication-entry__links"><a href="{{ paper.url }}" target="_blank" rel="noopener">Paper</a>{% if paper.project %}<a href="{{ paper.project }}" target="_blank" rel="noopener">Project</a>{% endif %}{% if paper.code %}<a href="{{ paper.code }}" target="_blank" rel="noopener">Code</a>{% endif %}</div>
      </div>
    </article>
    {% endfor %}
  </div>

  <h3 class="publication-group-title"><span>AI for Science</span><span class="publication-group-count">{{ science_papers.size }}</span></h3>
  <div class="scroll-window publication-list publication-list--scroll" tabindex="0" aria-label="AI for Science publications">
    {% for paper in science_papers %}
    <article class="publication-entry">
      <a class="publication-entry__thumb" href="{{ paper.url }}" target="_blank" rel="noopener" aria-label="Open {{ paper.title }}">
        {% if paper.image %}<img{% if paper.image_fit == "contain" %} class="publication-entry__image--contain"{% endif %} src="{{ paper.image }}" alt="{% if paper.image_alt %}{{ paper.image_alt }}{% else %}Figure for {{ paper.title }}{% endif %}" loading="lazy" decoding="async">{% else %}<span>{{ paper.venue }}</span>{% endif %}
      </a>
      <div class="publication-entry__content">
        <div class="publication-entry__meta"><span>{{ paper.venue }}</span><span>{{ paper.year }}</span>{% if paper.impact_factor %}<a class="publication-entry__impact" href="{{ paper.impact_url }}" target="_blank" rel="noopener" title="{{ paper.impact_year }} Journal Impact Factor">{{ paper.impact_year }} IF {{ paper.impact_factor }}</a>{% endif %}{% if paper.highlight %}<span class="publication-entry__highlight">{{ paper.highlight }}</span>{% endif %}</div>
        <h4><a href="{{ paper.url }}" target="_blank" rel="noopener">{{ paper.title }}</a></h4>
        <p class="publication-entry__authors">{{ paper.authors | replace: "Houcheng Su", "<strong>Houcheng Su</strong>" }}</p>
        <div class="publication-entry__links"><a href="{{ paper.url }}" target="_blank" rel="noopener">Paper</a>{% if paper.project %}<a href="{{ paper.project }}" target="_blank" rel="noopener">Project</a>{% endif %}{% if paper.code %}<a href="{{ paper.code }}" target="_blank" rel="noopener">Code</a>{% endif %}</div>
      </div>
    </article>
    {% endfor %}
  </div>

  <h3 class="publication-group-title"><span>Reliable Machine Learning</span><span class="publication-group-count">{{ learning_papers.size }}</span></h3>
  <div class="scroll-window publication-list publication-list--scroll" tabindex="0" aria-label="Reliable Machine Learning publications">
    {% for paper in learning_papers %}
    <article class="publication-entry">
      <a class="publication-entry__thumb" href="{{ paper.url }}" target="_blank" rel="noopener" aria-label="Open {{ paper.title }}">
        {% if paper.image %}<img{% if paper.image_fit == "contain" %} class="publication-entry__image--contain"{% endif %} src="{{ paper.image }}" alt="{% if paper.image_alt %}{{ paper.image_alt }}{% else %}Figure for {{ paper.title }}{% endif %}" loading="lazy" decoding="async">{% else %}<span>{{ paper.venue }}</span>{% endif %}
      </a>
      <div class="publication-entry__content">
        <div class="publication-entry__meta"><span>{{ paper.venue }}</span><span>{{ paper.year }}</span>{% if paper.impact_factor %}<a class="publication-entry__impact" href="{{ paper.impact_url }}" target="_blank" rel="noopener" title="{{ paper.impact_year }} Journal Impact Factor">{{ paper.impact_year }} IF {{ paper.impact_factor }}</a>{% endif %}{% if paper.highlight %}<span class="publication-entry__highlight">{{ paper.highlight }}</span>{% endif %}</div>
        <h4><a href="{{ paper.url }}" target="_blank" rel="noopener">{{ paper.title }}</a></h4>
        <p class="publication-entry__authors">{{ paper.authors | replace: "Houcheng Su", "<strong>Houcheng Su</strong>" }}</p>
        <div class="publication-entry__links"><a href="{{ paper.url }}" target="_blank" rel="noopener">Paper</a>{% if paper.project %}<a href="{{ paper.project }}" target="_blank" rel="noopener">Project</a>{% endif %}{% if paper.code %}<a href="{{ paper.code }}" target="_blank" rel="noopener">Code</a>{% endif %}</div>
      </div>
    </article>
    {% endfor %}
  </div>
</section>

<section class="cv-section" id="education" aria-labelledby="education-title">
  <div class="cv-heading"><h2 id="education-title">📖 Education</h2></div>
  <div class="education-list">
    <article class="education-card">
      <div class="education-card__content">
        <div class="education-card__topline"><span>Doctoral</span><time>2024.08 — 2028.06</time></div>
        <h3>Ph.D. in Data Science and Analytics</h3>
        <p class="education-card__institution"><a href="https://www.hkust-gz.edu.cn/" target="_blank" rel="noopener">Hong Kong University of Science and Technology (Guangzhou)</a></p>
        <a class="education-card__credential education-card__credential--qs" href="https://www.topuniversities.com/universities/hong-kong-university-science-technology" target="_blank" rel="noopener">HKUST · QS World University Rankings 2027 · <strong>#33</strong></a>
        <ul>
          <li><strong>Ph.D. Candidate</strong> · Expected graduation: <strong>June 2028</strong></li>
          <li>Advisor: <a href="https://scholar.google.com/citations?user=1K76SCUAAAAJ" target="_blank" rel="noopener">Prof. Yanlin Zhang</a></li>
        </ul>
      </div>
      <a class="education-card__logo education-card__logo--hkust" href="https://www.hkust-gz.edu.cn/" target="_blank" rel="noopener" aria-label="Visit HKUST Guangzhou website"><img src="/images/school-hkust-gz.png" alt="Hong Kong University of Science and Technology Guangzhou logo" loading="lazy" decoding="async"></a>
    </article>

    <article class="education-card">
      <div class="education-card__content">
        <div class="education-card__topline"><span>Master</span><time>2022.08 — 2024.06</time></div>
        <h3>M.Sc. in Data Science</h3>
        <p class="education-card__institution"><a href="https://www.um.edu.mo/" target="_blank" rel="noopener">University of Macau</a></p>
        <a class="education-card__credential education-card__credential--qs" href="https://www.topuniversities.com/universities/university-macau" target="_blank" rel="noopener">University of Macau · QS World University Rankings 2027 · <strong>#267</strong></a>
        <ul>
          <li>Concentration: <strong>Artificial Intelligence Applications</strong></li>
          <li>Advisor: <a href="https://scholar.google.com/citations?user=uFUPIekAAAAJ" target="_blank" rel="noopener">Prof. Chi-Man Vong</a></li>
        </ul>
      </div>
      <a class="education-card__logo education-card__logo--um" href="https://www.um.edu.mo/" target="_blank" rel="noopener" aria-label="Visit University of Macau website"><img src="/images/school-um.png" alt="University of Macau logo" loading="lazy" decoding="async"></a>
    </article>

    <article class="education-card">
      <div class="education-card__content">
        <div class="education-card__topline"><span>Undergraduate</span><time>2018.09 — 2022.06</time></div>
        <h3>B.Eng. in Computer Science and Technology</h3>
        <p class="education-card__institution"><a href="https://www.sicau.edu.cn/" target="_blank" rel="noopener">Sichuan Agricultural University</a></p>
        <a class="education-card__credential education-card__credential--211" href="https://www.moe.gov.cn/srcsite/A22/s7065/200512/t20051223_82762.html" target="_blank" rel="noopener">Project 211 · <strong>National Key University</strong></a>
        <ul>
          <li>A national key university supported under China’s <a href="https://www.moe.gov.cn/srcsite/A22/s7065/200512/t20051223_82762.html" target="_blank" rel="noopener"><strong>Project 211</strong></a>.</li>
          <li>Completed undergraduate study in Computer Science and Technology.</li>
        </ul>
      </div>
      <a class="education-card__logo education-card__logo--sicau" href="https://www.sicau.edu.cn/" target="_blank" rel="noopener" aria-label="Visit Sichuan Agricultural University website"><img src="/images/school-sicau.png" alt="Sichuan Agricultural University logo" loading="lazy" decoding="async"></a>
    </article>
  </div>
</section>

<section class="cv-section" id="service" aria-labelledby="service-title">
  <div class="cv-heading"><h2 id="service-title">📰 Peer Review</h2></div>
  <ul class="review-list" aria-label="Peer review experience">
    <li><time datetime="2025">2025</time><p><strong>ICASSP 2025</strong> Reviewer</p></li>
    <li><time datetime="2025">2025</time><p><strong>AAAI 2025</strong> Reviewer</p></li>
    <li><time datetime="2025">2025</time><p><strong>ICML 2025</strong> Reviewer</p></li>
    <li><time datetime="2025">2025</time><p><strong>NeurIPS 2025</strong> Reviewer</p></li>
    <li><time datetime="2025">2025</time><p><strong>IJCAI 2025</strong> Reviewer</p></li>
    <li><time datetime="2025">2025</time><p><strong>ICLR 2025</strong> Reviewer</p></li>
    <li><time datetime="2024">2024</time><p><strong>ICASSP 2024</strong> Reviewer</p></li>
    <li><time datetime="2024">2024</time><p><strong>IJCAI 2024</strong> Reviewer</p></li>
    <li class="review-list__journals"><span>Journals</span><p><strong>Frontiers of Computer Science</strong> · <strong>The Journal of Supercomputing</strong></p></li>
  </ul>
</section>

<footer class="cv-footer">
  <p>© {{ 'now' | date: "%Y" }} Houcheng Su · Last updated August 2026</p>
</footer>
