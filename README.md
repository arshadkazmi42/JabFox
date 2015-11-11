FireBib Firefox Addon
=============

FireBib collects online research material and sends the bibliographic information directly to your favorite reference manager - all in one click.

Supported sites: https://www.zotero.org/support/translators

_Currently, the development of this addon is in a very early stage. Use with care (backup!) and don't expect wonders. Please post any issues/suggestions here on github._

Installation and Settings
-------------------------

1. Make sure Zotero is [installed in Firefox](https://www.zotero.org/download/).
2. Install the addon by clicking [here](https://raw.githubusercontent.com/tobiasdiez/Jabref-FirefoxAddon/master/firebib.xpi). Alternatively, download `firebib.xpi` and then drag-n-drop it into Firefox. The JabRef icon should now appear in the Firefox toolbar. 
3. Change the path to the Jabref executable in the addon settings (Add-ons > FireBib > Options).

You might want to configure JabRef so that new entries are imported in an already opened instance of JabRef. For this, activate "Remote operation" under the Advanced tab in the JabRef Preferences.

How to import a new article into Jabref?
----------------------------------------

Navigate to the website which contains the to-imported items. For example, [the arXiv](http://arxiv.org/list/gr-qc/pastweek?skip=0&show=5). Now just click the JabRef symbol in the Firefox toolbar and wait.... until JabRef opens and wants to import your references.

Contributing
----------

In order to directly use the source code (and help with the development of this project) the following software has to be installed:

 - Firefox Addon SDK: https://developer.mozilla.org/en-US/Add-ons/SDK

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request.