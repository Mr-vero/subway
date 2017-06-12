Subway - Based on Zed
======

Welcome to [Subway](http://subwayapp.com), a code editor built using web technologies, designed to rethink some of the assumptions that underly most editors today. Some of the editor's core features are the features it does **not** have:

* Tabs
* Always visible file tree
* Menus and buttons and bells and whistles

What you get instead is a bare bones, simple yet powerful editor that focuses on what matters most: making you as productive at editing code and text as possible. To enable this, Zed has:

* Multiple cursors. Once mastered, you will never edit code the same way again.
* Code completion based on symbols defined in your project, current file and
  snippets.
* Efficient project navigation at various levels of granularity:
    * Files, quickly jump to the file you want
    * Symbols, Zed indexes all symbols defined in your project and lets you
      quickly jump to the one you're interested in
* (Vertical) split views, either 1, 2 or 3 vertical splits.
* Auto-updating preview split for various languages (including markdown and
  coffeescript).
* Editing of local files (via Chrome-specific APIs) and remote files (check the manual on how to do this)

Installation (Standalone)
-------------------------

To build locally:

    $ git clone https://github.com/Mr-vero/subway.git
    $ cd zed
    $ git submodule update --init

After this you can either build the version for your platform of choice:

    $ make apps-mac
    $ make apps-win
    $ make apps-linux32

or

    $ make apps-linux64

The builds end up in `nw/build` and the gzipped versions in `release`.

Inspiration
-----------

Inspiration for Zed comes from:

* [Notational Velocity](http://notational.net): the goto bar combining search
  with new file creation
* Apple's iOS and recent Mac file management: abstraction from whether a file
  is open and by removing the idea that a file has to be explicitly saved.

Technology
----------

* The excellent [ACE](http://github.com/ajaxorg/ace) editor
* [Architect](https://github.com/c9/architect)
* [jQuery](http://jquery.com)
* [Underscore.js](http://underscorejs.org)
* [Require.js](http://requirejs.org)

