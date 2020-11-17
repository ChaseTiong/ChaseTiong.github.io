---
title: 
author: PITOU
date: 2020-11-17 22:17:00 +0800
categories: [AI, COVID]
tags: [AI]
---

## Summary

This page consists of articles that are related to artifical intelligence

1. AI can detect asymptomatic COVID-19 infections in recorded coughs
```html
https://www.weforum.org/agenda/2020/11/artificial-intelligence-model-detects-asymptomatic-covid-19-infections-through-cellphone-recorded-coughs/
```
2. How to improve cybersecurity for artificial intelligence 
```html
https://www.brookings.edu/research/how-to-improve-cybersecurity-for-artificial-intelligence/
```

## Comments

Similar to TOC, the [Disqus](https://disqus.com/) comments is loaded by default in each post, and the global switch is defined by variable `comments` in file `_config.yml` . If you want to close the comment for specific post, add the following to the **Front Matter** of the post:

```yaml
---
comments: false
---
```


## Mathematics

For website performance reasons, the mathematical feature won't be loaded by default. But it can be enabled by:

```yaml
---
math: true
---
```

## Preview Image

If you want to add an image to the top of the post contents, specify the url for the image by:

```yaml
---
image: /path/to/image-file
---
```

## Pinned Posts

You can pin one or more posts to the top of the home page, and the fixed posts are sorted in reverse order according to their release date. Enable by:

```yaml
---
pin: true
---
```

## Code Block

Markdown symbols <code class="highlighter-rouge">```</code> can easily create a code block as following examples.

```
This is a common code snippet, without syntax highlight and line number.
```

## Specific Language

Using <code class="highlighter-rouge">```language</code> you will get code snippets with line numbers and syntax highlight.

> **Note**: The Jekyll style `{% raw %}{%{% endraw %} highlight LANGUAGE {% raw %}%}{% endraw %}` or `{% raw %}{%{% endraw %} highlight LANGUAGE linenos {% raw %}%}{% endraw %}` are not allowed to be used in this theme !

```yaml
# Yaml code snippet
items:
    - part_no:   A4786
      descrip:   Water Bucket (Filled)
      price:     1.47
      quantity:  4
```

### Liquid Codes

If you want to display the **Liquid** snippet, surround the liquid code with `{% raw %}{%{% endraw %} raw {%raw%}%}{%endraw%}` and `{% raw %}{%{% endraw %} endraw {%raw%}%}{%endraw%}` .

{% raw %}
```liquid
{% if product.title contains 'Pack' %}
  This product's title contains the word Pack.
{% endif %}
```
{% endraw %}

## Learn More

For more knowledge about Jekyll posts, visit the [Jekyll Docs: Posts](https://jekyllrb.com/docs/posts/).

