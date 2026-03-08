---
layout: home
title: "Francesco Forgione"
---

<div class="profile">
  <div class="profile-avatar">
    <div class="avatar-placeholder">&#128100;</div>
  </div>
  <div class="profile-info">
    <h1>{{ site.author.name }}</h1>
    <p class="position">{{ site.author.position }}</p>
    <p class="institution">{{ site.author.institution }}</p>
    <div class="profile-links">
      {% if site.author.email %}
      <a class="profile-link" href="mailto:{{ site.author.email }}">&#9993; Email</a>
      {% endif %}
      {% if site.author.github %}
      <a class="profile-link" href="{{ site.author.github }}" target="_blank" rel="noopener">&#128279; GitHub</a>
      {% endif %}
      {% if site.author.google_scholar %}
      <a class="profile-link" href="{{ site.author.google_scholar }}" target="_blank" rel="noopener">&#128218; Google Scholar</a>
      {% endif %}
      {% if site.author.orcid and site.author.orcid != "" %}
      <a class="profile-link" href="{{ site.author.orcid }}" target="_blank" rel="noopener">&#128279; ORCID</a>
      {% endif %}
      <a class="profile-link" href="{{ '/cv/' | relative_url }}">&#128196; CV</a>
    </div>
  </div>
</div>

<h2 class="section-title">About</h2>
<p>
  {{ site.author.bio }}
</p>
<p>
  My research interests include:
</p>
<ul>
  <li>Machine learning for dynamical systems</li>
  <li>System identification and state estimation</li>
  <li>Data-driven control and optimization</li>
  <li>Neural network-based modeling (RNNs, physics-informed networks)</li>
  <li>Linear Parameter-Varying (LPV) systems</li>
</ul>

<h2 class="section-title">Recent Publications</h2>
<ul class="publications-list">
{% assign recent_pubs = site.data.publications | slice: 0, 3 %}
{% for pub in recent_pubs %}
  <li class="publication-item">
    <p class="publication-title">
      {% include pub-title.html pub=pub %}
    </p>
    <p class="publication-authors">{{ pub.authors }}</p>
    <p class="publication-venue">{{ pub.venue }}, {{ pub.year }}</p>
    {% include pub-links.html pub=pub %}
  </li>
{% endfor %}
</ul>
<p><a href="{{ '/publications/' | relative_url }}">View all publications &rarr;</a></p>
