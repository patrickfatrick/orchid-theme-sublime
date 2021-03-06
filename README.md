# The Orchid Color Scheme for Sublime

Based on the original theme made for Brackets, found [here](https://github.com/patrickfatrick/orchid-theme).

This color scheme is intended to be pleasant but still easy to read. It's mostly designed to be used in HTML, CSS/SCSS, and ES6 Javascript (using [JavascriptNext](https://github.com/Benvie/JavaScriptNext.tmLanguage)).

The font used in the screenshots is Monaco, in case you're curious.

## Installation

```bash
$git clone git@github.com:patrickfatrick/orchid-theme-sublime.git
```

Move the file into your Application Support/Sublime Text/Packages/User folder, restart the editor and select the color scheme.

Or use Package Control and search for "orchid-theme-sublime".

### Theme Colors

![Colors](./images/orchid-theme-colors.png)

`#FF9A69` `#B28773` `#262626` `#FFDAA5` `#E84D49` `#DA70D6` `#63E87F` `#FFFAED` `#00B0FF` `#00FFFF`

### CSS/SCSS 

![Orchid Theme in a CSS file](./images/orchid-sublime-css.png)

### HTML

![Orchid Theme in an HTML file](./images/orchid-sublime-html.png)

### JavaScript (with JavascriptNext)

![Orchid Theme in a JS file](./images/orchid-sublime-js.png)

### Markdown (with Markdown Extended)

![Orchid Theme in a Markdown file](./images/orchid-sublime-markdown.png)

### BracketHighlighter

I've also included styles that can be used to override [BracketHighlighter's](https://github.com/facelessuser/BracketHighlighter) defaults for bracket matching. In your bh_core.sublime-settings file you'll want to specify the bracket styles pointing to the brackethighlighter.orchid and the brackethighlighter.orchidUnmatched scopes, like so:

```json
"default": {
	"icon": "dot",
	"color": "brackethighlighter.orchid",
	"style": "solid"
},
"unmatched": {
	"icon": "question",
	"color": "brackethighlighter.orchidUnmatched",
	"style": "solid"
}
```

The final result will look something like this (assuming you set all of the bracket options to point to the brackethighlighter.orchid scope).

![Matching Brackets](./images/orchid-sublime-brackets.png)
