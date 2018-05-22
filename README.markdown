Fork from evidens/vim-twig

Added basic auto-indent support

# vim-twig

## About
Supports Twig PHP templates [http://www.twig-project.org/][1]

Based on Jinja2 syntax highlighting by [Armin Ronacher][2]

-----
## Installation

This scripts bundles is compatible with [vim-addon-manager][3]

You can also install (locally) using [Pathogen][4]:

```sh
mkdir -p ~/.vim/bundle/vim-twig &&
git clone https://github.com/lumiliet/vim-twig ~/.vim/bundle/vim-twig
```

## Changes
### 2016-02-11
- Added basic support for auto-indent

### 2014-03-04
- Also supports html syntax highlighting

### 2011-07-29
- Re-based the syntax highlighting to properly support all tags
- Added support for .html.twig files

[1]: http://www.twig-project.org/
[2]: http://www.vim.org/scripts/script.php?script_id=1856
[3]: https://github.com/MarcWeber/vim-addon-manager
[4]: https://github.com/tpope/vim-pathogen
