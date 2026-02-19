==========================================
Followup Report - Date Ascending
==========================================

.. |badge1| image:: https://img.shields.io/badge/licence-LGPL--3-blue.png
    :target: http://www.gnu.org/licenses/lgpl-3.0-standalone.html
    :alt: License: LGPL-3

|badge1|

This module changes the sorting of follow-up report lines so that invoices are
listed by **earliest date first** (ascending order) instead of the default
newest-first sorting.  This matches the way invoices are listed in the UI report.

**Table of contents**

.. contents::
   :local:

Installation
============

1. Copy the ``account_followup_sort_asc`` folder to your Odoo addons directory.
2. Update the apps list in Odoo (Settings > Apps > Update Apps List).
3. Search for "Followup Report - Date Ascending" and install it.

**Dependency:** This module requires the ``account_followup`` module (Odoo Enterprise).

Usage
=====

No configuration is required. Once installed, the follow-up reports sent to
customers will automatically list invoice lines sorted by earliest date first.

Features
========

- **Date ascending sort**: Follow-up report lines are sorted by maturity date (or invoice date) in ascending order
- **Multi-currency support**: Totals and overdue amounts are correctly calculated per currency
- **Overdue highlighting**: Overdue amounts are highlighted in red for easy identification
- **No configuration needed**: Works automatically once installed

Support
=======

For support, please contact SJR Nebula:

- Website: https://sjr.ie
- Email: info@sjr.ie

Credits
=======

Authors
-------

* SJR Nebula

Contributors
------------

* John Ashurst
