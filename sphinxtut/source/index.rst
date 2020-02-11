.. Meine erste Sphinx-Doku documentation master file, created by
   sphinx-quickstart on Tue Feb 11 17:47:36 2020.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Willkommen zu Jörgs ersten Sphinx-Versuchen!
============================================

Schaun wir mal, was **daraus** wird …

.. toctree::
   :maxdepth: 2
   :caption: Contents:


Ein wenig Quellcode:
--------------------

.. code-block:: python
   :caption: Ein kleines Python-Programm
   :dedent: 1
   
    for i in range(7):
        print(i)

Das sieht ja schon ganz gut aus.\ [#]_  Wie man sieht, numeriert *Sphinx* die Fußnoten automatisch.\ [#]_  Jepp, klappt!

Und nun eine kleine Liste:
--------------------------

- Quellcode bereinigen
- Refactoring erforderlich (aber *Daniel Shiffman* erledigt das auch immer später)
- Buch zu Amazon hochladen
- Millionär werden und Geld zählen


Indizes und Tabellen
--------------------

* :ref:`genindex`
* :ref:`search`

.. rubric:: Fußnoten

.. [#] Aber ich bastel noch an den Einrückungen.
.. [#] Hoffe ich jedenfalls.
