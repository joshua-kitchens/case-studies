---
layout: default
title: Case Studies
permalink: /case_studies/
---

# {{ page.title }}

{% for item in site.case_studies %}
- [{{ item.title }}]({{ item.url | relative_url }})
  {% if item.excerpt %}{{ item.excerpt }}{% endif %}
{% endfor %}