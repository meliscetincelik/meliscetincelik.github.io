---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  You can also find my papers on <a href="{{ site.author.googlescholar }}" class="google-scholar-link"> Google Scholar</a>.
{% endif %}


{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
