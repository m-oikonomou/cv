{% if name.lower() != "none" %}
## <i class="fab fa-diaspora"></i> {{ name }}
{% endif %}
{% if legend %}
{{ legend }}

{% endif %}
{% block body %}
{{ data }}

{% endblock body %}
