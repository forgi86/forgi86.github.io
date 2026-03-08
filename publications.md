---
layout: page
title: "Publications"
permalink: /publications/
---

<ul class="publications-list">
{% assign pubs_by_year = site.data.publications | group_by: "year" | sort: "name" | reverse %}
{% for year_group in pubs_by_year %}
  <li class="publication-item" style="border-bottom: none; padding-bottom: 0;">
    <p class="section-title" style="font-size: 1.1rem; margin-top: 1.5rem;">{{ year_group.name }}</p>
  </li>
  {% for pub in year_group.items %}
  <li class="publication-item">
    <p class="publication-title">
      {% include pub-title.html pub=pub %}
    </p>
    <p class="publication-authors">{{ pub.authors }}</p>
    <p class="publication-venue">{{ pub.venue }}</p>
    {% include pub-links.html pub=pub %}
  </li>
  {% endfor %}
{% endfor %}
</ul>
