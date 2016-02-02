How to accommodate data column with huge width (more no. of characters)?
========================================================================

In the ‘Data’ section, declare column with datatype as string followed by desired size (character_count) in brackets.

See `more datatypes <../../language/data.html>`_ for details.

.. code-block:: yaml

    D:
        Dataset : [col1,col2, col3 (string(50000))]
