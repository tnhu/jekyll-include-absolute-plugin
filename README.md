# Jekyll include_absolute Tag

A Jekyll's liquid tag plugin to include a file from its path relative to Jekyll's source folder. Why? Because Jekyll's built-in `include` tag does not support including files outside of `_includes` folder.

Syntax: `{% include_absolute path %}`

## Installation

Copy `include_absolute.rb` into `/_plugins`.

## Examples

With this plugin you can include only a file.
```
{% include_absolute '../../folder/outside/jekyll/foo.html' %}
{% include_absolute 'other/folder/bar.js' %}
```
Or include the file and pass parameters to it.
```
{% include_absolute '../../folder/outside/jekyll/foo.html' param1='yes' param2='green' %}
```

## License

[MIT](./LICENSE)
