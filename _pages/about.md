---
layout: about
title: About
permalink: /

profile:
  align: right
  image: zoe-li-headshot.jpeg
  image_circular: false
  more_info: |
    <style>
      body > .container { max-width: 1200px; }
      .post > .post-header .post-title { font-size: 2.75rem; line-height: 1.15; }
      .post > article > .clearfix > h2 { font-size: 1.5625rem; font-weight: 400; line-height: 1.3; margin-top: 3rem; margin-bottom: 1.25rem; }
      @media (max-width: 600px) {
        .post > .post-header .post-title { font-size: 2.25rem; }
        .post > article > .clearfix > h2 { font-size: 1.375rem; margin-top: 2.5rem; }
      }
      .hobbies-grid { display: grid; grid-template-columns: minmax(0, 1fr); width: 25%; gap: 1.5rem; margin: 1.5rem 0 2rem; }
      @media (max-width: 600px) { .hobbies-grid { width: 100%; } }
      .hobby-label { display: flex; justify-content: space-between; align-items: baseline; gap: 0.5rem; margin-bottom: 0.65rem; font-size: 0.95rem; }
      .hobby-bar { height: 9px; border-radius: 8px; background: #e4e9ec; overflow: hidden; }
      .hobby-fill { height: 100%; border-radius: inherit; background: #496b80; }
      html[data-theme="dark"] .hobby-bar { background: #343e45; }
      html[data-theme="dark"] .hobby-fill { background: #a0bdce; }
      @media (min-width: 992px) {
        .post > article { display: grid; grid-template-columns: minmax(0, 1fr) 270px; gap: 48px; align-items: start; }
        .post > article > .clearfix { grid-column: 1; grid-row: 1; min-width: 0; }
        .post > article > .profile { grid-column: 2; grid-row: 1; float: none; width: 100%; margin: 0; position: sticky; top: 80px; max-height: calc(100dvh - 130px); overflow-y: auto; }
        .post > article > .profile img { width: auto; max-width: 100%; max-height: max(160px, calc(100dvh - 360px)); height: auto; }
      }
      @media (max-width: 991px) {
        .post > article > .profile { float: none; width: 100%; max-width: 330px; margin: 0 0 2rem; }
      }
      .profile .more-info a { color: inherit; text-decoration: none; text-underline-offset: 3px; }
      .profile-links { display: flex; gap: 0.75rem; margin-top: 0.75rem; }
      .profile .more-info .profile-links a { display: inline-flex; align-items: center; justify-content: center; width: 44px; height: 44px; font-size: 1.8rem; text-decoration: none; transition: transform 160ms ease; }
      .profile .more-info .profile-links a:hover,
      .profile .more-info .profile-links a:focus-visible { transform: scale(1.2); text-decoration: none; }
      @media (prefers-reduced-motion: reduce) { .profile .more-info .profile-links a { transition: none; } }
      .post .clearfix a,
      .post .clearfix a:hover,
      .post .clearfix a:focus-visible { color: var(--global-theme-color); text-decoration: none; }
      .profile .more-info .profile-links a { border: 0; background: transparent; border-radius: 0; }
      .profile-links .cv-icon { width: 36px; height: 32px; overflow: visible; }
      .profile-links .linkedin-icon { width: 32px; height: 32px; overflow: visible; }
      .profile-links .linkedin-dot { animation: linkedin-dot-hop 2.5s ease-in-out infinite; }
      .profile-links .linkedin-stem { transform-box: view-box; transform-origin: 6px 29px; animation: linkedin-stem-spring 2.5s ease-in-out infinite; }
      @keyframes linkedin-dot-hop { 0%, 55%, 88%, 100% { transform: translateY(0); } 63% { transform: translateY(0.8px); } 73% { transform: translateY(-1.5px); } 83% { transform: translateY(0.3px); } }
      @keyframes linkedin-stem-spring { 0%, 55%, 73%, 88%, 100% { transform: scaleY(1); } 63% { transform: scaleY(0.94); } 68% { transform: scaleY(1.025); } 83% { transform: scaleY(0.98); } }
      @media (prefers-reduced-motion: reduce) { .profile-links .linkedin-dot, .profile-links .linkedin-stem { animation: none; } }
      .post .publications ol.bibliography { padding-left: 0; margin-left: 0; }
      .post .publications ol.bibliography .author,
      .post .publications ol.bibliography .author a { color: #777; text-decoration: none; border-bottom: none; }
      .post .publications ol.bibliography .author > em { color: var(--global-text-color); font-weight: inherit; font-style: normal; text-decoration: none; border-bottom: none; }
      .post .publications ol.bibliography > li > .row { display: block; margin-left: 0; margin-right: 0; }
      .post .publications ol.bibliography .abbr { display: none; }
      .post .publications ol.bibliography > li > .row > [id] { width: 100%; max-width: 100%; flex: none; margin-left: 0; padding-left: 0; padding-right: 0; }
      .education-entry { margin-bottom: 1.5rem; }
      .education-entry-header { display: flex; flex-wrap: wrap; justify-content: space-between; align-items: baseline; gap: 0.25rem 1rem; }
      .education-entry-header h3, .post .news table th { font-size: 1rem; font-weight: 400; }
      .education-entry-header h3 { margin: 0; }
      .education-entry-date { font-size: 0.9rem; white-space: nowrap; }
      .education-entry-institution { margin-top: 0.25rem; }
      .award-description { margin-top: 0.25rem; font-size: 0.9rem; }
    </style>
    <div style="font-family: Roboto, sans-serif; font-size: 15px; font-weight: 300; line-height: 1.5;">
      <div style="font-size: 22px; margin-bottom: 10px;">Zhuo (Zoe) Li</div>
      <div><strong>PhD Student</strong></div>
      <div>Psychology (Cognitive Neuroscience)</div>
      <div>University of Texas at Austin</div>
      <div>Memory and Aging Lab</div>
      <div style="margin-top: 1rem;">
        <a href="mailto:zhuoli@utexas.edu"><i class="fa-solid fa-envelope fa-fw" aria-hidden="true"></i> zhuoli@utexas.edu</a>
      </div>
      <div class="profile-links">
        <a href="/assets/pdf/zhuo_li_cv.pdf" aria-label="Download CV" title="Download CV">
          <svg class="cv-icon" viewBox="0 0 36 32" fill="none" stroke="currentColor" stroke-width="1.6" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true" focusable="false">
            <path d="M16 9.5C14.5 7.8 12.5 7 10 7 4.7 7 2 11.2 2 17s2.7 10 8 10c2.5 0 4.5-.8 6-2.5l-3-3c-.8.9-1.7 1.3-3 1.3-2.6 0-3.7-2.5-3.7-5.8s1.1-5.8 3.7-5.8c1.3 0 2.2.4 3 1.3z" />
            <path d="M18 7h4.5l3.5 13.5L29.5 7H34l-6 20h-4z" />
          </svg>
        </a>
        <a href="https://www.linkedin.com/in/zoeliumich/" aria-label="LinkedIn" title="LinkedIn">
          <svg class="linkedin-icon" viewBox="0 0 32 32" fill="none" stroke="currentColor" stroke-width="1.6" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true" focusable="false">
            <circle class="linkedin-dot" cx="6" cy="6" r="3.1" />
            <path class="linkedin-stem" d="M3 12h6v17H3z" />
            <path d="M14 12h5v2.2c1.2-1.8 2.9-2.7 5-2.7 4 0 6 2.6 6 7V29h-6V19.7c0-2-.7-3.1-2.2-3.1-1.6 0-2.8 1.2-2.8 3.2V29h-5z" />
          </svg>
        </a>
      </div>
    </div>

selected_papers: false
social: false

announcements:
  enabled: false
  scrollable: true
  limit: 5

latest_posts:
  enabled: false
---

I study human episodic memory, aging, and cultural differences. Currently, I work with [Dr. Audrey Duarte](https://duartelab.la.utexas.edu/) at the Memory and Aging Lab. During my undergrad, I worked with [Dr. Thad Polk](https://sites.lsa.umich.edu/polklab/) at the Computational & Cognitive Neuroscience Lab and [Dr. Shinobu Kitayama](https://sites.lsa.umich.edu/kitayama/) at the Culture & Cognition Lab.

## Research

**Cultural differences in episodic memory.** How does the brain encode and retrieve relationships between objects and their backgrounds, especially when they are congruent or incongruent? How do these processes differ across cultures and with how independent or interdependent a person is?

**GABA, neural distinctiveness, and memory in the aging population.** As people age, patterns of brain activity elicited by different categories of visual stimuli become less distinct—a phenomenon known as age-related neural dedifferentiation. How does this affect memory? Specifically, do brain activity patterns become less distinct when older adults recall objects versus scenes?

## Education

<div class="education-entry">
  <div class="education-entry-header">
    <h3>Ph.D. in Psychology (Cognitive Neuroscience)</h3>
    <span class="education-entry-date">Aug 2025 – May 2030 (expected)</span>
  </div>
  <div class="education-entry-institution">University of Texas at Austin · Austin, Texas, USA</div>
</div>

<div class="education-entry">
  <div class="education-entry-header">
    <h3>B.S. in Biopsychology, Cognition, and Neuroscience (Honors) and Economics</h3>
    <span class="education-entry-date">Aug 2022 – May 2025</span>
  </div>
  <div class="education-entry-institution">University of Michigan · Ann Arbor, Michigan, USA</div>
</div>

## News

<div class="news table-responsive">
  <table class="table table-sm table-borderless">
    {% assign recent_news = site.news | sort: 'date' | reverse %}
    {% for item in recent_news limit: 5 %}
    <tr>
      <th scope="row" style="width: 20%; white-space: nowrap;">{{ item.date | date: '%B %Y' }}</th>
      <td>{{ item.content | remove: '<p>' | remove: '</p>' }}</td>
    </tr>
    {% endfor %}
  </table>
</div>

## Internships & Services

<div class="education-entry">
  <div class="education-entry-header">
    <h3>LSA Honors Program Ambassador</h3>
    <span class="education-entry-date">Nov 2024 – Aug 2025</span>
  </div>
  <div class="education-entry-institution">University of Michigan · Ann Arbor, Michigan, USA</div>
</div>

<div class="education-entry">
  <div class="education-entry-header">
    <h3>International Center Orientation Advisor</h3>
    <span class="education-entry-date">Jul 2024 – Sep 2024</span>
  </div>
  <div class="education-entry-institution">University of Michigan · Ann Arbor, Michigan, USA</div>
</div>

<div class="education-entry">
  <div class="education-entry-header">
    <h3>Content and Operations Intern</h3>
    <span class="education-entry-date">Apr 2024 – Aug 2024</span>
  </div>
  <div class="education-entry-institution">Family Business Audiocast · Remote</div>
</div>

<div class="education-entry">
  <div class="education-entry-header">
    <h3>Management Consulting Intern</h3>
    <span class="education-entry-date">Jun 2023 – Aug 2023</span>
  </div>
  <div class="education-entry-institution">Deloitte · Beijing, China</div>
</div>

## Presentations

{% include selected_papers.liquid %}

## Awards

<div class="education-entry">
  <div class="education-entry-header">
    <h3>Tanner Memorial Award</h3>
    <span class="education-entry-date">2025</span>
  </div>
  <div class="education-entry-institution">University of Michigan</div>
  <div class="award-description">For innovative and original research of merit</div>
</div>

<div class="education-entry">
  <div class="education-entry-header">
    <h3>Harold D. Osterweil Memorial Prize</h3>
    <span class="education-entry-date">2025</span>
  </div>
  <div class="education-entry-institution">University of Michigan</div>
  <div class="award-description">For the most outstanding academic record and greatest social awareness</div>
</div>

<div class="education-entry">
  <div class="education-entry-header">
    <h3>University Honors</h3>
    <span class="education-entry-date">2022–2025</span>
  </div>
  <div class="education-entry-institution">University of Michigan</div>
  <div class="award-description">For academic excellence</div>
</div>

<div class="education-entry">
  <div class="education-entry-header">
    <h3>James B. Angell Scholar</h3>
    <span class="education-entry-date">2025</span>
  </div>
  <div class="education-entry-institution">University of Michigan</div>
  <div class="award-description">For academic excellence</div>
</div>

## Hobbies

<div class="hobbies-grid">
  {% for hobby in site.data.hobbies %}
  <div class="hobby-item">
    <div class="hobby-label">
      <span><span aria-hidden="true">{{ hobby.icon }}</span> {{ hobby.name }}</span>
    </div>
    <div class="hobby-bar" role="meter" aria-label="{{ hobby.name }}" aria-valuemin="0" aria-valuemax="100" aria-valuenow="{{ hobby.percent }}">
      <div class="hobby-fill" style="width: {{ hobby.percent }}%;"></div>
    </div>
  </div>
  {% endfor %}
</div>
