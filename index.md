---
layout: index
title: Your New Jekyll Site
---

{% for post in site.posts %}
<div class="row">
    <div class="box">
        <div class="col-lg-12">
          <hr>
          <h2 class="intro-text text-center">{{ post.title }}
          </h2>
          <hr>
          {{ post.content }}
        </div>
    </div>
</div>
{% endfor %}

<!-- 
<div id="home">
  <h1>Blog Posts</h1>
  <ul class="posts">
    {% for post in site.posts %}
      <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>
</div> -->