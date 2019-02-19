First Steps
===========

Some code:

.. code-block:: python

    dataset = pd.read_csv("file.csv")

or

.. code-block:: sas

    proc sort data=sashelp.class out=class;
      by name;
    run;

to get the ``SASHELP.CLASS`` dataset.
