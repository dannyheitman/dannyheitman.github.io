---
layout: default
---

## Recent work
  **[All](/posts/all)**, [General](/posts/general), [Nature](/posts/nature), [Reading and literature](/posts/reading-and-literature)
{% for post in site.posts %}
  {% if post.external_url %}
  <h3>
    <a href="{{post.external_url}}">{{ post.title }} ({{post.external_site}})</a>
  </h3>
  {% else %}
    <a href="{{post.url}}">{{ post.title }}</a>
  {% endif %}
  {{ post.subtitle }}
  *{{ post.date | date: "%B %Y" }}*
  <br/><br/>
{% endfor %}