====================
rt.maracas
====================

.. image:: http://blog.redturtle.it/rt.maracas-plone-gadget-brazil-2014/leadImage_preview

A Plone gadget for the 2014 FIFA World Cup Brazil

* `Source code @ GitHub <https://github.com/RedTurtle/rt.maracas>`_
* `Releases @ PyPI <http://pypi.python.org/pypi/rt.maracas>`_


Installation
============

To install `rt.maracas` you simply add ``rt.maracas``
to the list of eggs in your buildout, run buildout and restart Plone.

Then, install `rt.maracas` using the Add-ons control panel.

What you will get
=================

A **maracas_macros view** with some macros:
 - http://localhost:8080/maracas_macros

Two **views** (**maracas-simple** and **maracas-and-whistle**).

You can control them with the query parameters:
    - autoplay (maracas start when page loads)
    - controls (you will get the interface to control the media execution)
    - loop (music will loop until you get crazy)

Example usage of these views:
 - http://localhost:8080/Plone/maracas-simple?controls=1
 - http://localhost:8080/Plone/maracas-and-whistle?autoplay=1&loop=1

You will also get a **Maracas portlet** (see the screenshot of the add form).

Enjoy and good luck for your favourite team!

Authors
=======

This product was developed by RedTurtle Technology team.

.. image:: http://www.redturtle.it/redturtle_banner.png
   :alt: RedTurtle Technology Site
   :target: http://www.redturtle.it/

Don't forget to check the predecessor of this package,
`rt.vuvuzela <https://pypi.python.org/pypi/rt.vuvuzela>`_