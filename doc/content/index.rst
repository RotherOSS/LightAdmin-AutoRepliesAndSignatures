.. toctree::
    :maxdepth: 2
    :caption: Contents

Sacrifice to Sphinx
===================

Description
===========
Enable the LightAdmin capability for the Signature and Auto Response features.

System requirements
===================

Framework
---------
OTOBO 11.0.x

Packages
--------
\-

Third-party software
--------------------
\-

Basic Configuration
===================
If not yet present, create a group for the light admin, e.g. *light*, and add it to the *GroupRo* key of the following settings. For the basic access:

- Frontend::Module###Admin
- Frontend::Module###AdminSignature
- Frontend::Module###AdminAutoResponse
- Frontend::Module###AdminQueueAutoResponse

And to provide the navigation entries:

- Frontend::NavigationModule###Admin
- Frontend::Navigation###Admin###001-Framework
- Frontend::NavigationModule###AdminSignature
- Frontend::NavigationModule###AdminAutoResponse
- Frontend::NavigationModule###AdminQueueAutoResponse

About
=======

Contact
-------
| Rother OSS GmbH
| Email: hello@otobo.io
| Web: https://otobo.io

Version
-------
Author: |doc-vendor| / Version: |doc-version| / Date of release: |doc-datestamp|
