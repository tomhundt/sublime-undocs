# Sublime Text Unofficial Documentation

**Update 2020-03-20: Because @guillermooo is AWOL, resulting in both the build pipeline and the domain being effectively unmaintained, the project has been forked to https://github.com/sublimetext-io/docs.sublimetext.io, accessible at https://docs.sublimetext.io/.** *See  [#270](https://github.com/guillermooo/sublime-undocs/issues/270) for details.*

---

We started this project
to fill the gaps in the Sublime Text [official documentation][off-docs].

**[Read this guide][undocs]** online for free.

You can follow our progress here and
on our public [Trello board][trello].


## Contributing

We accept error reports and requests for new content
via our [issue tracker][issues],
and encourage you to send pull requests
(but we cannot guarantee
they will always be merged).

**Please follow our style guidelines
as described in [CONTRIBUTING.md](./CONTRIBUTING.md).**

This repository includes a `.sublime-project`
with predefined settings and a build system
that builds the HTML docs using Sphinx.


### Building (HTML Preview)

In order to build and preview the docs,
you'll need [Sphinx][],
which in turn **requires Python 2.7**.
Python 3+ will not work.

    pip install sphinx

By default, the docs' preview will display
a standard Sphinx theme,
but you can install
and use ReadTheDocs' theme
if you prefer that:

    pip install sphinx_rtd_theme

If this theme is available,
the build system will pick it up.

After the build is finished,
you can open `build/html/index.html`
in your browser to see the guide.


[off-docs]: http://sublimetext.com/docs/3
[undocs]: http://docs.sublimetext.info/
[trello]: https://trello.com/b/ArLlY4X7/sublime-text-unofficial-documentation

[issues]: https://github.com/guillermooo/sublime-undocs/issues
[Sphinx]: http://sphinx-doc.org/
