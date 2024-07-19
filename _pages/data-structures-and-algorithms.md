# Data Structures and Algorithms

Welcome to the Data Structures and Algorithms section. Here you will find various articles and resources related to DSA.

## Articles

{% assign dsa_files = site.pages | where: "path", "/_dsa/" %}
<ul>
{% for file in dsa_files %}
  <li><a href="{{ file.url }}">{{ file.title }}</a></li>
{% endfor %}
</ul>