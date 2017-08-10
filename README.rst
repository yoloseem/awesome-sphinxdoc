Awesome Sphinx (Python Documentation Generator)
===============================================

A curated list of awesome extra libraries, software and resources for
Sphinx_ (Python Documentation Generator). Inspired by
awesome-sqlalchemy_.  (See also other `awesome lists`__!)

Licensed under a `Creative Commons Attribution-ShareAlike 4.0 International
License`__.

Your contributions are welcome.

.. _Sphinx: http://sphinx-doc.org/
.. _awesome-sqlalchemy: https://github.com/dahlia/awesome-sqlalchemy
__ https://github.com/sindresorhus/awesome
__ http://creativecommons.org/licenses/by-sa/4.0/

.. contents:: Table of Contents
   :backlinks: none
   :depth: 3


Sphinx
------------
| Wikipedia: `<https://en.wikipedia.org/wiki/Sphinx_(documentation_generator)>`__
| Homepage: http://sphinx-doc.org/
| Source: git https://github.com/sphinx-doc/sphinx

| Docs: http://sphinx-doc.org/contents.html
| Docs: http://sphinx-doc.org/develop.html
| Docs: http://sphinx-doc.org/rest.html
| Docs: http://docutils.sourceforge.net/docs/ref/rst/restructuredtext.html
| Docs: http://docutils.sourceforge.net/docs/ref/rst/restructuredtext.html#line-blocks
| Docs: http://docutils.sourceforge.net/docs/ref/rst/directives.html
| Docs: https://docs.python.org/devguide/documenting.html#sections
| Docs: http://sphinx-doc.org/markup/index.html
| Docs: http://sphinx-doc.org/glossary.html


Articles & Presentations
------------------------

`Documenting Your Project With Sphinx`_
   Exercises for the Sphinx Tutorial that Brandon Rhodes often gives at PyCon.

.. _Documenting Your Project With Sphinx: https://github.com/brandon-rhodes/sphinx-tutorial


Extensions
----------
| Source: git https://github.com/sphinx-doc/sphinx/tree/master/sphinx/ext
| Source: hg https://bitbucket.org/birkenfeld/sphinx-contrib
| Docs: http://sphinx-doc.org/extensions.html
| Docs: http://sphinx-doc.org/extdev/index.html
| Docs: http://sphinx-doc.org/extdev/appapi.html

breathe_
   ReStructuredText and Sphinx bridge to Doxygen.

javasphinx_
   Sphinx extension for documenting Java projects.

numpydoc_
   `NumPy`_'s Sphinx extensions.

Releases_
   A Sphinx changelog-generating extension.

sphinx-autodoc-annotation_
   Use Python 3 annotations in sphinx-enabled docstrings.

sphinx-autodoc-typehints_
   Type hints support for the Sphinx autodoc extension

sphinx-autodoc-napoleon-typehints_
   Type hints support for the Sphinx autodoc extension with support for NumPy
   and Google style docstrings (see sphinxcontrib-napoleon_).

sphinx-fortran-extension_
   A Fortran domain and autodocumentation module for Sphinx.

sphinx-git_
   git Changelog for Sphinx.

Sphinx-prompt_
   Sphinx directive to add unselectable prompt.

Sphinx-pyreverse_
   Simple sphinx wrapper around pyreverse (from pylint suit) to generate
   UML diagramms from modules.

sphinxcontrib-autojs_
   The auto JavaScript documentation Sphinx extension.

sphinxcontrib-autoprogram_
   Provides an automated way to document CLI programs.

sphinxcontrib-blockdiag_
   Sphinx extension for embedding blockdiag_ diagrams.

sphinxcontrib-cldomain_
   Common Lisp domain for Sphinx.

sphinxcontrib-docbookrestapi_
   Sphinx extension that generates documentation for api-site from RST files.

sphinxcontrib-fulltoc_
   Extension for Sphinx to make the sidebar show a full table of contents
   instead of just the local headings.

