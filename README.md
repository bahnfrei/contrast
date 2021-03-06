---
title: "About"
permalink: "/about/"
layout: page
---

## Installation

Just fork the repo and adjust the `_config.yml` to use with [Github Pages](https://pages.github.com/) and your page is done.

## Features

ORIG (niklasbuschmann):
 - supports dark mode on macOS Mojave
 - optional sidebar
 - MathJax support
 - no external ressources
 - included archive page
 - supports pagination
 - feed generation
 - responsive
 - syntax highlighting
 - supports comments via [disqus](https://disqus.com/) or [isso](http://posativ.org/isso/)

MOD (bahnfrei):
 - custom styles (includes assets/css/custom.sass)
 - custom archive and category page
 - simple search function using lunr
 - simple gallery with lightbox support
 - local video embedd functionality

## Based on

- [Hyde](https://github.com/poole/hyde)
- [Minima](https://github.com/jekyll/minima)
- [Lagrange](https://github.com/LeNPaul/Lagrange)
- [Font Awesome](http://fontawesome.io/)
- [KaTeX](https://katex.org/)
- [Pygments](https://github.com/richleland/pygments-css)

## Installation (jekyll-remote-theme method)

You can use this theme with the `jekyll-remote-theme` plugin. Just create an empty repo, copy over the `index.html` file and add this to your `_config.yml`:

```yaml
remote_theme: bahnfrei/contrast


plugins:
  - jekyll-remote-theme
```

## License

[public domain](http://unlicense.org/)

## Screenshots

![Screenshot](/assets/images/home.png)

![Screenshot](/assets/images/photo.png)

![Screenshot](/assets/images/categories.png)

![Screenshot](/assets/images/archive.png)

![Screenshot](/assets/images/search.png)

