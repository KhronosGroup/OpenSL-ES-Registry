# OpenSL-ES-Registry

The OpenSL-ES-Registry repository contains the OpenSL ES API
Registry, including specifications and headers.

It is also used as a backing store for the web view of the registry at
https://www.khronos.org/registry/sles/ ; commits to the main branch of
this repository will be reflected there.

**NOTE**: as of 2021-07-21, the default branch of this repository has
been renamed from 'master' to 'main'.

In the past, the OpenSL ES registry was maintained in a public Subversion
repository. The history in that repository has not been imported to github,
but it is still available at
https://cvs.khronos.org/svn/repos/registry/trunk/public/sles/ .

Interesting files in this repository include:

* index.php - toplevel index page for the web view. This relies on PHP
  include files found elsewhere on www.khronos.org and so is not very useful
  in isolation.
* api/ - OpenSL ES header files
* specs/ - OpenSL ES specification documents.


## Adding Extension Specifications

At present there are no extensions defined for OpenSL ES, and no process
for extending it.
