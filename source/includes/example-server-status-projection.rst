|operation-name| includes all fields by default, except
:data:`~serverStatus.workingSet` :data:`~serverStatus.rangeDeleter`,
and some content in the :data:`~serverStatus.repl` document.

.. note::

   You may only dynamically include top-level fields from the
   :doc:`serverStatus </reference/command/serverStatus>`
   document that are not included by default. You
   can exclude any field that |operation-name| includes by
   default.
