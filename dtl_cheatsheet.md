## Cool
- **_variables_** 
    ```django
    {{ biggus }}
    ```

## Not cool
- **_Autoescape_** - Dunno
- **_Block_** - Extendable part of template
    ```django
    {% block biggus %} {% endblock %}
    ```
- **_extends_**
    ```django
    {% extends 'base_template.html' %}
    ```

- **_load static_**
    ```django
    {% load static 'some_static_file.css' %}
    ```

- **_if_**
    ```django
    {% if %}{% endif %}
    ```

- **_if -> elif_**
    ```django
    {% if %}
    {% elifif %}
    {% endif %}
    ```

- **_form_**