---
layout: page
title: История изменений
---

{% assign changelogs = site.collections | find: "label", "changelogs" %}
{% for file in changelogs.files reversed %}
  {% assign version_numbers                  = file.basename | split: "." %}
  {% assign second_version_number_first_char = version_numbers[1] | slice: 0 %}

  {% if version_numbers[1].size == 2 and second_version_number_first_char == "0" %}
    {% assign second_version_number = version_numbers[1] | slice: 1 %}
    {% assign version               = version_numbers[0] | append: "." | append: second_version_number | append: "." | append: version_numbers[2] %}
  {% else %}
    {% assign version = file.basename %}
  {% endif %}

  {% if forloop.first %}
## Последняя версия --- {{ version }} {#latest}
  {% else %}
## {{ version }} {#v{{ version | slugify }}}
  {% endif %}

{% include_relative {{ file.path }} %}
{% endfor %}
