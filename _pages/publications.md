---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

---

{% if site.data.working-papers.size > 0 %}
## Working Papers
<ul>
{% for post in site.data.working-papers %}
  {% include archive-single-publication.html %}
{% endfor %}
</ul>
{% endif %}

<!-- ## Journal Articles -->
<!-- **Under Submission** -->
<!-- <ul>
{% for post in site.data.journal-submissions %}
  {% include archive-single-publication.html %}
{% endfor %}
</ul>
 -->
<!-- **Published** -->
<!-- <ul>
{% for post in site.data.journal %}
  {% include archive-single-publication.html %}
{% endfor %}
</ul> -->

## Conference Publications
<ul>
{% for post in site.data.publications %}
  {% include archive-single-publication.html %}
{% endfor %}
</ul>

---

### Note
Authors are ordered alphabetically unless noted otherwise. 

<!-- ## Unpublished Manuscripts

<ul>
{% for post in site.data.unpublished %}
  {% include archive-single-publication.html %}
{% endfor %}
</ul> -->



