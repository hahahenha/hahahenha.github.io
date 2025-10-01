---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
---

Download

{% include base_path %}


{% for post in site.cv %}
  {% include archive-single.html %}
{% endfor %}

<!--
---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
redirect_to: "https://www.hahahenha.net/static/CV/CV_HX.pdf"
---

{% include base_path %}

<script type="text/javascript">
  window.location.href = "{{ page.redirect_to }}";
</script>
-->

# Education
<hr style="margin-top: 8px; margin-bottom: 20px;">
<ul>
  <li>[2021.09-2025.02] Ph.D in Data Science, City University of Hong Kong</li>
  <li>[2018.09-2021.06] M.S. in Computer Science and Technology, Zhejiang University of Technology</li>
  <li>[2014.09-2018.06] B.S. in Computer Science and Technology, Automation, Zhejiang University of Technology</li>
</ul>


Work experience
======
* Spring 2024: Academic Pages Collaborator
  * Github University
  * Duties includes: Updates and improvements to template
  * Supervisor: The Users

* Fall 2015: Research Assistant
  * Github University
  * Duties included: Merging pull requests
  * Supervisor: Professor Hub

* Summer 2015: Research Assistant
  * Github University
  * Duties included: Tagging issues
  * Supervisor: Professor Git
  
Skills
======
* Skill 1
* Skill 2
  * Sub-skill 2.1
  * Sub-skill 2.2
  * Sub-skill 2.3
* Skill 3

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Currently signed in to 43 different slack teams
