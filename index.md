---

title: OWASP Global Board Candidates
layout: col-sidebar

---

The following people are the candidates for the OWASP Global Board of Directors.  Click each candidate's name to learn more about them.

{% assign candidates = site.pages | where: 'candidate', 'true' %}
{% if candidates.size < 1 %}
### The candidates are still being determined. Please return later.
{% endif %}
{% for candidate in candidates %}
### [{{ candidate.title }}]( /www-board-candidates{{ candidate.url }} )
{% endfor %}
