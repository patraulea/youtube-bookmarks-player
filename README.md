# Youtube Bookmarks Player

A browser extension that plays your bookmarked youtube videos as a playlist. 

Tested in Chrome and Firefox. It will look for a 'playlist' bookmarks folder, pick 
Youtube URLs at random or sequentially depending on the settings and play a new 
one when the current video ends. See the options page for more configuration.

### Install in Chrome
  - copy everything to a local dir
  - go to chrome://extensions
    - enable "Developer mode"
    - click "Load unpacked extension" at the top.

### Install in Firefox
  - copy everything to a local dir
  - overwrite manifest_for_firefox.json over manifest.json
  - go to about:debugging
    - enable "Add-on debugging"
    - click "Load temporary add-on"
