---

title: 2020 Global Board Candidates
layout: col-generic

---

The following people are the candidates for the OWASP Global Board of Directors.  Click each candidate's name to learn more about them.

{% assign candidates = site.pages | where: 'candidate', 'true' %}
{% for candidate in candidates %}
### [{{ candidate.title }}]( /www-board-candidates/{{ candidate.url }} )
{% endfor %}