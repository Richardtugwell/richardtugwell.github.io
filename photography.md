---
layout: page
title: Photography Stuff
---

I've been involved in photography for many years - these are a collection of posts on the topic.

<div class="posts">
  {{site.baseurl}}
  {% for post in paginator.posts %}
  {% if post.topic = photography %}
  <div class="post">
    <h1 class="post-title">
      <a href="{{ site.baseurl }}{{ post.url }}">
        {{ post.title }}
      </a>
    </h1>

    <span class="post-date">{{ post.date | date_to_string }}</span>
  </div>
  {% endif %}
  {% endfor %}
</div>

<div class="pagination">
  {% if paginator.next_page %}
    <a class="pagination-item older" href="{{ site.baseurl }}/page{{paginator.next_page}}">Older</a>
  {% else %}
    <span class="pagination-item older">Older</span>
  {% endif %}
  {% if paginator.previous_page %}
    {% if paginator.page == 2 %}
      <a class="pagination-item newer" href="{{ site.baseurl }}/">Newer</a>
    {% else %}
      <a class="pagination-item newer" href="{{ site.baseurl }}/page{{paginator.previous_page}}">Newer</a>
    {% endif %}
  {% else %}
    <span class="pagination-item newer">Newer</span>
  {% endif %}
</div>

