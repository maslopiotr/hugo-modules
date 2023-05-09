# Vimeo Lite Shortcode (DEPRICATED)

use this new version instead <https://github.com/maslopiotr/hugo-modules/tree/master/videos>

## Installation

Add the following code to your module list in the `config/_default/module.toml` file.

```toml
[[imports]]
path = "github.com/maslopiotr/hugo-modules/shortcodes/vimeo-lite"
```

<hr>

## Shortcode Implementation

```md
<!-- minimal use -->
{{< vimeo-lite 364402896 >}}

<!-- extended use -->
{{< vimeo-lite id="364402896" class="mx-auto" width="600px" style="" attr="" >}}
```
