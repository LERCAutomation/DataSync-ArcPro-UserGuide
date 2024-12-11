.. index::
	single: FAQ
	see: Frequently asked questions; FAQ

**************************
Frequently Asked Questions
**************************

This is a list of Frequently Asked Questions about the Data Sync tool. Feel free to suggest new entries!

General questions
=================

**How do I get a copy of the tool?**

	The source code as well as the installer setups can be downloaded from GitHub (`ArcGIS Pro <https://github.com/LERCAutomation/DataSync-ArcPro/releases>`_). Please ensure that you use the correct configuration file, examples copy of which are also included with the releases.

**Can several people use the tool at the same time?**

	Any number of users can use the tool if they have a copy of the tool installed or loaded in their own copy of GIS. However, it is important to ensure that no two users are using the same XML profile (and hence comparing the same local layer and remote table), otherwise unexpected results may appear.

**Does the tool work with MapInfo or QGIS?**

	Currently only an ArcGIS Pro implementation of the tool exists. However, if funding was available the tool could be adapted to also support MapInfo or QGIS.

Operating the tool
==================

**I synchronised updates to the local layer but there are still differences with the remote table**

	Features that have an empty boundary, an error with the unique ID, or where the unique ID is not recognised (orphans) will not be updated in the remote table. This is down to how the bespoke stored procedure used to synchronise the local layer with the remote table has been developed.


Tool issues
===========

**How do I report a new bug or propose a change in the tool?**

	Please report any issues or propose any new changes to `Andy Foy <mailto:andy@andyfoyconsulting.co.uk>`_. 
