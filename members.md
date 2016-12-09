---
layout: page
title: Members
---

{% assign members = site.data.members | sort: 'name' %}
{% for member in members %}
#### **{{ member.name }}**
*[{{ member.site }}]({{member.site}})*

{{ member.about }}

{% endfor %}


---

## Lab Alumni

{% assign alumni = site.data.alumni | sort: 'name' %}
{% for member in alumni %}
#### **{{ member.name }}**
*[{{ member.site }}]({{member.site}})*

{% endfor %}
