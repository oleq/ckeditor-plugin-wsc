CKEditor WebSpellChecker Plugin
===============================

This plugin brings Web Spell Checker (WSC) into CKEditor.

WSC is "installation-less", using the web-services of [WebSpellChecker.net](http://www.webspellchecker.net/). It's an out of the box solution.

Installation
------------

1. Clone/copy this repository contents in a new "plugins/wsc" folder in your CKEditor installation.
2. Load external wsc plugin:

         CKEDITOR.plugins.addExternal('wsc_external', baseUrl + 'wsc_external/', 'plugin.js') ;
3. Add plugin to CKEDITOR.config.extraPlugins:

		CKEDITOR.config.extraPlugins = "wsc_external";

That's all. WSC will appear on the editor toolbar and will be ready to use.

License
-------

Licensed under the terms of any of the following licenses at your choice: [GPL](http://www.gnu.org/licenses/gpl.html), [LGPL](http://www.gnu.org/licenses/lgpl.html) and [MPL](http://www.mozilla.org/MPL/MPL-1.1.html).

See LICENSE.md for more information.

Developed in cooperation with [WebSpellChecker.net](http://www.webspellchecker.net/).
