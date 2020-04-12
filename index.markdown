---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: post
---

<h2> Posts </h2>
<br>
<ul>
  {% for post in site.posts %}
    <li>
      <h3><b>{{ post.title }}</b></h3>
      {{ post.excerpt }}
      <a href="{{ post.url }}">Read More</a>
    </li>
  {% endfor %}
</ul>