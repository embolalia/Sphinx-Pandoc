Sphinx-Pandoc
=============

Convert docstrings from your markup of choice to ReStructuredText in Sphinx.

By default, this reads your docstrings in Markdown, and translates it to
ReStructuredText so that Sphinx can deal with it. This hasn't been thoroughly
tested yet, but as long as you aren't doing anything too complicated in your
docstrings, you should be fine. This only does docstrings; it doesn't do
anything to any other files Sphinx reads, so if you have an index.rst for
example, that will still need to be in ReStructuredText.
