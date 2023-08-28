## Function resource/get

The partial is designed for calls from the content via render hooks or shortcodes and can get all kinds of resources to give users the greatest flexibility.

There are three kinds of resources for Hugo:

Page resources
: Local files in a page bundle. They may be registered in the frontmatter and additional parameters may accompany them.

Site resources
: Local files in the `assets` folders.

Remote resources
: Files with an absolute URL from anywhere on the net.

**Warning:** The function does **not fit** as a replacement for direct calls of Hugo’s resource functions in templates when the origin of a resource is predetermined and its handling needs to be specific.
