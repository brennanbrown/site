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
    {% for tag in site.tags %}
    <div class="col-3">
        <h3 id="{{ tag | first }}">{{ tag | first | capitalize }}</h3>
        <ul>
        {% for post in tag.last %}
            <li><a href="{{post.url}}">{{ post.title }}</a></li>
        {% endfor %}
        </ul>
    </div>
    {% endfor %}
    <br/>
    <br/>
</div>
