Installazione
=====

..  Forge:

Installazione di Forge
------------

Per entrare nel nostro server Minecraft, hai bisogno di MinecraftForge.
Usa questo link per installare forge nella versione 1.12.2 (cioè quella del nostro server):
https://files.minecraftforge.net/net/minecraftforge/forge/index_1.12.2.html
Segui le immagini per installare Forge:

.. image:: https://thegruppomultigaming.com/img/1.png
  :width: 600
  :alt: Download Recommended
.. image:: https://thegruppomultigaming.com/img/2.png
  :width: 600
  :alt: Adfocus skip
.. image:: https://thegruppomultigaming.com/img/3.png
  :width: 600
  :alt: Apri il file
.. image:: https://thegruppomultigaming.com/img/4.png
  :width: 600
  :alt: Installa
.. image:: https://thegruppomultigaming.com/img/5.png
  :width: 600
  :alt: Launcher normale
.. image:: https://thegruppomultigaming.com/img/6.png
  :width: 600
  :alt: TLauncher

Installazione delle Mod
----------------

To retrieve a list of random ingredients,
you can use the ``lumache.get_random_ingredients()`` function:

.. autofunction:: lumache.get_random_ingredients

The ``kind`` parameter should be either ``"meat"``, ``"fish"``,
or ``"veggies"``. Otherwise, :py:func:`lumache.get_random_ingredients`
will raise an exception.

.. autoexception:: lumache.InvalidKindError

For example:

>>> import lumache
>>> lumache.get_random_ingredients()
['shells', 'gorgonzola', 'parsley']

