![header](.github/header.png)

ShadowBird is a spinoff of [ShadowFox](https://overdodactyl.github.io/ShadowFox/) ([GitHub Link](https://github.com/overdodactyl/ShadowFox)), a universal dark theme for Firefox 57+, designed for Thunderbird.  

This project is very early in development and users are encouraged to open issues or pull requests with any problems, enhancements or feature requests.  


## Installation

1. Download this repository and rename the folder to `chrome`.

2. Place the `chrome` folder inside your Thunderbird profile directory. To find your profile directory, you can do the following from within Thunderbird:

	- Help > Troubleshooting Information > Application Basics section > Profile Folder > Show in Finder

3. (Optional) To change the background and text area of the message composition pages, you can dd the following lines to your `user.js` file within the profile directory (this will not alter the appearance of sent messages):

```js
user_pref("browser.display.foreground_color", "#b1b1b3");
user_pref("browser.display.background_color", "#38383d");
```

4. Restart Firefox