==========================
beyondskins.phantasmagoria
==========================

Introduction
============

Beyondskins Phantasmagoria Theme is an installable Plone Theme developed by 
`Simples Consultoria`_ using the **theming** and **packaging** 
features available in `plone.app.theming`_.


Requirements
============

- From the Plone 4.1.x To the Plone 4.3 latest versión (https://plone.org/download)
- The ``plone.app.theming`` package (*will be installed as a dependency of this package*)


Screenshots
===========

Layout of the site when viewed in a computer resolution:

.. image:: https://github.com/simplesconsultoria/beyondskins.phantasmagoria/raw/master/beyondskins/phantasmagoria/static/preview.png


Features
========

- It's an installable Plone Theme package.
- After installation from Add-ons controlpanel, this theme is enabled automatically.
- Also it's a simple Diazo package (Zip file).
- It's have support for clean uninstallation.


Installation
============


Zip file
--------

If you are an end user, you might enjoy installation via zip file import.

1. Download a `zip file <https://github.com/simplesconsultoria/beyondskins.phantasmagoria/raw/master/beyondskins.phantasmagoria.zip>`_.
2. Import the theme from the Diazo theme control panel.

Enabling the theme
^^^^^^^^^^^^^^^^^^

Select and enable the theme from the Diazo control panel. That's it!


Buildout
--------

If you are a developer, you might enjoy installing it via buildout.

For install ``beyondskins.phantasmagoria`` package add it to your ``buildout`` section's 
*eggs* parameter e.g.: ::

   [buildout]
    ...
    eggs =
        ...
        beyondskins.phantasmagoria


and then running ``bin/buildout``.

Or, you can add it as a dependency on your own product ``setup.py`` file: ::

    install_requires=[
        ...
        'beyondskins.phantasmagoria',
    ],


Contribute
==========

- Issue Tracker: https://github.com/simplesconsultoria/beyondskins.phantasmagoria/issues
- Source Code: https://github.com/simplesconsultoria/beyondskins.phantasmagoria


License
=======

The project is licensed under the GPLv2.

Credits
-------

- Andre Nogueira (agnogueira at gmail dot com).

.. _`Simples Consultoria`: http://www.simplesconsultoria.com.br/
.. _`plone.app.theming`: https://pypi.org/project/plone.app.theming/
