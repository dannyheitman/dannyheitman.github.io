---
layout: home
title: Home
---

### [*The Baton Rouge Advocate* columns](https://www.theadvocate.com/baton_rouge/entertainment_life/danny_heitman/)
### [Phi Kappa Phi's *Forum* Magazine](https://www.phikappaphi.org/publications/phi-kappa-phi-forum/forum-archive)

---

## Recent work
[All](/posts/all), [General](/posts/general), [Nature](/posts/nature), [Reading and literature](/posts/reading-and-literature)

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

---
## Books
### [*A Summer of Birds* >>](https://lsupress.org/books/detail/a-summer-of-birds-paperback/)
Over the summer of 1821, a cash-strapped John James Audubon worked as a tutor at Oakley Plantation in Louisiana’s rural West Feliciana Parish. This move initiated a profound change in direction for the struggling artist. Oakley’s woods teemed with life, galvanizing Audubon to undertake one of the most extraordinary endeavors in the annals of art: a comprehensive pictorial record of America’s birds. That summer, Audubon began what would eventually become his four-volume opus, Birds of America.

In *A Summer of Birds*, Danny Heitman recounts the season that shaped Audubon’s destiny, sorting facts from romance to give an intimate view of the world’s most famous bird artist. A new preface marks the two-­hundredth anniversary of that eventful interlude, reflecting on Audubon’s enduring legacy among artists, aesthetes, and nature lovers in Louisiana and around the world.

