---
layout: "layouts/doc-post.njk"
title: "Manifest - Description"
#date: TODO
#updated: TODO
#description: TODO
---

!!!.aside.aside--caution

**Important:** Chrome will be removing support for Chrome Apps on all platforms. Chrome browser and
the Chrome Web Store will continue to support extensions. [**Read the announcement**][1] and learn
more about [**migrating your app**][2].

!!!

A plain text string (no HTML or other formatting; no more than 132 characters) that describes the
extension. The description should be suitable for both the browser's extension management UI and the
[Chrome Web Store][3]. You can specify locale-specific strings for this field; see
[Internationalization][4] for details.

[1]: https://blog.chromium.org/2020/01/moving-forward-from-chrome-apps.html
[2]: https://developers.chrome.com/apps/migration
[3]: https://chrome.google.com/webstore
[4]: https://developer.chrome.com/extensions/i18n