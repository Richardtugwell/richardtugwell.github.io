---
layout: page
title: A series of posts about music...
---
<p>I can say a lot of other stuff here</p>
<style>.embed-container { position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden; max-width: 100%; } .embed-container iframe, .embed-container object, .embed-container embed { position: absolute; top: 0; left: 0; width: 100%; height: 100%; }</style><div class='embed-container'><iframe src='https://www.youtube.com/embed/D0dC_Boq_yQ' frameborder='0'></iframe></div>
{% for page in site.posts %}
{{page.category}}
{{page.blah}}
{% endfor %}
