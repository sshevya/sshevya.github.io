---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---
<div class="home">

  <h2>A learning experience</h2>
    
 {% for post in site.posts %}
 <h6><li><a href="{{ post.url }}">{{post.title}}</a></li></h6>

{% endfor %}
</div>
 