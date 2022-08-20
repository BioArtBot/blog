---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: index
---

<h2>Posts</h2>
<hr>
{% for post in site.posts %}
<div>
    <em style="font-size:small">{{ post.date }}</em>
    <br>
    <strong style="font-size:x-large"><a href="{{ post.url }}">{{ post.title }}</a></strong>
</div>
{% endfor %}