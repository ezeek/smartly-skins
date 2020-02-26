# hubitat-dashboard

Hubitat Dashboard UI tweaks - a collection of modern "skins" for Hubitat Dashboard.  

- *smartly* - loosely based on the modern SmartThings app, with some direction from ActionTiles Slate skin.

### Getting Started

As there isn't an actual 'skin' system for Hubitat Dashboard, the easiest way to use these skins is to create a new dashboard then following the copy and paste instructions.  If you would like to keep your existing tiles, you'll need to backup your "tiles:[]" data from your existing JSON, and replace the empty "tiles:[]" line in our JSON.

### Installing

- Copy and paste the contents of .json into Options > Advanced > Layout then 'Save JSON'.
- Copy and paste the contents of .css into Options > Advanced > CSS then 'Save CSS'.

### Updating color templates

- Copy and paste ```"customColors": []``` from the .json and paste into and clobber ```"customColors": []``` section of Options > Advanced > Layout then 'Save JSON'.

### Fonts and Background Images

To truly have everything under one roof, you'll need to host the /assets folder locally and update your css and json to reflect the local url of those files.   Font references are at the start of the CSS file, and background image is at the end of the JSON.

## TODO

- As-is when viewing a dashboard on a computer monitor, tablet or phone, the icons tend to appear larger on the smaller device (depending on device resolution).  The 'auto-zoom' branch will contain the development of CSS media queries, setting appropriate zoom based on device pixel width.  This should assist in making a dashboard useable between devices.


## Changelog

- *smartly*
> 1/15/2020 - Initial commit

## Authors

* **Eli Altman** - *Initial work* - smartly
