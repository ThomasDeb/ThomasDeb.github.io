---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======

* 2017-2022 (expected): Ph.D in Electrical Engineering at the [Biomedical Imaging Group](http://bigwww.epfl.ch/), Ecole Polytechnique Fédérale de Lausanne, Switzerland
* 2016-2017: M.Sc. in [Mathematics, Vision and Learning](http://math.ens-paris-saclay.fr/version-francaise/formations/master-mva/), ENS Paris-Saclay, France
* 2013-2016: M.Sc. in Engineering (major in Applied Mathematics), [Mines ParisTech](https://www.minesparis.psl.eu), France
* 2011-2013: Louis-le-Grand preparatory school for "Grandes Ecoles" (Math and Physics section), Paris, France

Publications
======

Preprints
--------------
<ul>
{% for post in site.publications reversed%}
	{% if post.category contains 'preprint' %}
		{% include archive-single-cv.html %}
	{% endif %}
{% endfor %}
</ul>

Journal Papers
--------------
<ul>
{% for post in site.publications reversed%}
	{% if post.category contains 'journal' %}
		{% include archive-single-cv.html %}
	{% endif %}
{% endfor %}
</ul>

Conference Proceedings
--------------
<ul>
{% for post in site.publications reversed%}
	{% if post.category contains 'proceedings' %}
		{% include archive-single-cv.html %}
	{% endif %}
{% endfor %}
  </ul>

Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>

Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Go Achievements
======
* French national go champion: 2010-2014, 2018 (5 times)
* French representative at the World Amateur Go Championships: 2009-2011, 2013 (best result: 4th place)
* European team champion (with French team): 2015, 2019, 2020
