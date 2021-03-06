
Purpose
--------

``gitsane`` automates IAM user access key rotation from the cli by allowing ad hoc or
scheduled renewal of your access key credentials via the Amazon API's.

**gitsane**:

    * is a safe and reliable way to rotate (renew) access keys to Amazon Web Services as frequently as you wish, with minimal effort and risk.
    * requires only the profile name of your IAM user in your local `awscli configuration <https://docs.aws.amazon.com/cli/latest/reference/>`__

**Features**:

    * access key rotation via the Amazon APIs
    * key rotation includes:

        * creation of new access keys
        * automated installation in the local `awscli configuration <http://docs.aws.amazon.com/cli/latest/userguide/cli-config-files.html>`__
        * deprecated key deletion

    * automated, unattended key rotation
    * rotate keys as frequently as you wish (daily, for example)

.. figure:: ../assets/intro.png
   :alt:


--------------------

Getting Started
----------------

Before starting, please take a moment to read the following:

-  `Frequently Asked Questions (FAQ) <./FAQ.html>`__
-  `Use Cases <./usecases.html>`__


**Other Resources**:

-  Source Code: `gitsane bitbucket repository <https://bitbucket.org/blakeca00/gitsane>`__
-  Amazon `Secure Token Service (STS) <https://docs.aws.amazon.com/STS/latest/APIReference/Welcome.html>`__ Documentation
-  Amazon Web Services' `Command Line Interface (awscli) <https://docs.aws.amazon.com/cli/latest/reference/>`__ Documentation
-  **gitsane** `Open Source License Agreement <./license.html>`__

**Current Release**:

-  Ensure you are running the most current release.  See the most :ref:`latest`.

--------------

.. _Docs:

Documentation
-------------

**Online**:

- Complete html documentation available at `http://gitsane.readthedocs.io <http://gitsane.readthedocs.io>`__.

**Download**:  Available via download in the formats below

- `pdf format <https://readthedocs.org/projects/gitsane/downloads/pdf/latest/>`__
- `Amazon Kindle <https://readthedocs.org/projects/gitsane/downloads/epub/latest/>`__ (epub) format

--------------------

Parameters & Options
--------------------

Display help menu to see available options and functionality.

.. code:: bash


        $ gitsane -h

.. figure:: ../assets/help-menu.png
   :alt:

--------------

Author & Copyright
------------------

All works contained herein copyrighted via below author unless work is
explicitly noted by an alternate author.

-  Copyright Blake Huber, All Rights Reserved.

**License**

-  Software is licensed under the `GNU General Public License Agreement v3 <./license.html>`__.

--------------

Disclaimer
----------

*Code is provided "as is". No liability is assumed by either the code's
originating author nor this repo's owner for their use at AWS or any
other facility. Furthermore, running function code at AWS may incur
monetary charges; in some cases, charges may be substantial. Charges are
the sole responsibility of the account holder executing code obtained
from this library.*

Additional terms may be found in the complete `license agreement <./license.html>`__.

--------------

( `Table Of Contents <./index.html>`__ )

-----------------

|
