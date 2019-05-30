# Cookie Clicker Mod Manager (CCMM)

*Current version : 1.0*

**CCMM** is a browser extension to manage the javascript add-ons a player may want to use with the game [Cookie Clicker][CookieClickerLink]. Currently only for Firefox, but plans are in place for compatibility with other browsers.

## How to use it

Add the extension to your browser. 

* [Firefox][FirefoxLink]

Once the extension is added to your browser, a small icon of a cookie will appear in the URL bar when you are playing Cookie Clicker (Firefox). Clicking this icon will bring up the Mod Manager Main Menu. 

#### Main Menu

![Main menu][MainMenu]

In the Main Menu you can:
1. Toggle CCMM on and off
2. Open the Options Menu
3. Toggle individual mods on and off
4. Open the Add/Edit Mod Menu
5. Load mods that aren't already loaded

### Options Menu

![Options menu][OptionsMenu]

Here you can 
1. View CCMM's current configuration (in JSON format)
2. Any changes you make in the text box will not take effect until you click "Save changes"
3. Back up your configuration to a file for safekeeping
4. As a just-in-case, you can restore CCMM to its default settings

### Add/Edit Mod Menu

![Edit menu][EditMenu]

1. Paste the URL of the mod you want to add into the "URL" textbox (no such thing as intuitive design)
2. When the URL is changed, CCMM tries to guess a name for the mod in the "Name" textbox. This can be overwritten
3. Any changes you make will not take effect until you click "Save changes"
4. Click "Cancel" to undo all changes and return to the Main Menu
5. "Delete" will, naturally, remove the currently selected mod

## Bugs and suggestions

Any bug or suggestion should be **opened as an issue** [in the repository][IssueLink] for easier tracking. This allows me to close issues once they're fixed.

## Version History

**05/30/2019 - 1.0**
* Changed a couple of icons
* Code altered for compatibility with Google chrome

**05/28/2019 - 0.83**
* Removed a script-injection vulnerability
* Changed a button's icon and text to be more intuitive

**05/26/2019 - 0.80**
* Initial release

## Special thanks

Anyone who gives a suggestion or bugfix, especially code that gets implemented into CCMM, will be listed here along with their contribution.

* klattmose
	* Writing this thing

[CookieClickerLink]: https://orteil.dashnet.org/cookieclicker
[FirefoxLink]: https://addons.mozilla.org/en-US/firefox/addon/cookie-clicker-mod-manager/
[MainMenu]: https://i.imgur.com/CwV00hk.png
[OptionsMenu]: https://i.imgur.com/8Z4bS6Q.png
[EditMenu]: https://i.imgur.com/Qr8vyrr.png
[IssueLink]: https://github.com/klattmose/CookieClickerModManager/issues
