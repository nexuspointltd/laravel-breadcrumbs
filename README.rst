################################################################################
 Laravel Breadcrumbs 3
################################################################################

.. |stable| image:: https://poser.pugx.org/davejamesmiller/laravel-breadcrumbs/v/stable.png
   :alt: Latest Stable Version
   :target: https://packagist.org/packages/davejamesmiller/laravel-breadcrumbs

.. |downloads| image:: https://img.shields.io/packagist/dt/davejamesmiller/laravel-breadcrumbs.svg?style=flat
   :alt: Total Downloads
   :target: https://packagist.org/packages/davejamesmiller/laravel-breadcrumbs

.. |references| image:: https://www.versioneye.com/php/davejamesmiller:laravel-breadcrumbs/reference_badge.svg?style=flat
   :alt: Reference Status
   :target: https://www.versioneye.com/php/davejamesmiller:laravel-breadcrumbs/references

.. |build| image:: https://img.shields.io/travis/davejamesmiller/laravel-breadcrumbs/master.svg?style=flat
   :alt: Build Status
   :target: https://travis-ci.org/davejamesmiller/laravel-breadcrumbs

.. |coverage| image:: https://img.shields.io/coveralls/davejamesmiller/laravel-breadcrumbs.png
   :alt: Coverage Status
   :target: https://coveralls.io/r/davejamesmiller/laravel-breadcrumbs

.. |dependencies| image:: https://www.versioneye.com/php/davejamesmiller:laravel-breadcrumbs/badge.svg
   :alt: Dependency Status
   :target: https://www.versioneye.com/php/davejamesmiller:laravel-breadcrumbs

|stable| |downloads| |references|
|build| |coverage| |dependencies|

A simple Laravel-style way to create breadcrumbs in `Laravel 5 <http://laravel.com/>`_.

================================================================================
 Documentation
================================================================================

`View documentation >> <http://laravel-breadcrumbs.davejamesmiller.com/>`_

**Note:** If you are still using Laravel 4.0 to 4.2 please use the `2.x version <https://github.com/davejamesmiller/laravel-breadcrumbs/tree/2.x>`_ of Laravel Breadcrumbs instead.

================================================================================
 Support Requests / Bug Reports
================================================================================

All support requests / bug reports should be submitted using `GitHub issues <https://github.com/davejamesmiller/laravel-breadcrumbs/issues>`_, and **must** include the following:

- The complete error message, including file & line numbers
- Steps to reproduce the problem
- Laravel Breadcrumbs version
- Laravel version
- PHP version

You should also include copies of the following:

- ``app/Http/breadcrumbs.php``
- ``config/breadcrumbs.php`` (if used)
- The view or layout that outputs the breadcrumbs
- The custom breadcrumbs template (if applicable)
- The full ``providers`` and ``aliases`` sections of ``config/app.php`` (Note: **not the Encryption Key section** which should be kept private) -- in case there's a conflict with another package
- Any other relevant files

**Note:** Don't be afraid to go into the Laravel Breadcrumbs code and use ``var_dump()`` (or ``dd()`` or ``print_r()``) to see what's happening and try to fix your own problems! A pull request or detailed bug report is much more likely to get attention than a vague error report. Also make sure you read the `documentation <http://laravel-breadcrumbs.davejamesmiller.com/en/latest/>`_ carefully.

================================================================================
 Feature Requests / Pull Requests
================================================================================

Any feature requests / pull requests should include details of what you are trying to achieve (use case) to explain why your request should be implemented.

.. This text is also in docs/contributing.rst
If you want to submit a **bug fix**, please make your changes in a new branch, then open a `pull request <https://github.com/davejamesmiller/laravel-breadcrumbs/pulls>`_. (The `Contributing page of the docs <http://laravel-breadcrumbs.davejamesmiller.com/en/latest/contributing.html>`_ may help you to get started if you've not done this before.)

.. This text is also in docs/contributing.rst
If you want to submit a **new feature**, it's usually best to open an `issue <https://github.com/davejamesmiller/laravel-breadcrumbs/issues>`_ to discuss the idea first -- to make sure it will be accepted before spending too much time on it. (Of course you can go ahead and develop it first if you prefer!) Please be sure to update the documentation as well.

If you have any suggestions for improving the **documentation** -- especially if anything is unclear to you and could be explained better -- please let me know. (Or just edit it yourself and make a pull request.)

--------------------------------------------------------------------------------

Copyright © 2013-2015 Dave James Miller. Released under the `MIT License <docs/license.rst>`_.