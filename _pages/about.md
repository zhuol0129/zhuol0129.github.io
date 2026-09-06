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
      .profile .more-info a { color: inherit; text-decoration: none; text-underline-offset: 3px; }
      .profile .more-info a:not([href^="mailto:"]):hover,
      .profile .more-info a:not([href^="mailto:"]):focus-visible { text-decoration: underline; }
      .post .clearfix a,
      .post .clearfix a:hover,
      .post .clearfix a:focus-visible { color: #496b80; text-decoration: none; }
      html[data-theme="dark"] .post .clearfix a { color: #a0bdce; }
      .education-entry { margin-bottom: 1.5rem; }
      .education-entry-header { display: flex; flex-wrap: wrap; justify-content: space-between; align-items: baseline; gap: 0.25rem 1rem; }
      .education-entry-header h3 { font-size: 1.15rem; font-weight: 700; margin: 0; }
      .education-entry-date { font-size: 0.9rem; white-space: nowrap; }
      .education-entry-institution { margin-top: 0.25rem; }
    </style>
    <div style="font-family: Roboto, Arial, sans-serif; font-size: 13px; font-weight: 400; line-height: 1.5;">
      <div><strong>PhD Student</strong></div>
      <div>Psychology (Cognitive Neuroscience)</div>
      <div>University of Texas at Austin</div>
      <div>Memory and Aging Lab</div>
      <div style="margin-top: 1rem;">
        <a href="mailto:zhuoli@utexas.edu"><i class="fa-solid fa-envelope fa-fw" aria-hidden="true"></i> zhuoli@utexas.edu</a>
      </div>
      <div style="margin-top: 0.75rem;">Links</div>
      <div><a href="/assets/pdf/zhuo_li_cv.pdf"><i class="fa-solid fa-file-pdf fa-fw" aria-hidden="true"></i> CV</a></div>
      <div><a href="https://www.linkedin.com/in/zoeliumich/"><i class="fa-brands fa-linkedin fa-fw" aria-hidden="true"></i> LinkedIn</a></div>
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

**GABA, neural distinctiveness, and memory in the aging population.** examined how age-related GABA levels relate to neural distinctiveness and memory performance in older adults. Built a MATLAB/R/Bash data pipeline and modeled 50+ variables to identify neural predictors of memory.

**GABA/Glx and auditory processing in aging.** Explored how GABA and glutamate/glutamine (Glx) concentration in auditory cortex relate to auditory performance in older adults.

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

## Presentations & Publications

{% include selected_papers.liquid %}

## Hobbies

I have played basketball for 18 years, hiked in 10 National Parks, and was once a choir singer.
