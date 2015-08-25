# github_flavored_markdown 

_(Note: this forked package has been altered to work better with [highlight.js][1], instead of [github.com's][2] [Linguist][3].)_ 

Package github_flavored_markdown provides a GitHub Flavored Markdown renderer
with fenced code block highlighting, clickable header anchor links.

The functionality should be _ALMOST_ equivalent to the GitHub Markdown API endpoint specified at
https://developer.github.com/v3/markdown/#render-a-markdown-document-in-raw-mode, except
the rendering is performed locally.

See examples for how to generate a complete HTML page, including CSS styles.

Installation
------------

```bash
go get -u github.com/indraniel/github_flavored_markdown
```

License
-------

- [MIT License](http://opensource.org/licenses/mit-license.php)

[1]: https://highlightjs.org/
[2]: https://help.github.com/articles/github-flavored-markdown/
[3]: https://github.com/github/linguist
