# Changelog

## 1.0.3

Bug fixes:
  * Fix support for webpack 4.x.

## 1.0.2

Bug fixes:
  * Add support for webpack 4.x. We now support both webpack 3.x and 4.x.

## 1.0.1

Bug fixes:
  * Translations json parser is now more lenient by allowing non strings messages. Integer, float, and boolean are converted to string, null, array and object are replaced with an empty string.

## 1.0.0

New features:
  * Generate routes from symfony's routing, with variables support
  * Generate translations from symfony's translations, with variables and pluralization support
  * Support for elm 0.18 and 0.19

[//]: # (## x.y.z)
[//]: # (Breaking changes:)
[//]: # (New features:)
[//]: # (Bug fixes:)