{% for season in site.seasons %}
  <h2 id="{{ season.name }}">{{ season.name }} - {{ season.year }}</h2>
  <p>{{ season.content | markdownify }}</p>
{% endfor %}