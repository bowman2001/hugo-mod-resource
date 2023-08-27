---
title: Hugo module for retrieving resources in the most flexible way
---

The partial _get-resource_ is designed for calls from the content via render hooks or shortcodes and can get all kinds of resources available to Hugo. It tries all of the following three options to give users the best flexibility.

Page resources
: Local files in a page bundle. They may be registered in the frontmatter and additional parameters may accompany them.

Site resources
: Local files in the `assets` folders.

Remote resources
: Files with an absolute URL from anywhere on the net.

**Warning:** The function _get-resource_ does **not fit** as a replacement for direct calls of Hugo’s resource functions in templates when the origin and job of a resource is predetermined and error handling needs to be specific.
