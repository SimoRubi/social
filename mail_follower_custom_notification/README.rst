==========================================
Custom notification settings for followers
==========================================

.. !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
   !! This file is generated by oca-gen-addon-readme !!
   !! changes will be overwritten.                   !!
   !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!

.. |badge1| image:: https://img.shields.io/badge/maturity-Beta-yellow.png
    :target: https://odoo-community.org/page/development-status
    :alt: Beta
.. |badge2| image:: https://img.shields.io/badge/licence-AGPL--3-blue.png
    :target: http://www.gnu.org/licenses/agpl-3.0-standalone.html
    :alt: License: AGPL-3
.. |badge3| image:: https://img.shields.io/badge/github-SimoRubi%2Fsocial-lightgray.png?logo=github
    :target: https://github.com/SimoRubi/social/tree/10.0/mail_follower_custom_notification
    :alt: SimoRubi/social

|badge1| |badge2| |badge3| 

In standard Odoo, receiving mail notifications is an all or nothing affair.
This module allows users to decide per followed record if they want to
receive emails or not. Further, they can choose to receive notifications about
their own messages.

You can also set defaults for this settings on the subtype in question.

**Table of contents**

.. contents::
   :local:

Configuration
=============

When followers open their subscriptions, they will be offered the choice to
override mail settings and to force being notified about their own messages.

Note subscriptions are only editable for users of the `Technical settings`
group.

You can add defaults per message subtype for this settings in Settings /
Technical / Email / Subtypes. Here, you also have the opportunity to apply
those defaults to existing subscriptions. Note that this overrides all
customizations your users already have done.

Bug Tracker
===========

Bugs are tracked on `GitHub Issues <https://github.com/SimoRubi/social/issues>`_.
In case of trouble, please check there if your issue has already been reported.
If you spotted it first, help us smashing it by providing a detailed and welcomed
`feedback <https://github.com/SimoRubi/social/issues/new?body=module:%20mail_follower_custom_notification%0Aversion:%2010.0%0A%0A**Steps%20to%20reproduce**%0A-%20...%0A%0A**Current%20behavior**%0A%0A**Expected%20behavior**>`_.

Do not contact contributors directly about support or help with technical issues.

Credits
=======

Authors
~~~~~~~

* Therp BV

Contributors
~~~~~~~~~~~~

* Holger Brunn <hbrunn@therp.nl>

Other credits
~~~~~~~~~~~~~

* Odoo Community Association: `Icon <https://github.com/OCA/maintainer-tools/blob/master/template/module/static/description/icon.svg>`_.

Maintainers
~~~~~~~~~~~

This module is part of the `SimoRubi/social <https://github.com/SimoRubi/social/tree/10.0/mail_follower_custom_notification>`_ project on GitHub.

You are welcome to contribute.
