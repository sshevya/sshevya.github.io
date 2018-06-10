---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---
<div class="home">

  <h4>A learning experience</h4>
    
 {% for post in site.posts %}
 <h1><li><a href="{{ post.url }}">{{post.title}}</a></li></h1>

{% endfor %}
</div>
 