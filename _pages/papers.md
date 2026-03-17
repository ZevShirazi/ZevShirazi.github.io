---
title: "Papers"
permalink: /papers/
---

Below are selected publications. If you want, I can add BibTeX and PDF links for each entry.

{% for p in site.data.publications %}
**{{ p.year }} — [{{ p.title }}]({{ p.url }})**  
{{ p.authors }}. *{{ p.venue }}*. {% if p.pdf %}[PDF]({{ p.pdf }}){% endif %} {% if p.bib %}[BibTeX]({{ p.bib }}){% endif %}

{% endfor %}
