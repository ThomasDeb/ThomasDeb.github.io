---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on my <u><a href="{{author.googlescholar}}">Google Scholar</a>.</u> or <u><a href="{{author.researchgate}}">Research Gate</a>.</u> profiles.
{% endif %}

{% include base_path %}

Preprints
--------------
{% for post in site.publications %}
	{% if post.category contains 'preprint' %}
		{% include archive-single.html %}
	{% endif %}
{% endfor %}

Journal Papers
--------------
{% for post in site.publications %}
	{% if post.category contains 'journal' %}
		{% include archive-single.html %}
	{% endif %}
{% endfor %}

Conference Proceedings
--------------
{% for post in site.publications %}
	{% if post.category contains 'proceedings' %}
		{% include archive-single.html %}
	{% endif %}
{% endfor %}
