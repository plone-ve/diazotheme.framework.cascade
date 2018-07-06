============================
diazotheme.framework.cascade
============================

This package provides the diazo framework implementation of the 
`Cascade framework`_. For documentation on the 
framework itself, check the website.


Introduction
============

``diazotheme.framework.cascade`` package using the **theming** and 
**packaging** features available in the `diazoframework.plone`_ core 
package for create Diazo_ theme using `plone.app.theming`_.

``diazotheme.framework.cascade`` package contains the following diazo implementations: 

- **Cascade Starter Theme**, is the Twitter Bootstrap starter theme on diazo based.


Screenshots
===========


Cascade Starter Theme
---------------------

Layout of the site when viewed in a computer resolution:

.. image:: https://github.com/TH-code/diazotheme.framework.cascade/raw/master/docs/screenshot0.png
  :alt: Cascade Starter Theme
  :align: center


Requirements
============

- From the Plone 4.1.x To the Plone 4.3 latest version (https://plone.org/download)
- The ``plone.app.theming`` package (*You will need enable it to use this package*)


Features
========

- This support the *Cascade CSS* resources for version 1.0.
- Provides the diazo rules for *Cascade Starter* theme.
- Included Diazo rules for the ``head``, ``portlets`` and ``structures`` *Cascade* CSS styles.


Installation
============


Buildout
--------

If you are a developer, you might enjoy installing it via buildout.

For install ``diazotheme.framework.cascade`` package add it to your ``buildout`` section's 
*eggs* parameter e.g.: ::

   [buildout]
    ...
    eggs =
        ...
        diazotheme.framework.cascade


and then running ``bin/buildout``.

Or, you can add it as a dependency on your own product ``setup.py`` file: ::

    install_requires=[
        ...
        'diazotheme.framework.cascade',
    ],



Enabling the theme
^^^^^^^^^^^^^^^^^^

Select and enable the theme from the Diazo control panel. That's it!


Themes that use it
==================

This framework is used by:

`diazotheme.framework.cascade`_
    which contains themes that can both be used as starters for your own *Cascade* based theme.

For more frameworks see: the `diazoframework.plone`_ package.


Resources
=========

The resources of this framework can be reached through

- **Cascade Starter Theme**
    ``/++theme++cascade-framework``

There are placed at ``diazotheme.framework.cascade/diazotheme/framework/cascade/static/`` directory 
with following resources files:

::

    _ static
      Provides the resources from *Cascade Starter Theme*.
      _ cascade
      _ manifest.cfg
      _ preview.png
      _ rules.xml
      _ rules
        _ columns.xml
        _ head-base.xml
        _ head-theme.xml


Contribute
==========

- Issue Tracker: https://github.com/TH-code/diazotheme.framework.cascade/issues
- Source Code: https://github.com/TH-code/diazotheme.framework.cascade


License
=======

The project is licensed under the GPLv2.


Credits
-------

- Thijs Jonkman (t.jonkman at gmail dot com).


Amazing contributions
---------------------

- Leonardo J. Caballero G. aka macagua (leonardocaballero at gmail dot com).

You can find an updated list of package contributors on https://github.com/TH-code/diazotheme.framework.cascade/contributors

.. _`Cascade framework`: http://www.cascade-framework.com/
.. _`diazotheme.framework.cascade`: https://github.com/TH-code/diazotheme.framework.cascade
.. _`diazoframework.plone`: https://github.com/TH-code/diazoframework.plone#current-frameworks
.. _`Diazo`: http://diazo.org
.. _`plone.app.theming`: https://pypi.org/project/plone.app.theming/
