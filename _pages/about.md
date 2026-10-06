---
layout: academic
permalink: /
title: "Ruibo Chen"
description: "Ruibo Chen is a Ph.D. student in Computer Science at the University of Maryland, College Park, working on large language models, vision-language models, and watermarking."
profile: true
redirect_from:
  - /about/
  - /about.html
---

<section class="section">
  <h2 class="section__title">About</h2>
  <div class="prose">
    <p>
      I am a third-year Ph.D. student in Computer Science at the
      <strong>University of Maryland, College Park</strong>, advised by
      <a href="https://www.cs.umd.edu/~heng/">Heng Huang</a>,
      Brendan Iribe Endowed Professor of Computer Science.
      Previously I received my B.S. in Intelligence Science and Technology from the
      School of Electronics Engineering and Computer Science at <strong>Peking University</strong>,
      where I was fortunate to work with Prof. <a href="https://xusun26.github.io/">Xu Sun</a>.
    </p>
    <p>
      My research is about building <strong>stronger large language models and vision-language
      models</strong>, alongside efforts to enhance their reliability and ensure their safe use.
      Recently I have focused on generative model watermarking — for language, speech, audio,
      and proteins — as well as data selection and preference optimization for multimodal models.
    </p>
    <p>
      I am always happy to connect. Feel free to email me at
      <a href="mailto:rbchen@umd.edu">rbchen [at] umd [dot] edu</a>
      if you are interested in my research or possible collaborations.
    </p>
  </div>
</section>

<section class="section">
  <h2 class="section__title">News</h2>
  <ul class="news">
    {% for item in site.data.news %}
    <li>
      <span class="news__date">{{ item.date }}</span>
      <span class="news__text">{{ item.text | markdownify | remove: '<p>' | remove: '</p>' }}</span>
    </li>
    {% endfor %}
  </ul>
</section>

<section class="section">
  <h2 class="section__title">Selected Publications</h2>
  <p class="note">* denotes equal contribution.</p>
  {% include pub-list.html selected_only="true" %}
  <p class="more-link">
    <a href="{{ '/publications/' | relative_url }}">See all publications &rarr;</a>
    &nbsp;·&nbsp;
    <a href="{{ site.author.googlescholar }}">Google Scholar</a>
  </p>
</section>

<section class="section">
  <h2 class="section__title">Experience</h2>
  <ul class="timeline">
    <li>
      <span class="timeline__when">2026</span>
      <span class="timeline__what">
        <strong>Research Scientist Intern</strong>
        <span class="where">TikTok</span>
      </span>
    </li>
    <li>
      <span class="timeline__when">2025</span>
      <span class="timeline__what">
        <strong>Research Scientist Intern</strong>
        <span class="where">TikTok</span>
      </span>
    </li>
  </ul>
</section>

<section class="section">
  <h2 class="section__title">Education</h2>
  <ul class="timeline">
    <li>
      <span class="timeline__when">2023 – present</span>
      <span class="timeline__what">
        <strong>Ph.D., Computer Science</strong>
        <span class="where">University of Maryland, College Park</span>
      </span>
    </li>
    <li>
      <span class="timeline__when">2019 – 2023</span>
      <span class="timeline__what">
        <strong>B.S., Intelligence Science and Technology</strong>
        <span class="where">Peking University</span>
      </span>
    </li>
  </ul>
</section>

<section class="section">
  <h2 class="section__title">Honors &amp; Awards</h2>
  <ul class="awards">
    <li>Dean's Fellowship, University of Maryland, College Park <span class="year">2023–2025</span></li>
    <li>Outstanding Graduates of Beijing <span class="year">2023</span></li>
    <li>Outstanding Graduates of Peking University <span class="year">2023</span></li>
    <li>National Scholarship, Ministry of Education, China <span class="year">2022</span></li>
  </ul>
</section>
