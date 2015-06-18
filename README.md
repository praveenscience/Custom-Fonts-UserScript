# Custom Fonts User Script

This is a [User Script](http://userscripts-mirror.org/) for making the User Interface of particular websites to have your own custom fonts as their default font. This is basically a stylesheet (`<link />` tag) injector in JavaScript.

**Plus!** There is a SCSS source file (`SegoeUI.scss`) for getting started with editing. And I used [SassMeister](http://sassmeister.com/) to convert the SCSS to CSS and compress it. `;)`

## Installation

You need to have a parser (Tampermonkey, Greasemonkey) installed already in order to use this script. The installation instructions can be referred at [Installing Greasemonkey Scripts](http://userscripts-mirror.org/about/installing.html).

### Chrome

1. Download the `Custom-Fonts.user.js` from the repository.
2. Install [Tampermonkey](http://tampermonkey.net/) extension for Chrome from the [WebStore](https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo).
3. Click on the Tampermonkey icon next to the address bar and click on **Dashboard**.
4. Click on Utilities tab and in the File section, choose the downloaded `Custom-Fonts.user.js` file.
5. You need to configure the list of sites from the Dashboard by editing the settings and you are good to go!

### Firefox

1. Download the `Custom-Fonts.user.js` from the repository.
2. Install [Greasemonkey](https://addons.mozilla.org/en-US/firefox/addon/greasemonkey/) add-on for Firefox from Add-ons for Firefox.
3. Drag the `Custom-Fonts.user.js` file to a new tab in your Firefox browser window.
4. Greasemonkey identifies any file ending with `.user.js` as a User Script and shows you the installation dialogue. Wait for a few seconds and click on Install.
5. You need to configure the list of sites from the Dashboard by editing the settings and you are good to go!

### Other Browsers

**Opera**

Opera has it's own UserScript API with different functionality than Greasemonkey's or Tampermonkey's. However, it does recognise Greasemonkey scripts. Refer to [Opera's Help](http://www.opera.com/help) for installing User Scripts.

**Others (Including IE)**

You can import any GreaseMonkey script fairly easily with the [Crossrider](http://crossrider.com) cross-browser extension framework to work with Internet Explorer, along with Firefox, Safari and Chrome (It's a free service)<sup>[[Ref]](http://stackoverflow.com/a/12176626/462627)</sup>.

## Issues & Features

Please use the GitHub's issue tracker to raise issues. Being a one-line script, I don't think there'll be issues. Suggestions are welcome! Do let me know in the issues if I need to update or modify anything.

Feature requests are welcome. Please fork the project and create a pull request! You are also free to mail me at `praveen [@] praveen-kumar [dot] org`, but please keep the mail to the point and clear. You can expect a response within a day's time.

## License

Released under the The KINDLY License. See [`LICENSE.md`(./LICENSE.md) file for the license document.

## Authors

* [**Praveen Kumar Purushothaman**](https://github.com/praveenscience): Currently I am the only author of this script.