Grvlms plugin cookiecutter 🍪
============================

This is a `cookiecutter`__ for getting started with `Grvlms plugins`__. It will generate a base scaffold for an empty grvlms plugin that does, well, nothing.

Requirements
------------

::

    pip install cookiecutter

Usage
-----

::
    
    cookiecutter https://github.com/groovetch/cookiecutter-grvlms-plugin.git

Once you have generated your plugin, you can start using it right away (even if it won't do anything)::
  
    pip install -e ./grvlms-myplugin
    grvlms plugins list # your plugin should appear here
    grvlms plugins enable myplugin # hack at it!

License
-------

This software is licensed under the terms of the `AGPLv3 <https://www.gnu.org/licenses/agpl-3.0.en.html>`__.
