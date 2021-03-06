.. image:: https://img.shields.io/badge/licence-AGPL--3-blue.svg
    :alt: License: AGPL-3

Module name
===========

mrp_bom_version, MRP - BoM version

Short Description
-----------------

This module is intended to add a version control to BoM (Bill of Materials) and to allow to control his life cycle.

[es_ES] Este módulo tiene como objetivo el añadir el control de versiones a la LdM (Lista de Materiales) y permitir el control de su ciclo de vida.

Long Description
----------------

This module provides a state in the BoM whether to allow their use in
manufacturing, to do the following states are defined:

* **Draft**:
  The form will be available for data entry, and may move to "active" state.
* **Active**:
  You can modify all of the form fields except for the fields: routing, BoM
  lines, and the new field Active, for false default when you create a new BoM.
  The "active" state may be passed back to state "draft", if we mark the new
  field "Allow re-edit the BoM list", this new field is defined in 
  *Configuration > Configuration > Manufacturing*.
  The active state may move to state "Historical".
* **Historical**: 
  This is the last state of the LdM, you can not change any field on the form.

When the MRP BoM list is put to active, a record of who has activated, and when
will include in chatter/log. It also adds a constraint for the sequence field
to be unique.

* **New version** :
  By clicking the button version, current BOM is moved to historical state,
  and a new BOM is creating based on this  but with version number +1 and
  changing state to draft

Installation
============

To install this module, you need to:
** to do **

Configuration
=============

To configure this module, you need to:
** to do **

Usage
=====

** to do **

Installation
============

** to do **

Configuration
=============

To configure this module, you need to:
** to do **

Usage
=====

To use this module, you need to:
** to do **

Credits
=======

* odooMRP Project, www.odoomrp.com

Contributors
------------

** to do **
