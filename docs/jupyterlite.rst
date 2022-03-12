JupyterLite directive
=====================

``jupyterlite-sphinx`` provides a ``jupyterlite`` directive that allows you to embed JupyterLab in your docs.

.. code-block:: rst

    .. jupyterlite::
       :theme: JupyterLab Dark
       :width: 100%
       :height: 600px

.. jupyterlite::
   :theme: JupyterLab Dark
   :width: 100%
   :height: 600px

You can also pass a Notebook file to open automatically:

.. code-block:: rst

    .. jupyterlite:: dashboard_nc-jupyterlite.ipynb
       :theme: JupyterLab Dark
       :width: 100%
       :height: 600px

.. jupyterlite:: dashboard_nc-jupyterlite.ipynb
   :theme: JupyterLab Dark
   :width: 100%
   :height: 600px
