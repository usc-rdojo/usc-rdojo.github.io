---
layout: default
weight: 98
---

RDojo is a group started by Psychology graduate students at the University of Southern California. We meet every-other week to learn about scientific computing in R/RStudio. During each meeting, attendees give hands-on, code-based presentations on a planned topic. Each presentation will be posted to our blog and all code will be stored in our <a href="https://github.com/usc-rdojo/rdojo">github repository</a>. 

<div class="posts">
  {% for post in site.posts %}
    <article class="post">

      <h1><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h1>

      <div class="entry">
        {{ post.excerpt }}
      </div>

      <a href="{{ site.baseurl }}{{ post.url }}" class="read-more">Read More</a>
    </article>
  {% endfor %}
</div>