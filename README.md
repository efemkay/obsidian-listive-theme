# Listive

> Outliner focused theme with differentiated header style and subtle interface for atomic notes with insight-based points

<!-- updated for v0.4.0 (draft) -->

![](https://img.shields.io/github/v/release/efemkay/obsidian-listive-theme) ![](https://img.shields.io/github/release-date/efemkay/obsidian-listive-theme) ![](https://img.shields.io/github/license/efemkay/obsidian-listive-theme)

<!-- old TOC
<table >
    <tr>
        <td align="center" colspan="5" style="padding:0.5em 0; border:none; ">Quick TOC:</td>
    </tr>
    <tr>
        <td style="padding:0.5em 1em; border: none; border-right: 1px solid DarkSlateGray">
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
    </tr>
</table>
-->

![Listive screenshot](Listive.jpg)

Customisation I did for this theme (started off as a personal theme) are now optional / revert-able to cater for wider userbase. I follows this <a href="#guiding-principles">Guiding Principles</a>, and you may log a feature request as long as it doesn’t sway away for it.

Anyway, you might benefit more using this theme together with [Modular CSS Layout (MCL)](https://github.com/efemkay/obsidian-modular-css-layout) snippets for added functionality on multi columns, cards layout, gallery and image control.


### Table of Contents

- <a href="#guiding-principles">Guiding Principles</a>
- <a href="#features">Features</a>
- <a href="#companion-plugins">Companion Plugins</a>
- <a href="#supported-plugins">Supported Plugins</a>
- <a href="#credits">Credits</a>
- <a href="#support-me">Support Me</a>



## Guiding Principles

**Focus on making outlining a better experience**

- I aim to do that as much as CSS can do, and introduce customisation that are list-centric (especially for the plugins I use. See <a href="#supported-plugins">Supported Plugins</a>)
- *But it doesn’t mean it doesn’t work for normal paragraph style writing – coz I still use for occasional paper write ups*

**Make insights prominent with differentiated headers**

- Each header level has different styling (by default) for a differentiated look to support [lead-in / action title](https://strategy-compass.com/en/action-titles-slides-headings/) style headers, focusing on the gist.
- *But it can be reverted to original (or further customised) if so desire.*

**Minimise distraction through subtle UI changes**

- There will be (1) no hard lines (or borders) except for typography, and (2) minimal colors to be used for UI, focusing instead on shades. This is to minimise distraction but not to the extent of hiding default UI (like sidebar ribbon).


## Features

#### Differentiated Headers (customisable)

Custom font and spacing for Headers in lists vs in normal paragraph. By default, the font family is paired for H1/H2, H3/H4 and H5/H6 but that can be manually changed via Style Settings. There's also custom spacing for Headers.

![](docs/assets/hero-differentiated-header.png)


### List-related Features

**List Embed or Inline Embed for "clean" embed in lists**

Use this feature to seamlessly or cleanly embed your list block (your block of notes that are in a list/outline style). Enable globally via Style Settings or specify for only specific embed via link alias (i.e. `![[notename#^xyz123|list-embed]]`).

Use `![[notename#^xyz123|inline-embed]]` when the targetting note block isn't a list block



![](docs/assets/hero-list-inline-embed.png)

**List bullet styling options**

Choose from 3 different options of bullet styling to further visually differentiate your list level - (1) disc only (default), (2) alternating disc-circle, and sequential disc-circle-square. Change via Style Settings.



### Mobile-friendly

I use Obsidian on the mobile for reference frequently (and sometimes to edit notes), so this theme is constantly tested to be responsive and optimal to mobile view.

As such, Floating Action Button (FAB) for edit/read is enabled by default. There's also a second FAB for you to assign any button using Commander plugin (the first button you add to "Page Header" section). No worries, you can disable it via Style Settings if you don't like it. Also you can adjust the position of either FAB via Style Settings.



#### Custom Dataview Styling via Callout

Use callout metadata `dv-list-nav` e.g. `[!blank-container|dv-list-nav]` to display dataview list in a button like style. Alternatively, use `dv-list-button` to make it really button like...



![](docs/assets/hero-dv-list-nav-button.png)



#### Auxiliary Customisation


**Color Schemes**

Currently there's only color scheme i.e. Base (grayscale) and Discord. You can change it via Style Settings


**Callout styling**

Default Listive design is “Icon on Top Right” but you can revert it to original via Style Settings.

Additionally, you may also do a callout without title (useful for quotes) with `no-title` callout-metadata option (e.g. `> [!quote|no-title]`). Btw, using this option will force styling to “Icon on Top Right”


**Frontmatter compact and always "collapsed" styling**

“Compact” styling as default (Reading View only). You can revert back to original via Style Settings. For Live Preview, you can enable "Hide Frontmatter in LP" via Style Settings to make the frontmatter always "collapsed" except when active or on hover.


**Alignment for Mathjax / Latex in List**

You can adjust whether math equation in a list/bullet is aligned to left (default, makes more sense in this case), center (default Obsidian behaviour), or right (useful for RTL).


### Planned Features

- [ ] Mermaid custom styling (especially Gantt chart)
- [ ] Multiple Table Design (alternate rows styling and perhaps first column)
- [ ] Different background for Journal (to have custom background in Reading View for section with specific header text)
- [x] Adjustable position for FAB


> This theme is still work in progress. There are more features I have in mind -- those will be updated/released in due time.


## Companion Plugins

Listive works best with the following plugins installed to enable more complicated features and give more control to refine the look and feel.

- ~~**Contextual Typography** plugin for advanced layout features such as custom spacing for 1st para/list.~~ I've migrated all my CSS to utilise `:has()`, as such the plugin is no longer required. But in turn, your Obsidian must be installed with installer v1.1.9 or higher (note that Obsidian has two version numbers i.e. (a) app version and (b) installer version)
- **Style Settings** plugin for refining the look and feel including choosing/creating custom color scheme.


## Community Plugins UI Customisation

These are the plugins I use personally on frequent basis, and with that, I make some customisation for better UI

- Outliner and Zoom by vslinko
- Strange New World by TfTHacker
- Query Control by nothingislost (but the plugin partly breaks with Obsidian v1.2 onwards)


## Credits

- chrisgrieser (aka pseudometa) for [Theme Design Utilities](https://github.com/chrisgrieser/obsidian-theme-design-utilities) plugin that I use frequently to test mobile UIUX as well helps given in discord
- [Obsidian You theme](https://github.com) for the FAB I adopted (because I find it very useful when using on a phone)


## Support Me

I do this on my free time for personal joy. However, a cup of coffee or two would motivate me further! If you like what I do, and want to contribute back, you can support me via Ko-fi

<a href='https://ko-fi.com/M4M3C77PF' target='_blank'><img height='36' style='border:0px;height:36px;' src='https://cdn.ko-fi.com/cdn/kofi1.png?v=3' border='0' alt='Buy Me a Coffee at ko-fi.com' /></a>
