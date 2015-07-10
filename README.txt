University IT Visitor Modules for Drupal 7.x


-- SUMMARY --

Author: Marco Wise

These modules are meant to find out information about visitors to the Stanford
University IT website and reach appropriately (adding session variables, 
assigning Drupal roles, etc.)

For example, if someone is looking for instructions on configuring their email
account, the modules can discover in advance which email service they are on
(Zimbra, Google, Office 365, etc.) so that the appropriate instructions are
displayed.


-- LICENSE --

See the LICENSE file.


-- REQUIREMENTS --

The Visitor Roles module requires the WebAuth module for Drupal.
It can be found on Github: https://github.com/Stanford/WMD


-- INSTALLATION --

Download and extract the module's package in your sites/all/modules directory.
As an admin, go to Administer > Site building > Modules to enable the module.
More detailed information on installing modules here: http://drupal.org/node/70151

At installation, the Visitor Roles module will create roles for each of the email
services in use at Stanford.


-- CONFIGURATION --

No configuration is necessary.
