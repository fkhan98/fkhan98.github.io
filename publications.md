---
layout: page
title: "Publications"
permalink: /publication/
---

<p class="lede-note">* denotes equal contribution (co-first authorship). See also my <a href="https://scholar.google.com/citations?user=w8iVLl8AAAAJ&amp;hl=en">Google Scholar</a> profile.</p>

<ol class="pubs">
{% for pub in site.data.publications %}
  <li class="pub">
    <span class="pub-short">{{ pub.short }}</span>
    <div class="pub-body">
      <div class="pub-title">{{ pub.title }}</div>
      <div class="pub-authors">{{ pub.authors }}</div>
      <div class="pub-venue">{{ pub.venue }}{% if pub.status %} <span class="status">{{ pub.status }}</span>{% endif %}</div>
      {% if pub.links %}<p class="links">{% for l in pub.links %}<a href="{{ l.url }}">{{ l.label }}</a>{% endfor %}</p>{% endif %}
    </div>
  </li>
{% endfor %}
</ol>
