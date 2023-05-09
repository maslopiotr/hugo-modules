# Table Of Contents Shortcode (DEPRICATED)

use this new version instead <https://github.com/maslopiotr/hugo-modules/tree/master/table-of-contents>

## Install Module

Add the following code to your module list in the `config/_default/module.toml` file.

```toml
[[imports]]
path = "github.com/maslopiotr/hugo-modules/shortcodes/table-of-contents"
```

Add the following code to your `asstes/scss/main.scss` or `asstes/scss/style.scss` file.

```scss
@import 'toc';
```

<hr>

## Shortcode Implementation

```md
{{< toc >}}
```

<hr>

## Customize Shortcode

```toml
[markup.tableOfContents]
startLevel = 2
endLevel = 5
ordered = true
```
