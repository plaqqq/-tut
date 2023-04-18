<details>
<summary><b>LTBEEF inspect</b> (Using inspect to disable extensions)</summary>

![image](https://user-images.githubusercontent.com/58097612/207386423-e6aa2095-d92d-44a8-a3d6-e42066bdf34e.png)

The screenshot below was preformed on 108.0.5359.75 (Official Build) (64-bit) on the stable channel.

This has been tested and does work but has varying levels of success, you will need access to inspect element, more specifically, console.

- Open this URL on your chromebook: `chrome-extension://gndmhdcefbhlchkhipcnnbkcmicncehk/manifest.json` ( copy the link and paste it into the search bar on a new tab.

- Open inspect and navigate to the console tab. (press control+shift+i and go to the console tab.)
- Run the basic LTBEEF code such as copy the code below and paste it into the console on the URL u copied and pasted into the new tab.
```js
chrome.management.setEnabled('abmmkhcfmfmkgeeopaedjcnckmchannj', false)
```
Replacing `extensionid` with the ID of the extension you want to disable, e.g. the stuff after the = in the URL bar when you click the extension's "details" button in chrome://extensions make sure to have the developer mode on to see the ext id.
