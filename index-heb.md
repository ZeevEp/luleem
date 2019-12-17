---
layout: body-heb
title: Heb
permalink: /heb/
---

{% assign data = site.data %}
{% assign h_url = data.home-heb %}

{% if h_url.has_home and  h_url.video  %}
  {% include heb/home.html %}
{% endif  %}

{% if h_url.has_contact and  h_url.contact  %}
  {% include heb/contact.html  %}
{% endif  %}

{% if h_url.has_work and  h_url.work  %}
  {% include heb/work.html  %}
{% endif  %}

{% if h_url.has_service and  h_url.service-h  %}
  {% include heb/service.html  %}
{% endif  %}

{% if h_url.has_contact and  h_url.contact  %}
  {% include heb/contact2.html  %}
{% endif  %}