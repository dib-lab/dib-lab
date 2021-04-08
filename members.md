---
layout: page
title: Members
---

#### **C. Titus Brown**, <small>*QSWG and Assoc Professor*</small>
*[http://ivory.idyll.org/](http://ivory.idyll.org/)*

The PI and Chief of Things. Twitter poweruser. Data wizard. Amateur blockchain enthusiast.

---

{% assign members = site.data.members | sort: 'name' %}
{% for member in members %}
#### **{{ member.name }}**, <small>*{{ member.position }}*</small>
*[{{ member.site }}]({{member.site}})*

{{ member.about }}

---
{% endfor %}


## Lab Alumni

{% assign alumni = site.data.alumni | sort: 'name' %}
{% for member in alumni %}
#### **{{ member.name }}**
*[{{ member.site }}]({{member.site}})*

---

{% endfor %}
