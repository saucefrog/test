{% for entry in site.data.test %}
  <h3>{{ entry.title }}</h3>
  <h4>{{ entry.year }}, {{ entry.publisher }}</h4>
{% endfor %}
