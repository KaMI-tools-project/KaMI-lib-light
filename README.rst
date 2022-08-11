|Python Version| |Version| |License|

KaMI-lib (Kraken Model Inspector) - Light version
=================================================

|Logo|

A light version of KaMI-lib containing only the transcription metrics module (without Kraken).

🔌 Installation
===============

User installation
-----------------

Use pip to install package:

.. code-block:: bash

    $ pip install kamilib-light

Developer installation
----------------------

1. Create a local branch of the kami-lib light project

.. code-block:: bash

    $ git clone https://github.com/KaMI-tools-project/KaMI-lib-light.git

2. Create a virtual environment

.. code-block:: bash

    $ virtualenv -p python3.7 kami_venv

then

.. code-block:: bash

    $ source kami_venv/bin/activate

3. Install dependencies with the requirements file

.. code-block:: bash

    $ pip install -r requirements.txt

4. Run the tests

.. code-block:: bash

    $ python -m unittest tests/*.py -v


🔑 Quickstart
==============

Please, follow the documentation of `kami-lib <https://github.com/KaMI-tools-project/KaMi-lib>`__ and ignore part 2 (with Kraken engine).

Note that instead of importing Kami-lib like this:

.. code-block:: python

    from kami.Kami import Kami

Replace by this :

.. code-block:: python

    from kami_light.Kami import Kami

❓ Do you have questions, bug report, features request or feedback ?
====================================================================

Please use the issue templates:


- 🐞 Bug report: `here <https://github.com/KaMI-tools-project/KaMI-lib-light/issues/new?assignees=&labels=&template=bug_report.md&title=>`__


- 🎆 Features request: `here <https://github.com/KaMI-tools-project/KaMI-lib-light/issues/new?assignees=&labels=&template=feature_request.md&title=>`__

*if aforementioned cases does not apply, feel free to open an issue.*

✒️ How to cite
==============

.. code-block:: latex

    @misc{Kami-lib-light,
        author = "Lucas Terriel (Inria - ALMAnaCH) and Alix Chagué (Inria - ALMAnaCH)",
        title = {Kami-lib - Kraken model inspector, a light version},
        howpublished = {\url{https://github.com/KaMI-tools-project/KaMI-lib-light}},
        year = {2022}
    }

🐙  License and contact
=======================

Distributed under `MIT <./LICENSE>`__ license. The dependencies used in
the project are also distributed under compatible license.

Mail authors and contact: Alix Chagué (alix.chague@inria.fr) and Lucas
Terriel (lucas.terriel@inria.fr)

*KaMI-lib-light* is a part of `KaMI-tools-project <https://github.com/KaMI-tools-project>`__ and maintained by authors (2022) with contributions of
`ALMAnaCH <http://almanach.inria.fr/index-en.html>`__ at
`Inria <https://www.inria.fr/en>`__ Paris.

|forthebadge made-with-python|

.. |Logo| image:: https://raw.githubusercontent.com/KaMI-tools-project/KaMi-lib/master/docs/static/kamilib_light_logo.png
    :width: 100px
.. |Python Version| image:: https://img.shields.io/badge/Python-%3E%3D%203.7-%2313aab7
   :target: https://img.shields.io/badge/Python-%3E%3D%203.7-%2313aab7
.. |Version| image:: https://badge.fury.io/py/kamilib-light.svg
   :target: https://badge.fury.io/py/kamilib-light
.. |License| image:: https://img.shields.io/github/license/Naereen/StrapDown.js.svg
   :target: https://opensource.org/licenses/MIT
.. |forthebadge made-with-python| image:: http://ForTheBadge.com/images/badges/made-with-python.svg
   :target: https://www.python.org/