sphinxcontrib-httpdomain_
   Provides a Sphinx domain for describing RESTful HTTP APIs.
   Also supports reflection for Flask, Bottle, and Tornado apps.

cornice.ext.sphinxext_
   Sphinx extension to build RESTful HTTP API documentation from
   Pyramid Cornice docstrings.

sphinxcontrib-programoutput_
   Sphinx extension to include program output into documents.

sphinxcontrib-napoleon_
   Napoleon is a pre-processor that parses NumPy and Google style docstrings.

Tut_
   Tut is a tool that helps you write tutorial style documentation using
   Sphinx.

Hieroglyph_
   Hieroglyph is an extension for Sphinx which builds HTML slides from
   ReStructuredText documents.

Sphinx-Needs_
   Sphinx-Needs allows the definition, linking, and filtering of need-objects: requirements, specifications, implementations, test cases, and more.

.. _blockdiag: http://blockdiag.com/en/blockdiag/index.html
.. _breathe: https://github.com/michaeljones/breathe
.. _javasphinx: https://github.com/bronto/javasphinx
.. _NumPy: http://www.numpy.org/
.. _numpydoc: https://github.com/numpy/numpydoc
.. _Releases: https://github.com/bitprophet/releases
.. _sphinx-autodoc-annotation: https://github.com/hsoft/sphinx-autodoc-annotation
.. _sphinx-autodoc-typehints: https://github.com/agronholm/sphinx-autodoc-typehints
.. _sphinx-autodoc-napoleon-typehints: https://github.com/daviskirk/sphinx-autodoc-napoleon-typehints
.. _sphinx-fortran-extension: https://github.com/VACUMM/sphinx-fortran
.. _sphinx-git: https://github.com/OddBloke/sphinx-git
.. _Sphinx-prompt: http://sbrunner.github.io/sphinx-prompt/
.. _Sphinx-pyreverse: https://github.com/alendit/sphinx-pyreverse
.. _sphinxcontrib-autojs: https://github.com/lunant/sphinxcontrib-autojs
.. _sphinxcontrib-autoprogram: https://pythonhosted.org/sphinxcontrib-autoprogram/
.. _sphinxcontrib-blockdiag: http://blockdiag.com/en/blockdiag/sphinxcontrib.html
.. _sphinxcontrib-cldomain: http://cldomain.russellsim.org/
.. _sphinxcontrib-docbookrestapi: https://github.com/stackforge/sphinxcontrib-docbookrestapi
.. _sphinxcontrib-fulltoc: https://github.com/dreamhost/sphinxcontrib-fulltoc
.. _sphinxcontrib-httpdomain: https://pythonhosted.org/sphinxcontrib-httpdomain/
.. _cornice.ext.sphinxext: http://cornice.readthedocs.io/en/latest/sphinx.html
.. _sphinxcontrib-programoutput: https://github.com/NextThought/sphinxcontrib-programoutput
.. _sphinxcontrib-napoleon: http://sphinxcontrib-napoleon.readthedocs.io/en/latest/
.. _Tut: https://github.com/nyergler/tut
.. _Hieroglyph: http://hieroglyph.io/
.. _Sphinx-Needs: http://sphinxcontrib-needs.readthedocs.io/en/latest/

Internationalizations
---------------------

sphinx-intl_
   Sphinx utility that make it easy to translate and to apply translation.

.. _sphinx-intl: https://pypi.python.org/pypi/sphinx-intl


Miscellaneous
-------------

django-sphinxdoc_
   Integrate Sphinx documentation into a Django-powered website. Allows you to
   use your sites templates, auth and so on. Offers search via Haystack.

ome-documentation_
   Sphinx-based documentation for the Open Microscopy Environment.

riv.vim_
   ReStructured text editing extensions for Vim, GVim, MacVim;
   optionally with `InstantRst`_ gevent live reload.

