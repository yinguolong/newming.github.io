---
layout: default
title: Newming's Blogs
---

Hi here,I'm newming,a college student.

This is my first time using  jekyll.

<p><b>My Blogs:</b></p>
	<ul class="posts">
    {% for post in site.posts %}
      <li>
      	<span>{{ post.date | date_to_string }}</span> &raquo; 
      	<a href="{{ post.url }}">{{ post.title }}</a>
      </li>
    {% endfor %}
  	</ul>

<blockquote>
欢迎所有朋友加我QQ：977527479
</blockquote>