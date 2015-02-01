# Jekyll include_absolute Tag

A liquid tag to include a file from its path relate to Jekyll's source folder

Syntax: {% include_absolute path %}

## Installation

Copy include_absolute.rb into /_plugins

## Examples

js/common.js

```
{% include_absolute js/jquery.js %}
{% include_absolute js/bootstrap.js %}
```

css/common.css

```
{% include_absolute css/bootstrap.css %}
{% include_absolute css/ionicons.css %}
```

## License

MIT
