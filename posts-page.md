---
layout: default
title: Posts
permalink: /posts-page/

---
<header class="post-header">
<h1>Posts</h1>
</header>
<div>
<ul class="post-list">
    {% for post in site.posts %}
      <li>
        <a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
      </li>
    {% endfor %}
  </ul>
</div>