.. image:: https://img.shields.io/badge/license-LGPL--3-blue.svg
   :target: http://www.gnu.org/licenses/lgpl-3.0-standalone.html
   :alt: License: LGPL-3

=================
Password Security
=================

This module allows admin to set company-level password security requirements
and enforces them on the user.

It contains features such as

* Password expiration days
* Password length requirement
* Password minimum number of lowercase letters
* Password minimum number of uppercase letters
* Password minimum number of numbers
* Password minimum number of special characters

Configuration
=============

# Navigate to company you would like to set requirements on
# Click the ``Password Policy`` page
# Set the policies to your liking.

Password complexity requirements will be enforced upon next password change for
any user in that company.


Settings & Defaults
-------------------

These are defined at the company level:

=====================  =======   ===================================================
 Name                  Default   Description                             
=====================  =======   ===================================================
 password_expiration   60        Days until passwords expire
 password_length       12        Minimum number of characters in password
 password_lower        0         Minimum number of lowercase letter in password
 password_upper        0         Minimum number of uppercase letters in password
 password_numeric      0         Minimum number of number in password
 password_special      0         Minimum number of unique special character in password
 password_history      30        Disallow reuse of this many previous passwords
 password_minimum      24        Amount of hours that must pass until another reset
=====================  =======   ===================================================


Credits
=======

Images
------

* Odoo Community Association: `Icon <https://github.com/OCA/maintainer-tools/blob/master/template/module/static/description/icon.svg>`_.

Contributors
------------

* James Foster <jfoster@laslabs.com>
* Dave Lasley <dave@laslabs.com>
