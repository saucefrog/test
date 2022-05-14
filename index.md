<ul>
{% for entry in site.data.test %}
  <li>{{ entry.title" }}-{{ entry.year }}-{{ entry.publisher }}</li>
{% endfor %}
</ul>

