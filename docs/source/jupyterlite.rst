JupyterLite directive
=====================

``jupyterlite-sphinx`` provides a ``jupyterlite`` directive that allows you to embed JupyterLab in your docs.

.. code-block:: rst

    .. jupyterlite::
       :width: 100%
       :height: 600px

.. jupyterlite::
   :width: 100%
   :height: 600px

You can also pass a Notebook file to open automatically:

.. code-block:: rst

    .. jupyterlite:: dashboard_nc-jupyterlite.ipynb
       :width: 100%
       :height: 600px

.. jupyterlite:: dashboard_nc-jupyterlite.ipynb
   :width: 100%
   :height: 600px
