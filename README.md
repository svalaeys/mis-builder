[![Runbot Status](https://runbot.odoo-community.org/runbot/badge/flat/248/10.0.svg)](https://runbot.odoo-community.org/runbot/repo/github-com-oca-mis-builder-248)
[![Build Status](https://travis-ci.org/OCA/mis-builder.svg?branch=10.0)](https://travis-ci.org/OCA/mis-builder)
[![codecov](https://codecov.io/gh/OCA/mis-builder/branch/10.0/graph/badge.svg)](https://codecov.io/gh/OCA/mis-builder)

# MIS Builder

Management Information System reports for Odoo: easily build super fast, 
beautiful, custom reports such as P&L, Balance Sheets and more.

This project implements a class of reports where KPI (Key Performance Indicators) 
are displayed in row, and time periods in columns. It focuses on very fast reporting
on accounting data but can also use data from any other Odoo model.

It features the following key characteristics:

- User configurable: end users can create new report templates without development,
  using simple Excel-like formulas.
- Very fast balance reporting for accounting data, even on million lines databases
  and very complex account charts.
- Use the same template for different reports.
- Compare data over different time periods.
- User-configurable styles (CSS).
- Interactive display with drill-down.
- Export to PDF and Excel.


[//]: # (addons)

Available addons
----------------
addon | version | summary
--- | --- | ---
[mis_builder](mis_builder/) | 10.0.2.0.2 | Build 'Management Information System' Reports and Dashboards


Unported addons
---------------
addon | version | summary
--- | --- | ---
[mis_builder_demo](mis_builder_demo/) | 9.0.1.0.0 (unported) | Demo data for the mis_builder module

[//]: # (end addons)

Translation Status
------------------
[![Transifex Status](https://www.transifex.com/projects/p/OCA-mis-builder-10-0/chart/image_png)](https://www.transifex.com/projects/p/OCA-mis-builder-10-0)

----

OCA, or the [Odoo Community Association](http://odoo-community.org/), is a nonprofit organization whose
mission is to support the collaborative development of Odoo features and
promote its widespread use.
