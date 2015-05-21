---
layout: page
title: Uninstall
---

For each repository with ghpages-ghcomments:

 1. Remove the hooks from:
  * **.git/hooks/pre-commit**
  * **.git/hooks/pre-push**
 1. Remove the ghpages-ghcomments files:
  * **_data/gpgc.yml**
  * **\_includes/gpgc_comments.html**
  * **public/css/gpgc_styles.css**
  * **public/html/gpgc_redirect.html**
  * **public/js/gpgc_core.js**
 1. Remove the lines you added from:
  * **_includes/head.html**
  * **_layouts/post.html**

---

## Other advanced topics:

* [Verbose Usage](../verbose-usage)
* [Custom GitHub App](../custom-github-app)
* [Troubleshooting](../troubleshooting)
* [Manual](../manual)
* Uninstall