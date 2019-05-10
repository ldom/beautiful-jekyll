{% for image in site.static_files %}
    {% if image.path contains page.permalink %}
![]({{ image.path }})
    {% endif %}
{% endfor %}
