Field Validation
================

Allows for validation rules for field instances.

The following validators are currently included:

* Regular expression
* Numeric values (optionally specify min and / or max value)
* Length (optionally specify min and / or max length)
* Number of words (optionally specify min and / or max words )
* Plain text (disallow tags)
* Must be empty (Anti-Spam: Hide with CSS)
* Words blacklist
* Number of selections (optionally specify min and / or max selections )
* Unique
* Match against a field
* Match against a property
* Specific value(s)
* Require at least one of several fields
* Equal values on multiple fields
* Unique values on multiple fields
* PHP Code (powerful but dangerous)
* URL (support internal path and external url validation)
* Email
* Pattern (Regular expression lite)
* Date range2

Following validators are included in sub module field validation extras:

* Color(HTML5)
* Date(ISO)
* EAN number
* Field collection unique
* Integer values
* IP Address
* Numeric (HTML5, with the option to specify min/max/step)
* Regular expression (Perl-Compatible)
* Phone
* Required field
* Require some of several fields
* Postal code (depend on Postal Code Validation, support Address Field)

There is also another sub-module Property Validation which could solve validation issues for property (non-field), such as title, Ubercat SKU, list_price.

Documentation
-------------

* [Docs on drupal.org](http://drupal.org/node/1299698)
* [Date range](http://drupal.org/node/1438436)
* [PHP code validator](https://www.drupal.org/node/1537028)

Write complex validation rules for your fields, http://www.lullabot.com/articles/module-monday-field-validation

Issues
------

To submit bug reports and feature suggestions, or to track changes:
  https://github.com/backdrop-contrib/field_validation/issues.

Current Maintainers
-------------------

* No current maintainers.

Credits
-------

* Ported to Backdrop by [Herb v/d Dool](https://github.com/herbdool/)
* Originally developed for Drupal by [Howard Ge](https://www.drupal.org/u/g089h515r806)

Inspired by [Webform Validation](http://drupal.org/project/webform_validation).

License
-------

This project is GPL v2 software. See the LICENSE.txt file in this directory for
complete text.