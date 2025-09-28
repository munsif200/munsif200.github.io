---
layout: archive
title: "Sitemap"
permalink: /sitemap/
author_profile: true
---

## Pages

{% for post in site.pages %}
  {% if post.permalink %}
    * [{{ post.title }}]({{ post.permalink }})
  {% endif %}
{% endfor %}

## Publications

{% for post in site.publications %}
  * [{{ post.title }}]({{ post.url }})
{% endfor %}

## Talks

{% for post in site.talks %}
  * [{{ post.title }}]({{ post.url }})
{% endfor %}

## Teaching

{% for post in site.teaching %}
  * [{{ post.title }}]({{ post.url }})
{% endfor %}

## Portfolio

{% for post in site.portfolio %}
  * [{{ post.title }}]({{ post.url }})
{% endfor %}

## Blog Posts

{% for post in site.posts %}
  * [{{ post.title }}]({{ post.url }})
{% endfor %}