## Note

This is a forked version of [squidfunk/mkdocs-material](https://github.com/squidfunk/mkdocs-material) and used to host [https://canineglioma.verhaaklab.com](https://canineglioma.verhaaklab.com). I am unlikely to update this code on regular basis. Please report issues related to theme directly at [squidfunk/mkdocs-material issue page](https://github.com/squidfunk/mkdocs-material/issues).

Visit [TheJacksonLaboratory/canineglioma](https://github.com/TheJacksonLaboratory/canineglioma) on how-to build and deploy MkDocs built website. Look for [mkdocs.yml](https://github.com/TheJacksonLaboratory/canineglioma/blob/master/mkdocs.yml) for configuration, and [build_methods.sh](https://github.com/TheJacksonLaboratory/canineglioma/blob/master/build_methods.sh) and [serve_test_local.sh](https://github.com/TheJacksonLaboratory/canineglioma/blob/master/serve_test_local.sh) scripts in root directory.

### Installation

I'd used following setup to install MkDocs and additional plugins. Make sure to follow updated documentation, if any at [squidfunk/mkdocs-material](https://github.com/squidfunk/mkdocs-material).

>Prefer python 3.7.3 or higher version.

```sh
pip install mkdocs
## Alternate (unused) via conda
## conda install mkdocs

##### Theme #####
## https://squidfunk.github.io/mkdocs-material/
pip install mkdocs-material

#### Extensions ####
### pymdown-extensions ###
## requirements
pip install markdown
pip install pygments
pip install fontawesome_markdown
## install
pip install pymdown-extensions

#### Plugins ####
pip install mkdocs-git-revision-date-plugin
pip install mkdocs-git-revision-date-localized-plugin
pip install mkdocs-minify-plugin
```

***

Original README

[![Travis][travis-image]][travis-link]
[![Downloads][downloads-image]][downloads-link]
[![Gitter][gitter-image]][gitter-link]
[![PyPI][pypi-image]][pypi-link]
[![dependabot][dependabot-image]][dependabot-link]

  [travis-image]: https://travis-ci.org/squidfunk/mkdocs-material.svg?branch=master
  [travis-link]: https://travis-ci.org/squidfunk/mkdocs-material
  [downloads-image]: https://img.shields.io/pypi/dm/mkdocs-material.svg
  [downloads-link]: https://pypistats.org/packages/mkdocs-material
  [gitter-image]: https://badges.gitter.im/squidfunk/mkdocs-material.svg
  [gitter-link]: https://gitter.im/squidfunk/mkdocs-material
  [pypi-image]: https://img.shields.io/pypi/v/mkdocs-material.svg
  [pypi-link]: https://pypi.python.org/pypi/mkdocs-material
  [dependabot-image]: https://img.shields.io/badge/dependabot-enabled-06f.svg
  [dependabot-link]: https://dependabot.com

# Material for MkDocs

A Material Design theme for [MkDocs][1].

[![Material for MkDocs](https://raw.githubusercontent.com/squidfunk/mkdocs-material/master/docs/assets/images/material.png)][2]

  [1]: https://www.mkdocs.org
  [2]: https://squidfunk.github.io/mkdocs-material/

## Quick start

Install the latest version of Material with `pip`:

``` sh
pip install mkdocs-material
```

Append the following line to your project's `mkdocs.yml`:

``` yaml
theme:
  name: 'material'
```

## What to expect

* Responsive design and fluid layout for all kinds of screens and devices,
  designed to serve your project documentation in a user-friendly way in 37
  languages with optimal readability.

* Easily customizable primary and accent color, fonts, favicon and logo;
  straight forward localization through theme extension; integrated with Google
  Analytics, Disqus and GitHub.

* Well-designed search interface accessible through hotkeys (<kbd>F</kbd> or
  <kbd>S</kbd>), intelligent grouping of search results, search term
  highlighting and lazy loading.

For detailed installation instructions and a demo, visit
https://squidfunk.github.io/mkdocs-material/

## License

**MIT License**

Copyright (c) 2016-2019 Martin Donath

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to
deal in the Software without restriction, including without limitation the
rights to use, copy, modify, merge, publish, distribute, sublicense, and/or
sell copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NON-INFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING
FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS
IN THE SOFTWARE.
