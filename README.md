# <img src="/src/img/icon48.png" align="absmiddle"> The Great Suspender

### Currently down on the webstore!!! Please read if you have lost tabs ###

The webstore version of this extension was compromised yesterday. It has since been returned to my ownership but Google have removed it from the webstore until they can review the situation.

While the extension was out of my control, an update was forced upon all users. I have inspected the source code of this unsolicited update, and it was not modified in any way except for a change in version number (it has a version 6.22 but in all other respects it is the same as v6.21). This version of the extension is safe to use and can be re-enabled manually from chrome://extensions.

Unfortunately, due to the way the extension works, when it is disabled, all suspended tabs are removed from the chrome browser. The only way to recover these tabs is to re-enable the extension. As mentioned above, this is safe to do.

If you were asked recently to accept new permissions, this is purely because you were upgrading from an older version of the extension to a newer one (v6.22). The extension has required these permissions to operate for quite some time now and is not related at all to the extension being compromised.

For more information on the compromise, please refer to this gitHub issue: (https://github.com/deanoemcke/thegreatsuspender/issues/512)

For more information on the permissions required for the extension, please refer to this gitHub issue: (https://github.com/deanoemcke/thegreatsuspender/issues/213)

### Welcome

"The Great Suspender" is a free and open-source Google Chrome extension for people who find that chrome is consuming too much system resource or suffer from frequent chrome crashing. Once installed and enabled, this extension will automatically *suspend* tabs that have not been used for a while, freeing up memory and cpu that the tab was consuming.

If you have suggestions or problems using the extension, please [submit a bug or a feature request](https://github.com/deanoemcke/thegreatsuspender/issues/).

### Installation

1. Download the **[latest available version](https://github.com/deanoemcke/thegreatsuspender/releases/tag/v6.21)** and unarchive to your preferred location (whichever suits you).
2. Using **Google Chrome** browser, navigate to chrome://extensions/ and enable "Developer mode" in the upper right corner.
3. Click on the <kbd>Load unpacked extension...</kbd> button.
4. Browse to the src directory of the downloaded, unarchived release and confirm.

If you have completed the above steps, the "welcome" page will open indicating successful installation of the extension.

### Chrome webstore

Please note that the version on the Chrome webstore may be some versions behind. Also, the webstore version has automatic updates *disabled* so you will need to uninstall/reinstall if you want to update after a new webstore version is pushed. For information on why this is the situation please read this issue thread: https://github.com/deanoemcke/thegreatsuspender/issues/322

### License

This work is licensed under a GNU GENERAL PUBLIC LICENSE (v2)

### Shoutouts

This package uses the [html2canvas](https://github.com/niklasvh/html2canvas) library written by Niklas von Hertzen.  
It also uses the indexedDb wrapper [db.js](https://github.com/aaronpowell/db.js) written by Aaron Powell.  
Thank you also to [BrowserStack](https://www.browserstack.com) for providing free chrome testing tools.  
