################################
pl-workshop-2018
################################


Abstract
********

An app to showcase making a plugin

Run
***

Using ``docker run``
====================

Assign an "input" directory to ``/incoming`` and an output directory to ``/outgoing``

.. code-block:: bash

    docker run -v --rm $(pwd)/in:/incoming -v $(pwd)/out:/outgoing   \
            fnndsc/pl-workshop-2018 workshop_2018.py            \
            /incoming /outgoing

This will ...

Make sure that the host ``$(pwd)/out`` directory is world writable!







