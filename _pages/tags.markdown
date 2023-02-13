---
layout: page
title: Tags
permalink: /tags/
content-type: eg
---

<style>
.category-content a {
    text-decoration: none;
    color: #4183c4;
}

.category-content a:hover {
    text-decoration: underline;
    color: #4183c4;
}
</style>

<div class="row">
    {% assign tags = site.tags | sort %}
    {% for tag in site.tags %}
    <div class="col-3">
  {% assign tag_name = tag[0] %}
  {% assign tag_posts = tag[1] %}
  <li>
    <a href="#{{ tag_name | slugify }}">{{ tag_name }}</a> ({{ tag_posts | size }})
  </li>
    </div>
    {% endfor %}
    <br/>
    <br/>
</div>
