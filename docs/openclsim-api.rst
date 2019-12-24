=============
OpenCLSim API
=============

A flask server is part of the OpenCLSim package. This allows using the python code from OpenCLSim from a separate front-end. 

Starting the Flask Server: Windows
-------------------------

The example code below lets you start the Flask server from the windows command line, for other operation systems please check the `Flask Documentation`_.

.. code-block:: bash

    # Set Flask app
    set FLASK_APP=openclsim/server.py

    # Set Flask environment
    set FLASK_ENV=development

    # Run Flask
    flask run


Starting the Flask Server: Mac/Linux 
-------------------------
.. code-block:: bash

    # Set Flask app
    export FLASK_APP=openclsim/server.py 

    # Set Flask environment
    export FLASK_ENV=development

    # Run Flask
    flask run

Using the Flask Server
----------------------

You can send json strings to the Flask Server using the methods presented in the `server module`_. 


.. _Flask Documentation: https://flask.pocoo.org/docs/dev/cli/
.. _server module: https://openclsim.readthedocs.io/en/latest/openclsim.html#module-openclsim.server/
