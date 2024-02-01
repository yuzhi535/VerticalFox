# Vertical Firefox

a custom firefox theme. containing features below:

* vertical tabs
* compact mode
* random background image for new tab
* remove title bar

## prequisite

1. open `about:config` in firefox
2. set `toolkit.legacyUserProfileCustomizations.stylesheets` to `true`
3. install [`sidebery` addon](https://addons.mozilla.org/en-US/firefox/addon/sidebery/)


## how to install

### For windows

1. find your firefox profile folder. (usually in `C:\Users\{username}\AppData\Roaming\Mozilla\Firefox\Profiles\{profile}`)
2. create a folder named `chrome` in it.
3. copy `userChrome4win.css`, `userContent.css` to `chrome` folder.
4. rename `userChrome4win.css` to `userChrome.css`. 
5. enjoy! 

### for mac

1. find your firefox profile folder. (usually in `~/Library/Application Support/Firefox/Profiles/{profile}`)
2. create a folder named `chrome` in it.
3. copy `userChrome4mac.css`, `userContent.css` to `chrome` folder.
4. rename `userChrome4mac.css` to `userChrome.css`. 
5. enjoy! 

## how to use

1. keep the `sidebery` addon enabled.
2. keep `sidebery sidebar` opened. this is the vertical tabs.
3. explore the `sidebery` addon. it's powerful! 

## demo

* when firefox is not maximized, the title bar is not hidden; however, if firefox is maxmized, the title bar will be hidden(on mac, it's maximazed; on windows, it's fullscreen).
* titlebar is hidden always.
* homepage background image is from [unsplash](https://unsplash.com/).

![demo](./imgs/demo%20-%20Made%20with%20Clipchamp.gif)

