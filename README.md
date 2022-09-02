# its-work
Notes and journals from ITS classes
<ul>
  {% for item in site.pages %}
    <li {% if page.url contains item.url %}class="active"{% endif %}><a href="/its-work/{{ item.url }}">{{ item.title }}</a></li>
  {% endfor %}
</ul>
