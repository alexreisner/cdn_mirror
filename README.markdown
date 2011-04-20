CDN Mirror
==========

This is a mirror of some libraries (jQuery, jQueryUI, YUI) as they are stored on various CDNs (Google, Microsoft), intended for use when developing web sites without Internet access. For example, the [local_assets Ruby gem](http://github.com/alexreisner/local_assets) Ruby gem (for Rack apps) scans all output HTML for CDN URLs and replaces them with configurable localhost URLs which can point to your local copy of this mirror. (The intention is that you place this repo somewhere within the document root of your development machine's web server.)

A spider script is included for downloading the newest versions from the actual CDNs.


Notes
-----

* Google's CDN appears to be missing the `ui-anim_basic_16x16.gif` image for all themes other than `base` in jQueryUI 1.8.0 and 1.8.1. No attempt has been made to correct this in the mirror.
* For YUI download links see: http://yuilibrary.com/downloads/
