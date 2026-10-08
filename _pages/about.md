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
      I am a fourth-year Ph.D. student in Computer Science at the
      <strong>University of Maryland, College Park</strong>, advised by
      <a href="https://www.cs.umd.edu/~heng/">Heng Huang</a>,
      Brendan Iribe Endowed Professor of Computer Science.
      Previously I received my B.S. in Intelligence Science and Technology from the
      School of Electronics Engineering and Computer Science at <strong>Peking University</strong>,
      where I was fortunate to work with Prof. <a href="https://xusun26.github.io/">Xu Sun</a>.
    </p>
    <p>
      My research is about making generative models <strong>more capable</strong> and, just as
      importantly, <strong>more trustworthy</strong>. On the capability side, I work on data
      selection, preference optimization, and test-time scaling for vision-language understanding
      and image generation. On the trustworthiness side, I design distortion-free watermarks that
      carry provenance signals at no cost to generation quality, across text, speech, audio, and
      protein sequences, and I study attacks such as watermark removal, since robustness against
      an adversary is what makes these guarantees usable in practice.
    </p>
    <p>
      I am always happy to connect. Feel free to email me at
      <a href="mailto:rbchen@umd.edu">rbchen [at] umd [dot] edu</a>
      if you are interested in my research or possible collaborations.
    </p>
    <p>
      <strong>I am actively looking for research internship opportunities for Spring and Summer 2027!</strong>
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
  {% include pub-list.html selected_only="true" kind="published" %}
</section>

<section class="section">
  <h2 class="section__title">Preprints</h2>
  {% include pub-list.html selected_only="true" kind="preprint" %}
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
        <span class="where">TikTok, San Jose, CA &middot; Mentor: Jian Du</span>
        <ul class="timeline__points">
          <li>Developed the core watermarking algorithms for ByteDance LLM products, improving
              the detectability and security of distortion-free LLM watermarks.</li>
          <li>Built and pretrained VAE-free multi-scale pixel-space diffusion transformers for
              class-conditional and text-to-image generation.</li>
        </ul>
      </span>
    </li>
    <li>
      <span class="timeline__when">2025</span>
      <span class="timeline__what">
        <strong>Research Scientist Intern</strong>
        <span class="where">TikTok, San Jose, CA &middot; Mentors: Jiacheng Pan, Zhenheng Yang</span>
        <ul class="timeline__points">
          <li>Mitigated the training-inference mismatch in text-to-image models by training an LLM
              with RL to align user prompts with the model's input distribution, improving
              generation quality.</li>
        </ul>
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
