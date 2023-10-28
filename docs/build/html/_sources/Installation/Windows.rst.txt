Windows Installation
+++++++++++++++++++++++++

Install git
============================

To install git on Windows :

* Navigate to https://git-scm.com/download/win

.. code-block:: bash 

    sudo apt update
    sudo apt install git


You can verify the installation by running:

.. code-block:: bash

    git --version

Set up your username and email
==================================

.. code-block::  bash

    git config --global user.name "username"
    git config --global user.email mail@mail.com

Verify the new username and email have changed:

.. tip:: 

    It's also usefull to configure the default text editor that git will
    be using to be vsode. You can do this by running:

    .. code-block:: bash
        
        git config --global core.editor "code --wait"