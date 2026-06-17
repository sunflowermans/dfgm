---
title: Digital-first GM
layout: home
nav_order: 0
description: "The landing page for the Digital-first GM."
permalink: /dfgm
nav_exclude: true
---

# Focus on running games
{: .fs-9 }

Instead of scrolling through multiple PDFs, use a website that is easily copied, customized and hosted on GitHub Pages.
{: .fs-6 .fw-300 }

![test](/assets/images/window-preview-demo-1.png)

## Rule reference and running-the-game aid

This site uses [Just The Docs](https://github.com/just-the-docs/just-the-docs), a documentation theme layout for Jekyll. It also uses several plug-ins to make running and referencing your game easier on a computer or mobile device.

Fonts, colors and styles for this site are based on the [Designing Dungeons](https://dungeons.hismajestytheworm.games/) course and are used with permission.

All the documents within are written in Markdown with some optional HTML for styling.

If you’d like to submit an adventure, hack, or conversion take a look at the [submission guide](https://puzzledungeon.com/).

Please refer to the individual adventure or ruleset for various licenses. Some images presented are the property of the original artist and are used with permission. These images are already removed the public GitHub repository so you may clone or fork it without extra work. Here are [instructions on how to do that](https://puzzledungeon.com/) and [host your own site](https://puzzledungeon.com/).

# Plug-ins

This site uses 

These plugins are designed to be used individually or together with any *Just The Docs* site. Here's what it looks like with the [Cairn SRD](https://digital-cairn.pages.dev/).

```ruby
gem "jekyll-hover-popup" # Link preview windows
gem "jekyll-jtd-toc-nav" # Table of Contents in the navigation bar
gem "jekyll-dice-tray" # Dice tray with clickable dice notation recognition
gem "jekyll-image-links" # Custom image map features
```

## Dice Tray

* Automatic dice notation links: 2d6, d20+1, 2-in-6, d6 + d8 (take highest result)
* Type your own
* History
* Automatic dice table results (example below)




  | d6      | Code Name |  Blog     |
  | :-------: |:---: | :-------------: | 
  | 1 | Doctor Worm | [Rise Up Comus](https://riseupcomus.blogspot.com/) |
  | 2 | Dwizard The Lizard Wizard |   [Knight at the Opera](https://knightattheopera.blogspot.com/) |
  | 3 | Big D |  [I Cast Light](https://icastlight.blogspot.com/) |
  | 4 | Oakcat |  [Among Cats and Books](https://elmc.at/) |
  | 5 | W. F. Sandshrew |  [Prismatic Wasteland](https://www.prismaticwasteland.com/) |
  | 6 | 1/2 HD Dragon |  [Explorer's Design](https://www.explorersdesign.com/) |

## Table of Contents in Navigation Bar

By default, *Just The Docs* doesn't include document headers in the side navigation bar. This plugin injects the table of contents into the navigation bar with collapsible links.

## Link Preview Windows

* Hover over an [internal link](/docs/a-familiar-tower/#biting-fly-giant) to see a reference preview
* Persist windows by holding the SHIFT key
* Close all windows by holding CTRL while closing one
* Minimize windows by double clicking the title bar
* Navigate to an entry later by clicking the link in the title bar
* Eight point window resize

## Custom Image Maps

* Zoom
* Auto-rescale for variable image dimensions (i.e. `width: 50%`)
* Clickable area text
* Works natively with the preview window plug-in

# Making your own

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod  tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim  veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea  commodo consequat. Duis aute irure dolor in reprehenderit in voluptate  velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint  occaecat cupidatat non proident, sunt in culpa qui officia deserunt  mollit anim id est laborum.

# Contributing

You're welcome to submit adventures