sphinx-gui_
   Desktop GUI for editing Sphinx docs.

sphinx-markdown-sample_
   Markdown based sphinx the documentation generator sample.

tinkerer_
   Blog engine static HTML5 generator
   with categories, tags, landing page, nav sidebar,
   RSS powered by Sphinx and responsive Jinja templates.

ablog_
   ABlog is a Sphinx extension that converts any documentation
   or personal website project into a full-fledged blog with
   atom feeds, archive pages, blog sidebars, Disqus integration,
   Font-Awesome integration and easy GitHub Pages deploys

.. _django-sphinxdoc: https://pypi.python.org/pypi/django-sphinxdoc
.. _InstantRst: https://github.com/Rykka/InstantRst
.. _ome-documentation: https://github.com/openmicroscopy/ome-documentation
.. _riv.vim: https://github.com/Rykka/riv.vim
.. _sphinx-gui: https://github.com/audreyr/sphinx-gui
.. _sphinx-markdown-sample: https://github.com/mctenshi/sphinx-markdown-sample
.. _tinkerer: https://github.com/vladris/tinkerer
.. _ablog: http://ablog.readthedocs.io/

Themes
------
| Docs: http://sphinx-doc.org/theming.html
| Docs: http://sphinx-doc.org/templating.html
| Source: git https://github.com/sphinx-doc/sphinx/tree/master/sphinx/themes

Alabaster_
   Modified Kr Sphinx doc theme.

flask-sphinx-themes_
   Sphinx Themes for Flask related projects and Flask itself.

`krTheme Sphinx Style`_
   Sphinx theme Kenneth Reitz uses for most projects e.g. Requests_.

`Sphinx Readable Theme`_
   A clean and readable Sphinx theme with focus on autodoc – documentation
   from docstrings.

sphinx-better-theme_
   A theme for Sphinx that looks nice, is easy to style with CSS, works well
   on small screens and mobile devices, and organizes the page better.

sphinx_rtd_theme_
   Sphinx theme for `readthedocs.io`_.

sphinx-theme-graphite_
   A slightly muted light-on-dark theme for the Sphinx document generator
   using only CSS.

sphinxjp.themes.basicstrap_
   Sphinx theme built with responsive `Bootstrap`_.

sublee-sphinx-themes_
   Sphinx themes Heungsub Lee uses for his projects e.g. Energy_, Korean_,
   Ranking_, TrueSkill_.

sphinx-py3doc-enhanced-theme_
   A theme based on the theme of https://docs.python.org/3/ with some responsive enhancements.

sphinx-bootstrap-theme_
   Integrates Bootstrap CSS/Javascript framework responsive design with any Bootswatch CSS themes.

sphinx-foundation-theme_
   Theme based on the Foundation 4 CSS framework.

sphinx-nameko-theme_
   Forked from Sphinx Readable Theme, combined with elements of the Read The Docs theme.

sphinx-guzzle-theme_
   Sphinx theme used by Guzzle: http://guzzlephp.org

sphinx-hbp-theme_
   HumanBrainProject Collaboratory Sphinx Theme.

crate-docs-theme_
   This project provides a Sphinx theme for Crate's documentation that is compatible with ReadTheDocs.

solar-theme_
   Solar is an attempt to create a theme for the Python Sphinx documentation generator based on the Solarized color scheme.

sphinxtrap-theme_
   Sphinxtrap is a minimalist bootstrap2-based + fontawesome sphinx theme.

mdn-sphinx-theme_
   This is a version of the Mozilla Developer Network theme, for the Sphinx documentation engine.

sphinx_adc_theme_
   The Apple Developer Connection theme for sphinx

