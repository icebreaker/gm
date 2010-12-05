Markdown Preview plugin for Gedit
========================================

Purpose
-------

If you write documents in *Markdown* as often as I do at some point you'll
love to preview them before pushing somewhere on the web, be it GitHub or a
Jekyll generated blog, you always tweak them before they can be considered ready.

Yet Another Markdown Preview?
-----------------------------

Not really, the existing plugin was old and rusty using the good old GTK2
HTML stuff.

Like I said, this plugin is based on the **original** markdown preview plugin by
**Michele Campeotto** which can be found over [here](http://live.gnome.org/Gedit/MarkdownSupport) .

Another significant difference is that the preview is styled with the original
`GitHub` *cascading stylesheet* which results in a nice and clean look.

The initial `Github Markdown` stylesheet has been grabbed from FNass's [blog](http://fgnass.posterous.com/github-markdown-preview) .

How to install
--------------
Checkout the repository and copy `mp.py`, `mp.gedit-plugin` and `markdown.py`
to `~/.gnome2/gedit/plugins` .

Afterwards, be sure to restart Gedit and activate the `GitHub Markdown Preview` plugin.

How to use
----------
Just press `Ctrl+Shfit+G` with some text in the current document to generate the
preview.

The preview pane will pop-up automatically.

Todo
----

I don't see the point of having *automatic* preview as you type, that would be
slow as hell and way too distracting.

Here are a couple of `nice-to-have` features I have on my list:

* Save the active/open files before preview
* Save the preview/generated HTML to a file (export)
* Customize stylesheet
* Configuration dialog
* Preserve scroll position between previews
* Detach preview window


Note on Patches/Pull Requests
-----------------------------

* Fork the project.
* Make your feature addition or bug fix.
* Send me a pull request. Bonus points for topic branches.

Copyright
---------

Copyright (c) 2010 Mihail Szabolcs. See LICENSE for details.
