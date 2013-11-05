Getting Started
===============

Installing Hightide
-------------------

Requirements
^^^^^^^^^^^^^
You need `Java SDK v1.8`_ to run Hightide. Check your current java installation::

   $ java -version

Manual Installation
^^^^^^^^^^^^^^^^^^^
You can manually download Hightide 

Homebrew Installation [Mac OS X]
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
For mac users you can also install Hightide using `Homebrew`_::

   $ brew install hightide

Creating your first application
-------------------------------
Once you're done with the installation, check if Hightide is successfully installed using the following command::

   $ hightide

You should see something like the following output::

       __  ___       __    __  _     __
      / / / (_)___ _/ /_  / /_(_)___/ /__
     / /_/ / / __ `/ __ \/ __/ / __  / _ \
    / __  / / /_/ / / / / /_/ / /_/ /  __/
   /_/ /_/_/\__, /_/ /_/\__/_/\__,_/\___/
           /____/


   hightide> 

You can now create a new Hightide application from Hightide's shell prompt::

   hightide> new mynewapp

or straight from your command line prompt::

   $ hightide new mynewapp

.. pull-quote::

   **NOTE:** All Hightide commands can be executed either from Hightide's shell or command line [#f1]_. More information on Hightide Shell available :doc:`here </shell>`

The above command will create a new directory named ``mynewapp`` and all necessary files to run a Hightide application, using the default Hightide prototype.

:doc:`Application prototypes </prototypes>` is a very usefull concept and the default way of making a new application in Hightide.

.. [#f1] Except the ``exit`` command!

.. External Links
.. _Java SDK v1.8: https://jdk8.java.net/download.html
.. _Homebrew: http://brew.sh/
