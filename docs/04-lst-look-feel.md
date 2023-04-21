
### Callout
- “Icon on Top Right” as default, revert-able to original via Style Settings
- `no-title` callout-metadata option (e.g. `> [!quote|no-title]`) for callout without title. Using this option will force styling to “Icon on Top Right”

> **Example**
> 
> ![[pic lst no-title callout.png]]
> 

### Custom Dataview Styling via Callout
- Use callout metadata `dv-list-nav` e.g. `[!blank-container|dv-list-nav]` to display dataview list in a button like style

> **Example**
> ````md
> [!blank|no-margin dv-list-nav]
> ```dataview
> LIST WITHOUT ID file.link
> WHERE
> 	date(file.name) = (this.file.day + dur(1d)) OR
> 	date(file.name) = (this.file.day - dur(1d))
> ```
> ```dataview
> LIST WITHOUT ID file.link
> WHERE
> 	(number(split(file.name, "W")[1]) = this.file.day.weekyear AND
> 	  contains(split(this.file.folder,"/"),"journals") ) OR
> 	file.name = "Weekly Review"
> ```
> ````
> ![[pic lst dv navigation.png|400]]

### Frontmatter
- “Compact” styling as default (Reading View only). Revert-able to original via Style Settings
- Hide frontmatter/YAML in Live Preview when line is not active

### Mathjax / Latex
- Alignment for Mathjax / Latex in Lists – left (default), center, and right.

### Floating Action Button
- adopted from [Obsidian You theme](https://github.com/selfire1/obsidian-you-theme)

> **Example**
>
> ![[pic lst FAB.png|400]]

### Tabs