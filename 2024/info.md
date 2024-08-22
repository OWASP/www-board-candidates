### [Board Candidates](/www-board-candidates/)

{% assign candidates = site.pages | where: 'candidate', 'true' %}
{% for candidate in candidates %}
* [{{ candidate.title }}]( /www-board-candidates{{ candidate.url }} )
{% endfor %}