.. _Alabaster: https://github.com/bitprophet/alabaster
.. _bootstrap: https://github.com/twbs/bootstrap
.. _Energy: http://pythonhosted.org/energy/
.. _flask-sphinx-themes: https://github.com/pallets/flask-sphinx-themes
.. _Korean: https://pythonhosted.org/korean/
.. _krTheme Sphinx Style: https://github.com/kennethreitz/kr-sphinx-themes
.. _Ranking: http://pythonhosted.org/ranking/
.. _readthedocs.io: https://readthedocs.io
.. _Requests: http://docs.python-requests.org/
.. _Sphinx Readable Theme: https://sphinx-readable-theme.readthedocs.io/en/latest/
.. _sphinx-better-theme: http://sphinx-better-theme.readthedocs.io/en/latest/
.. _sphinx_rtd_theme: https://github.com/snide/sphinx_rtd_theme
.. _sphinx-theme-graphite: https://github.com/Cartroo/sphinx-theme-graphite
.. _sphinxjp.themes.basicstrap: https://github.com/tell-k/sphinxjp.themes.basicstrap
.. _sublee-sphinx-themes: https://github.com/sublee/sublee-sphinx-themes
.. _TrueSkill: http://trueskill.org/
.. _sphinx-py3doc-enhanced-theme: https://github.com/ionelmc/sphinx-py3doc-enhanced-theme
.. _sphinx-bootstrap-theme: https://github.com/ryan-roemer/sphinx-bootstrap-theme
.. _sphinx-foundation-theme: https://github.com/peterhudec/foundation-sphinx-theme
.. _sphinx-nameko-theme: https://github.com/onefinestay/sphinx-nameko-theme
.. _sphinx-guzzle-theme: https://github.com/guzzle/guzzle_sphinx_theme
.. _sphinx-hbp-theme: https://github.com/HumanBrainProject/hbp-sphinx-theme/
.. _crate-docs-theme: https://github.com/crate/crate-docs-theme
.. _solar-theme: https://github.com/vimalkvn/solar-theme
.. _sphinxtrap-theme: https://github.com/jfardello/Sphinxtrap
.. _mdn-sphinx-theme: https://github.com/mdn/sphinx-theme
.. _sphinx_adc_theme: https://github.com/mga-sphinx/sphinx_adc_theme

Publication
-----------

`Read the Docs`_
   Read the Docs hosts documentation, making it fully searchable and easy to
   find.  You can import your docs using any major version control system,
   including Mercurial, Git, Subversion, and Bazaar.  It supports webhooks__
   so your docs get built when you commit code.  There's also support for
   versioning so you can build docs from tags and branches of your code in
   your repository. A `full list of features`__ is available.

Okydoky_
   Automated docs builder using Sphinx/GitHub/Distribute for private use.

sphinx-autobuild_
   Watch a Sphinx directory and rebuild the documentation when a change is
   detected.

sphinx-server_
   A universal Sphinx Server based on sphinx-autobuild_ with Docker support
   that can be used in production (self-hosted) and for documentation development,
   bundled with *PlantUML*, *Graphviz* and *HTTP authentication*.

sphinx-me_
   Wraps your README-only projects in a dynamic Sphinx shell for hosting on
   `Read the Docs`_.

`Sphinx to GitHub`_
   Script to prepare Sphinx html output for `GitHub Pages`_.

`ghp-import`_
   Script to overwrite a ``gh-pages``/``master`` branch with a ``.nojekyll`` file for `GitHub Pages`_.

.. _ghp-import: https://pypi.python.org/pypi/ghp-import
.. _GitHub Pages: https://pages.github.com/
.. _Okydoky: https://pypi.python.org/pypi/Okydoky
__ http://read-the-docs.readthedocs.io/en/latest/webhooks.html
__ http://read-the-docs.readthedocs.io/en/latest/features.html
.. _Read the Docs: https://readthedocs.io/
.. _sphinx-autobuild: https://github.com/GaretJax/sphinx-autobuild
.. _sphinx-server: https://github.com/dldl/sphinx-server
.. _sphinx-me: https://github.com/stephenmcd/sphinx-me
.. _Sphinx to GitHub: https://github.com/michaeljones/sphinx-to-github
