{% for image in site.static_files %}
    {% if image.path contains page.permalink + 'img' %}
![]({{ image.path }})
    {% endif %}
{% endfor %}
