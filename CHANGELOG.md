Change logs of create-api-gem
====================================================

Version 1.1.0
----------------------------------

* Switch to Rails gem require scheme, easier for Articule use case: Move code to
  `app/lib` instead of `lib` to avoid multi-threading issues with Rails
  auto-loading classes in production. Would take PR to make this both Rails and
  non-Rails compatible.

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