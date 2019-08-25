[![portray - Your Project with Great Documentation.](https://raw.github.com/timothycrosley/portray/master/art/logo.png)](https://timothycrosley.github.io/portray/)
_________________

[![PyPI version](https://badge.fury.io/py/portray.svg)](http://badge.fury.io/py/portray)
[![Build Status](https://travis-ci.org/timothycrosley/portray.svg?branch=master)](https://travis-ci.org/timothycrosley/portray)
[![codecov](https://codecov.io/gh/timothycrosley/portray/branch/master/graph/badge.svg)](https://codecov.io/gh/timothycrosley/portray)
[![Gitter](https://badges.gitter.im/portray/community.svg)](https://gitter.im/portray/community?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge)
[![License](https://img.shields.io/github/license/mashape/apistatus.svg)](https://pypi.python.org/pypi/hug/)
[![Downloads](https://pepy.tech/badge/portray)](https://pepy.tech/project/portray)
_________________

[Read Latest Documentation](https://timothycrosley.github.io/portray/) - [Browse GitHub Code Repository](https://github.com/timothycrosley/portray/)
_________________

> The only thing worse than documentation never written, is documentation written but never read.

**portray** is a Python3 command line tool and library that helps you create great documentation websites for your Python projects with as little effort as possible.

[![Example Usage Gif](https://raw.githubusercontent.com/timothycrosley/portray/master/art/example.gif)](https://raw.githubusercontent.com/timothycrosley/portray/master/art/example.gif)

Key Features:

* **Zero-Config**: No configuration is necessary to use `portray`. Just run `portray` in the root of your Python project and it will find your documentation.
* **Statically Generated**: `portray` websites are easy to host on GitHub pages and other similar services as they are outputted as standard static HTML website.
* **Markdown Aware**: `portray` will automatically include your projects `.md` files and render them into HTML. It will also find and render Markdown within `__doc__` strings.
* **Fully Configurable**: While `portray` doesn't have to be configured, you still can fully configure it withing the standard `pyproject.toml` file.
* **Easily Programmable**: `portray` exposes a clean and simple [Python API](https://timothycrosley.github.io/portray/reference/portray/api/).
* **Searchable**: Out of the box `portray` makes all of your documentation, even autogenerated code references, free-text searchable.
* **Themeable**: `portray` is compatible with all existing [MkDocs Themes](https://github.com/mkdocs/mkdocs/wiki/MkDocs-Themes).

Under the hood portray combines the [Markdown](https://commonmark.org/help/) documentation rendering capabilities provided by [MkDocs](https://www.mkdocs.org/)
with the automatic reference documentation generated by [pdoc3](https://pdoc3.github.io/pdoc/).

