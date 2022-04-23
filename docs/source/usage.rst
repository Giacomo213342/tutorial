Usage
=====

.. _installation:

Installation
------------

Per entrare nel nostro server Minecraft, hai bisogno di MinecraftForge.
Usa questo link per installare forge nella versione 1.12.2 (cioè quella del nostro server):
https://files.minecraftforge.net/net/minecraftforge/forge/index_1.12.2.html
Segui le immagini se non sai come si installa Forge:

![Download Recommended](https://thegruppomultigaming.com/img/1.png)
![Adfocus skip](https://thegruppomultigaming.com/img/2.png)
![Apri il file](https://thegruppomultigaming.com/img/3.png)
![Installa](https://thegruppomultigaming.com/img/4.png)
![Launcher normale](https://thegruppomultigaming.com/img/5.png)
![TLauncher](https://thegruppomultigaming.com/img/6.png)

Creating recipes
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

