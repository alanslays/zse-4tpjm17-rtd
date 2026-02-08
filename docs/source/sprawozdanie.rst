Sprawozdanie RtD
================

Nagłówki (1–4)
--------------

*kod*::

   Nagłówek poziomu 1
   ------------------

*wynik:*

Nagłówek poziomu 1
------------------

*kod*::

   Nagłówek poziomu 2
   ^^^^^^^^^^^^^^^^^^

*wynik:*

Nagłówek poziomu 2
^^^^^^^^^^^^^^^^^^

*kod*::

   Nagłówek poziomu 3
   """""""""""""""""""

*wynik:*

Nagłówek poziomu 3
"""""""""""""""""""

*kod*::

   Nagłówek poziomu 4
   ~~~~~~~~~~~~~~~~~~~

*wynik:*

Nagłówek poziomu 4
~~~~~~~~~~~~~~~~~~~


Akapity
-------

*kod*::

   To jest zwykły akapit tekstowy.

*wynik:*

To jest zwykły akapit tekstowy.


*kod*::

   .. note::
      To jest akapit informacyjny Note.

*wynik:*

.. note::
   To jest akapit informacyjny Note.


*kod*::

   .. tip::
      To jest akapit informacyjny Tip.

*wynik:*

.. tip::
   To jest akapit informacyjny Tip.


Kod
---

*kod*::

   Kod liniowy: ``print("Hello")``

*wynik:*

Kod liniowy: ``print("Hello")``


*kod*::

   .. code-block:: python

      print("Hello World!")
      for i in range(3):
          print(i)

*wynik:*

.. code-block:: python

   print("Hello World!")
   for i in range(3):
       print(i)


Odnośniki (hiperlinki)
----------------------

*kod*::

   Idź do `nagłówka tytułowego <#sprawozdanie-rtd>`_.

*wynik:*

Idź do `nagłówka tytułowego <#sprawozdanie-rtd>`_.


*kod*::

   Idź do mojego `GITHUBA <https://github.com/Youlek07>`_.

*wynik:*

Idź do mojego `GITHUBA <https://github.com/Youlek07>`_.


Listy
-----

*kod*::

   - pierwszy punkt
   - drugi punkt

*wynik:*

- pierwszy punkt  
- drugi punkt  


*kod*::

   1. element pierwszy
   2. element drugi

*wynik:*

1. element pierwszy  
2. element drugi


*kod*::

   Termin
      Opis definicji terminu.

*wynik:*

Termin  
   Opis definicji terminu.


Obraz z podpisem i tekstem alternatywnym
----------------------------------------

*kod*::

   .. figure:: beluga.jpg
      :alt: Kotek
      :align: center

      Kotek

*wynik:*

.. figure:: beluga.jpg
   :alt: Kotek
   :align: center

   Kotek


Tabela
------

*kod*::

   +----------------+----------------+
   | Kolumna 1      | Kolumna 2      |
   +================+================+
   | Komórka A      | Komórka B      |
   +----------------+----------------+
   | Komórka C      | Komórka D      |
   +----------------+----------------+

*wynik:*

+----------------+----------------+
| Kolumna 1      | Kolumna 2      |
+================+================+
| Komórka A      | Komórka B      |
+----------------+----------------+
| Komórka C      | Komórka D      |
+----------------+----------------+
