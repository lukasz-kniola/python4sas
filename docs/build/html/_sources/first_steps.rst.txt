First Steps
===========

Reading in data:

.. code-block:: sas

        proc sort data=sashelp.class out=class;
          by name;
        run;

(everybody knows about the ``sashelp.class`` dataset)

or

.. code-block:: python

    new_dataset = pd.read_csv("source.csv")


And that's it.

