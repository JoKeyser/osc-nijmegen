---
title: Upcoming events
layout: collection
collection: events
---

See below for upcoming events. Have an idea for an event? Get
[in touch](https://radboud-university.github.io/osc-nijmegen/_pages/contact/)
with us or open a new issue on our [Github repo](https://github.com/Radboud-University/osc-nijmegen)! We're available on Twitter as [@OSCNijmegen](https://twitter.com/OSCNijmegen).

{% for post in site.posts %}
{% if post.categories contains 'event' %}
<h3>{{ post.title }}</h3>
{{ post.excerpt }}<br>
<a href="{{ post.url }}">More information...</a>
{% endif %}
{% endfor %}
