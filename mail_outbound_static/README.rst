====================
Mail Outbound Static
====================

.. !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
   !! This file is generated by oca-gen-addon-readme !!
   !! changes will be overwritten.                   !!
   !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!

.. |badge1| image:: https://img.shields.io/badge/maturity-Beta-yellow.png
    :target: https://odoo-community.org/page/development-status
    :alt: Beta
.. |badge2| image:: https://img.shields.io/badge/licence-LGPL--3-blue.png
    :target: http://www.gnu.org/licenses/lgpl-3.0-standalone.html
    :alt: License: LGPL-3
.. |badge3| image:: https://img.shields.io/badge/github-SimoRubi%2Fsocial-lightgray.png?logo=github
    :target: https://github.com/SimoRubi/social/tree/10.0/mail_outbound_static
    :alt: SimoRubi/social

|badge1| |badge2| |badge3| 

This module brings Odoo outbound emails in to strict compliance with RFC-2822
by allowing for a statically configured From header, with the sender's e-mail
being appended into the proper Sender header instead.

**Table of contents**

.. contents::
   :local:

Usage
=====

* Navigate to an Outbound Email Server
* Set the `Email From` option to an email address
* If not email_from has been defined in any smtp server, the address can be obtained
  via the odoo.conf file, using the parameter email_from,
  Ex:

# specify the SMTP email address for sending email

email_from = example@server.com

Known issues / Roadmap
======================

* Allow for domain-based whitelist that will not be manipulated

Bug Tracker
===========

Bugs are tracked on `GitHub Issues <https://github.com/SimoRubi/social/issues>`_.
In case of trouble, please check there if your issue has already been reported.
If you spotted it first, help us smashing it by providing a detailed and welcomed
`feedback <https://github.com/SimoRubi/social/issues/new?body=module:%20mail_outbound_static%0Aversion:%2010.0%0A%0A**Steps%20to%20reproduce**%0A-%20...%0A%0A**Current%20behavior**%0A%0A**Expected%20behavior**>`_.

Do not contact contributors directly about support or help with technical issues.

Credits
=======

Authors
~~~~~~~

* LasLabs
* Trescloud

Maintainers
~~~~~~~~~~~

This module is part of the `SimoRubi/social <https://github.com/SimoRubi/social/tree/10.0/mail_outbound_static>`_ project on GitHub.

You are welcome to contribute.
