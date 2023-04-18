<details>
<summary><b>LTBEEF inspect</b> (Using inspect to disable extensions)</summary>

![image](https://user-images.githubusercontent.com/58097612/207386423-e6aa2095-d92d-44a8-a3d6-e42066bdf34e.png)

The screenshot below was preformed on 108.0.5359.75 (Official Build) (64-bit) on the stable channel.

This has been tested and does work but has varying levels of success, you will need access to inspect element, more specifically, console.

- Open this URL on your chromebook: `chrome-extension://gndmhdcefbhlchkhipcnnbkcmicncehk/manifest.json` Shortened link: https://tinyurl.com/i-ltbeef
- Open inspect and navigate to the console tab.
- Run the basic LTBEEF code such as
```js
chrome.management.setEnabled('extensionid', false)
```
Replacing `extensionid` with the ID of the extension you want to disable, e.g. the stuff after the = in the URL bar when you click the extension's "details" button in chrome://extensions
