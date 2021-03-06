# Themes

These themes are compatible with [ThiefMD](https://thiefmd.com), [Ulysses](https://ulysses.app), [gedit](https://wiki.gnome.org/Apps/Gedit), and other Markdown editors based on [GtkSourceView](https://wiki.gnome.org/Projects/GtkSourceView). [Learn how to generate your own](/howto) with our [Theme Generator](https://flathub.org/apps/details/io.github.thiefmd.themegenerator), and if you feel like sharing it, [send us a pull request](https://github.com/ThiefMD/themes).

## Placement

Every theme is placed in its own directory in the /themes/ folder. The folder is structured:

```
themes/
       theme-name/
                  theme-name-dark.xml
                  theme-name-light.xml
                  theme-name.ultheme
                  LICENSE.md (if applicable)
```

Export CSS packages follow a similar pattern

```
export-css/
          css-theme-name/
                         preview.css
                         print.css
                         css-theme-name.zip
                         LICENSE.md (if applicable)
```

We will generate the preview images after completing the pull request.

`_posts` is used to index the theme on the site when the preview images are complete, along with determining order. Previews can be generated using [thiefshot](https://github.com/TwiRp/thief-screenshot).

## Post Format

```
---
layout: post
type: [theme|export-css]
theme: theme-name
title: Pretty Theme Name
datetime: YYYY-MM-DD HH:MM
---

Theme description. If you want to link a license or author or inspiration, you can put it here.

License could be in `/[theme|export-css]/theme-name/license/`.

For CSS, special instructions or notices like page-break before every `h1` could be insightful.
```
