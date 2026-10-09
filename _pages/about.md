---
permalink: /
title: "Recko Zhu"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<p class="home-kicker">PhD Candidate · Xiamen University</p>

I work on multimodal intelligence and 3D perception, with current interests in multimodal large-model agents, harness design, and cross-modal representation learning. My earlier research focused on 3D representations for localization in autonomous-driving scenarios.

<div class="profile-actions" aria-label="Profile links">
  <a class="profile-action" href="{{ '/cv/' | relative_url }}"><i class="fas fa-file-lines" aria-hidden="true"></i> CV</a>
  <a class="profile-action" href="https://scholar.google.com/citations?user=YILgmXQAAAAJ&hl=zh-CN&oi=ao"><i class="ai ai-google-scholar" aria-hidden="true"></i> Google Scholar</a>
  <a class="profile-action" href="https://github.com/Reckozmh"><i class="fab fa-github" aria-hidden="true"></i> GitHub</a>
  <a class="profile-action" href="mailto:judemihoo@gmail.com"><i class="fas fa-envelope" aria-hidden="true"></i> Email</a>
</div>

## About Me

I am currently a PhD candidate at the Key Laboratory of Multimedia Trusted Perception and Efficient Computing, Ministry of Education, Xiamen University, working with Prof. Cheng Wang and Assistant Prof. Sheng Ao.

I received my academic master's degree in Computer Technology from Huaqiao University in 2023, advised by Prof. Xin Liu. I am based in Xiamen, China. You can reach me at [judemihoo@gmail.com](mailto:judemihoo@gmail.com) or [mihoo@stu.xmu.edu.cn](mailto:mihoo@stu.xmu.edu.cn).

## Research Interests

<ul class="interest-list" aria-label="Research interests">
  <li>LiDAR / 4D Radar Localization</li>
  <li>3D Vision</li>
  <li>Vision-Language Models</li>
  <li>Long Multimodal Document Understanding</li>
</ul>

## News

<div class="news-list">
  <div class="news-item"><time>Sep 2026</time><p><strong>DocHarness-RSI</strong> was submitted to ICLR 2027 (first author).</p></div>
  <div class="news-item"><time>Sep 2026</time><p><strong>VLM-Loc</strong> was accepted by NeurIPS 2026 (first author).</p></div>
  <div class="news-item"><time>Sep 2026</time><p><strong>LINK</strong> was accepted by NeurIPS 2026 (first author).</p></div>
  <div class="news-item"><time>Sep 2026</time><p><strong>BiLi</strong> was accepted by NeurIPS 2026 (first author).</p></div>
  <div class="news-item"><time>Sep 2026</time><p><strong>SPAR</strong> was accepted by NeurIPS 2026.</p></div>
  <div class="news-item"><time>Sep 2026</time><p><strong>TempLoc</strong> was accepted by ACM MM 2026 as an oral paper (first author; <span class="todo-inline">TODO: verify oral-rate figure</span>).</p></div>
  <div class="news-item"><time>Feb 2026</time><p><strong>LEADER</strong> was accepted by CVPR 2026 (co-first author, Highlight; <span class="todo-inline">TODO: verify highlight-rate figure</span>).</p></div>
  <div class="news-item"><time>Oct 2025</time><p><strong>RCP-LO</strong> acceptance reported in the supplied notes (<span class="todo-inline">TODO: verify conference year</span>).</p></div>
  <div class="news-item"><time>Feb 2026</time><p><strong>DiffLo</strong> acceptance reported in the supplied notes (<span class="todo-inline">TODO: verify conference year</span>).</p></div>
</div>

## Selected Publications

{% assign selected_publications = site.publications | where: "selected", true | sort: "order" %}
<div class="publication-list">
  {% for publication in selected_publications %}
    {% include publication-card.html publication=publication %}
  {% endfor %}
</div>

<p class="section-link"><a href="{{ '/publications/' | relative_url }}">View all publications <span aria-hidden="true">→</span></a></p>

## Honors and Awards

<div class="todo-panel">
  <strong>TODO: Honors and awards</strong>
  <p>No verified award list was included in the supplied materials. Add award name, granting organization, and year.</p>
</div>

## Academic Services

<div class="todo-panel">
  <strong>TODO: Academic services</strong>
  <p>No verified reviewing, committee, or community-service records were included. Add venue, role, and year.</p>
</div>
