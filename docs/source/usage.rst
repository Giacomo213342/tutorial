Installazione
=====

..  Forge:

Installazione di Forge su Launcher originale
------------

Per entrare nel nostro server Minecraft, hai bisogno di MinecraftForge.
Usa questo link per installare forge nella versione 1.12.2 (cioè quella del nostro server):
https://files.minecraftforge.net/net/minecraftforge/forge/index_1.12.2.html

Segui le istruzioni per installare Forge sul launcher Premium:

Apri il link, e clicca su Download Recommended.

.. image:: https://thegruppomultigaming.com/img/1.png
  :width: 600
  :alt: Download Recommended

Tutti le cose che ti appariranno sullo schermo sono annunci. Aspetta 5 secondi e poi clicca su SKIP.

.. image:: https://thegruppomultigaming.com/img/2.png
  :width: 600
  :alt: Adfocus skip

Ti si scaricherà un file sul computer. Aprilo.

.. image:: https://thegruppomultigaming.com/img/3.png
  :width: 250
  :alt: Apri il file

Nella finestra per l'installazione di Forge, clicca su Install

.. image:: https://thegruppomultigaming.com/img/4.png
  :width: 400
  :alt: Installa
  
Se usi il Launcher di Minecraft originale (premium) troverai Forge già installato. Scorri in basso tra le versioni e clicca qella chiamata Forge

.. image:: https://thegruppomultigaming.com/img/5.png
  :width: 600
  :alt: Launcher normale

Installazione di Forge su TLauncher (SP)
------------

Se usi TLauncher trovarai Forge direttamente tra le versioni.

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

