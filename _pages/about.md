---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

{% include_relative includes/intro.md %}

{% include_relative includes/news.md %}

{% include_relative includes/pub.md %}


# 💻 Work Experience
- *2021.07 - 2022.10*, [Tencent](https://arc.tencent.com/zh/index), ARC Lab, Shenzhen, China. Full-time Computer Vision Researcher.
- *2019.012 - 2022.10*, [Tencent](https://arc.tencent.com/zh/index), ARC Lab, Shenzhen, China. Computer Vision Researcher Intern.

<center> <i><font color=Gray>Last updated on June. 2025</font></i> </center>