---
title: 主要教義
---

{% for doctrine in site.data.doctrines %}
## {{ doctrine.text }}

{% if doctrine.tenets %}

{% for tenet in doctrine.tenets %}
- {{ tenet.text }}
{% endfor %}

{% endif %}
{% endfor %}
