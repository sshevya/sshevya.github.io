---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---
<div class="home">

  <h4></h4>
    
 {% for post in site.posts %}
 <h2><li><a href="{{ post.url }}">{{post.title}}</a></li></h2>

{% endfor %}
  
  <a href="mailto:shevya.shruti999@gmail.com?subject=SweetWords&body=Please send me a copy of your new program!">Email Me</a>


</div>
 