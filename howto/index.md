---
layout: page
title: How To
---

# Generating Themes

If you're using Ulysses or ThiefMD, the ThiefMD [Theme Generator](https://github.com/ThiefMD/theme-generator) makes creating themes easy on Linux. For IDE's, [GtkSourceSchemer](https://github.com/jonocodes/GtkSourceSchemer) provides power and control or [Scribes Theme Generator](http://scribes.sourceforge.net/themegenerator.php) provides a quick and easy method. For macOS, [Ulysses](https://ulysses.app/styles) can be used to build themes.

Today, we're going to be using the ThiefMD [Theme Generator](https://github.com/ThiefMD/theme-generator).

## Export CSS

For generating CSS Packages, check out [thiefmd.com/tips/export-styles](https://thiefmd.com/tips/export-styles).

## Installing the Theme Generator

Conveniently provided binary builds can be [found in our PPA](https://launchpad.net/~thiefmd/+archive/ubuntu/thiefmd). Alternatively, [build from scratch](https://github.com/ThiefMD/theme-generator#requirements), or [build into your user's flatpak](https://github.com/ThiefMD/theme-generator#building-with-flatpak).

```bash
sudo add-apt-repository ppa:thiefmd/thiefmd
sudo apt-get update
sudo apt-get install io.github.thiefmd.themegenerator
```

## ThiefMD Theme Generator Overview

![](/images/pallet.png)

The Color Pallet sits at the top of the window. The first row is the **Light** Color Pallet. These colors will be select-able when modifying the **Light** theme. The second row provides colors available for modifying the **Dark** theme.

The first color in each row is the **Foreground** color. Text defaults to this color.  The second color is the **Background** color. The editor background defaults to this color.

The remaining 11 colors can be used to customize different [Markdown elements](https://daringfireball.net/projects/markdown).

Changing colors is easy. Click on a color, and a Color Picker will appear. On newer versions of the GTK, there's a custom color picker that will even let you grab colors off the screen.

## Markdown Settings

![](/images/attributes.png)

Underneath the Color Pallet are the Markdown Elements and the styling options available. Each element can have a custom Foreground Color, Background Color, and then options of **Bold**, <u>Underline</u>, *Italics*, or ~~Strikethrough~~.

<div style="float: right; width: 40%"><img src="/images/preview.png" /></div> Clicking on the Color will bring up the current colors loaded into the theme's Color Pallet. The results will instantly show in the Preview Window:

Edit the preview text if you want to see how certain elements will render.

<div style="clear: both"></div>

## Color Tools

[ColorHexa](https://www.colorhexa.com) is useful for finding additional colors. We can start with a random color, like <span style="background: #BFDC7E;">#BFDC7E</span>. [ColorHexa](https://www.colorhexa.com/BFDC7E) will show:

![](/images/colorpallet.png)

We can use the Color Picker tool to grab the colors and load them into the Theme Generator.

Once our colors are in, we can play with the Markdown Element Settings to get the theme just the way we want it.

![](/images/current-vibe.png)

Ah yes, that's the vibe I was going for.

## Export

![](/images/export.png)

Clicking on **Export** will bring up the Export Settings. Here, you can name your Theme, and claim Authorship. **Save Ulysses Theme** will create a file holding both the Light and Dark Themes. This file will work with Ulysses or ThiefMD. **Save Light** will save your light theme as a GtkSourceView Style Scheme. **Save Dark** will save your dark theme.

For submission to [themes.thiefmd.com](https://github.com/ThiefMD/themes), you'll have to save all 3. For personal use, just save what you need.

Enjoy Creating! [Download Theme Here](/2020/10/02/howtovibes.html)
