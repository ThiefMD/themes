---
title: ThiefMD Themes
layout: page
---

# Themes

These themes are compatible with [ThiefMD](https://thiefmd.com), [Ulysses](https://ulysses.app), [gedit](https://wiki.gnome.org/Apps/Gedit), and other Markdown editors based on [GtkSourceView](https://wiki.gnome.org/Projects/GtkSourceView). [Learn how to generate your own](/howto) with our [Theme Generator](https://github.com/ThiefMD/theme-generator), and if you feel like sharing it, [send us a pull request](https://github.com/ThiefMD/themes).

## The Latest:

{% assign index = true %}
<div class="row">
{% for post in site.posts limit:3 %}
<div class="theme_preview">
    {% include theme_preview.html %}
</div>
{% endfor %}
</div>

<script type="text/javascript">
    $('.slider').slider({ instructionText: "" });
</script>