{% for image in site.static_files %}
    {% if image.path contains page.permalink + 'IMG' %}
![]({{ image.path }})
    {% endif %}
{% endfor %}
