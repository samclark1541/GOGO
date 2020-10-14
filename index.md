---
title: Home
---

A maths and physics tutor available for online tutoring.

*Currently taking on students.*

<button type="button" class="btn btn-primary btn-block">Contact</button>

<div class="toc" markdown="1">
## Contents:

{% for lesson in site.pages %}
{% if lesson.nav == true %}- [{{ lesson.title }}]({{ lesson.url | absolute_url }}){% endif %}
{% endfor %}
</div>
