---
layout: home
permalink: researchers
title: "Researchers and Staff"
excerpt: " <br> <br>"
image:
  feature: 20110808_077.jpg
---
<h2 class="post-title">Researchers</h2>
<div class="tiles">
{% for post in site.categories.researchers %}
	{% include researchers-grid.html %}
{% endfor %}
</div><!-- /.tiles -->
<br><br><br><br><br><br><br><br><br><br><br><br><br><br>

<div><h2 class="post-title">Staff</h2></div>
<div class="tiles">
{% for post in site.categories.staff %}
	{% include researchers-grid.html %}
{% endfor %}
</div><!-- /.tiles -->
