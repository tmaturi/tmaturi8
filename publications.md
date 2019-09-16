---
title: Publications
layout: default
---

### Publications (Journal papers and Book sections)

<ul>
{% for paper in site.data.papers %}
  <li>
      {{ paper.Name }} {{paper.Year}}. {{ paper.Title }}, {{ paper.Journal }}, {{ paper.Volume }}: {{ paper.Pages }}.
  </li>
{% endfor %}
</ul>
