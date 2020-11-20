<h2>{{ site.data.navigation.docs_list_title }}</h2>
<ul>
   {% for item in site.data.navigation.docs %}
      <li><a href="{{ item.url }}">{{ item.title }}</a></li>
   {% endfor %}
</ul>
