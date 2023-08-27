---
title: Hugo module for retrieving resources
---

The module can get all kinds of resources available with Hugo:

Page resources
: Local files in a page bundle. They may be registered in the frontmatter and additional parameters may accompany them.

Site resources
: Local files in the `assets` folders.

Remote resources
: Files with an absolute URL from anywhere on the net.

The partial _get-resource_ tries all of the three options and is meant for situations where users need flexibility.

It does **not** suit as a replacement for direct calls of Hugo’s resource functions in templates when the origin of a needed resource is known to the developer.
