---
layout: default
title: cv (english)
---

{% capture my_include %}{% include_relative cv_english.md %}{% endcapture %}
{{ my_include | markdownify }}
