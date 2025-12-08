---
layout: single_page
---

{% assign media = site.mindoc_media | where: "page", "source" | sort: "order" %}

{% assign media = site.mindoc_media | where: "page", "section-name" %}
{% include media_next.html pages=media %}
