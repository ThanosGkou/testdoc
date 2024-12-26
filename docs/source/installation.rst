************
Installation
************



.. _installation:

.. class:: right
Installation / Upgrade
======================
It's best to create a dedicated **virtual environment** to install and launch exso.


Auto-Mode
---------

Recommended for users:

* with zero to little programming skills,
* that are not familiar with virtual environments,
* that want to make a quick and effortless review of the tool.

Process
""""""""


* Download `ExSO.xlsm <https://github.com/ThanosGkou/exso/blob/main/ExSO.xlsm>`_
* Follow the instructions contained inside. All it takes is two or three clicks
    * Hit the "Download Python" button and follow the instructions of the python installer
    * Hit the "Install ExSO" button.


.. figure:: figs/exso_xlsm_1.png
   :scale: 50 %
   :alt: ExSO.xlsm user interface

* You can then continue using ExSO through the ExSO.xlsm, which provides an excel-based GUI for the exso API basic functionality
* Or, use the automatically created virtual environment through your preferred IDE, to directly use the exso API through the command line or an IDE.



Manual-Mode
-----------
* Install Python >= 3.10
* Create a new virtual environment (Or, use an existing one if you know what you're doing)
* Install exso in this virtual environment:
>>> (venv) pip install exso

