# Staffeln:
- <a href="#Staffel 1">Staffel 1</a>
- <a href="#Staffel 2">Staffel 2</a>
- <a href="#Staffel 3">Staffel 3</a>
- <a href="#Staffel 4">Staffel 4</a>
- <a href="#Staffel 5">Staffel 5</a>
- <a href="#Staffel 6">Staffel 6</a>
- <a href="#Staffel 7">Staffel 7</a>
- <a href="#Staffel 8">Staffel 8</a>
- <a href="#Staffel 9">Staffel 9</a>
- <a href="#Staffel 10">Staffel 10</a>
- <a href="#Staffel 11">Staffel 11</a>
- <a href="#Staffel 12">Staffel 12</a>

{% for season in site.seasons %}
  <h2 id="{{ season.name }}">{{ season.name }} - {{ season.year }}</h2>
  <p>{{ season.content | markdownify }}</p>
{% endfor %}