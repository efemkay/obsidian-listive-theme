# Listive
> Outliner focused theme with differentiated header style and subtle interface for atomic notes with insight-based points

![](https://img.shields.io/github/v/release/efemkay/obsidian-listive-theme) ![](https://img.shields.io/github/release-date/efemkay/obsidian-listive-theme) ![](https://img.shields.io/github/license/efemkay/obsidian-listive-theme) ![](https://img.shields.io/github/downloads/efemkay/obsidian-listive-theme/total)

<table >
<tr>
<td style="padding:0.5em 0; border:none;">Quick TOC:</td>
</tr>
<tr>
<td style="padding:0.5em 1em 0.5em 0; border: none; border-right: 1px solid DarkSlateGray">
    <a href="#guiding-principles">Guiding Principles</a>
</td>
<td style="padding:0 1em; border: none; border-right: 1px solid DarkSlateGray">
    <a href="#features">Features</a>
</td>
<td style="padding:0 1em; border: none; border-right: 1px solid DarkSlateGray">
    <a href="#companion-plugins">Companion Plugins</a>
</td>
<td style="padding:0 1em; border: none; border-right: 1px solid DarkSlateGray">
    <a href="#credits">Credits</a>
</td>
<td style="padding:0 1em; border: none; border-right: 1px solid DarkSlateGray">
    <a href="#support-me">Support Me</a>
</td>
</tr></table>

![Listive screenshot](Listive.jpg)

## Guiding Principles
- **Focus on making outlining a better experience**
    - as much as CSS can provide to support relevant plugins
- **Make insights prominent with differentiated headers**
    - to complement writing H4-H6 as insight gist
- **Minimise distraction through subtle UI changes**
    - No hard lines except for typography
    - Minimise distraction without disruption access to icons
    - Minimal colors used for UI, focusing on shades

## Features

#### Differentiated Headers (customisable)
- Custom font and spacing for Headers in lists vs in normal paragraph
    - By default, pairing H1/H2, H3/H4 and H5/H6
    - Custom spacing for Headers mainly for Reading View

#### Color Schemes
Currently there's only color scheme i.e. Base (grayscale) and Discord. You can change it via Style Settings

#### List Embed for "clean" embed in lists
Two options to use List Embed -- per embed basis or global/vault wide. For Live Preview use, it's still experimental, and you able to adjust the positioning via Style Settings.
- For per embed basis, put `list-embed` in the alias part e.g. `![[Why I Use Obsidian|list-embed]]`
- For vault wide, enable the "Enable List Embed vault-wide" option via Style Settings

#### Custom Dataview Styling via Callout
Use callout metadata `dv-list-nav` e.g. `[!blank-container|dv-list-nav]` to display dataview list in a button like style

#### Auxiliary Customisation
- List bullet styling options – default (disc only), alternating disc-circle, and disc-circle-square. Change via Style Settings
- Callout styling options – icon-on-top-right (default), and "standard". Change via Style Settings
- `no-title` callout-metadata option (e.g. `> [!quote|no-title]`) for callout without title. Styling similar to icon-on-top-right style
- Frontmatter compact styling. Change via Style Settings to get back to “standard” styling
- Alignment for Mathjax / Latex in Lists – left (default), center, and right.
- Floating Action Button, adopted from [Obsidian You theme](https://github.com/selfire1/obsidian-you-theme)
- (not yet ready) Mermaid
- (not yet ready) Multiple Table Design
- (not yet ready) Different background for Journal

> This theme is still work in progress. There are more features I have in mind -- those will be updated/released in due time.

## Companion Plugins
Listive works best with the following plugins installed to enable more complicated features and give more control to refine the look and feel.
- **Contextual Typography** plugin for advanced layout features such as custom spacing for 1st para/list.
- **Style Settings** plugin for refining the look and feel including choosing/creating custom color scheme.

## Credits
- [Obsidian You theme](https://github.com) for the FAB I adopted (because I find it very useful when using on a phone)

## Support Me
I do this on my free time for personal joy. However, a cup of coffee or two would motivate me further! If you like what I do, and want to contribute back, you can support me via Ko-fi

<a href='https://ko-fi.com/M4M3C77PF' target='_blank'><img height='36' style='border:0px;height:36px;' src='https://cdn.ko-fi.com/cdn/kofi1.png?v=3' border='0' alt='Buy Me a Coffee at ko-fi.com' /></a>
