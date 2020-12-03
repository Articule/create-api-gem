Change logs of create-api-gem
====================================================

Version 1.2.6
----------------------------------

* Fix new `:show_time_estimate` in Form settings

Version 1.2.5
----------------------------------

* Fix new `:are_uploads_public` in Form settings

Version 1.0.5
----------------------------------

* Fix missing `randomize` property in `DropdownBlock`

Version 1.0.4
----------------------------------

* Remove unnecessary SSL_NONE in a theme request #6c2e41a
* Force Block require, in the hope of avoiding annoying random issues with
  "Typeform::Block" not being a known constant name, often in production, with
  no clear cause. Probably a race condition in Rails constants autoloading.

Version 1.0.3
----------------------------------

* Add error message logging when a request fails


Version 1.0.2
----------------------------------

* Add Changelog


Version 1.0.1
----------------------------------

* Fix `content-type` not being adequate for some requests (missing or extraneous)


Version 1.0.0
----------------------------------

* Bump bundler & rails versions

* Enclose all classes in `Typeform` namespace