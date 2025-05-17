---
layout: page
title: Blog
permalink: /blog/
nav-include: true
nav-order: 1
---
Welcome to my blog.

{{ content }}

<h2 class="post-list-heading line-bottom">{{ page.list_title | default: "Posts" }}</h2>
  <ul class="post-list">
    {% for post in site.posts %}
      <li>
        {% include post_preview.html post=post %}
      </li><br/>
    {% endfor %}
  </ul>
</div>