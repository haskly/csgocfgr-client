# CS:GO Configr Changelog

### 0.1.4

* [ENHANCEMENT] Update dependency ember to 1.8.0-beta.1
* [ENHANCEMENT] Update dependency ember-data to 1.0.0-beta.10
* [ENHANCEMENT] Update to ember-cli 0.0.46
* [ENHANCEMENT] Update README with more instructions and helpful links (provided by ember-cli)
* [ENHANCEMENT] Added the ability to edit an existing config. It doesn't overwrite the old one, it makes a new config with its own unique URL
* [ENHANCEMENT] Added some comments to the code to explain what's going on in some parts
* [BUGFIX] Fix issue with ' key outputting incorrect text in preview window (this time at config url)

### 0.1.3

* [ENHANCEMENT] Update dependency csgocfgr-plugins
* [ENHANCEMENT] Update dependency ember-cli-simple-flash-message
* [ENHANCEMENT] Add ability to import settings via .cfg file or pasting in some config settings
* [BUGFIX] Fix text spilling out of keyboard buttons on keybinds page
* [BUGFIX] Improve crosshair preview lock positioning to compensate for new import module
* [ENHANCEMENT] Add auto focus text box when opening keybind modal

### 0.1.2

* [ENHANCEMENT] Add reset to defaul values button for most input fields. Radar size and scale were having issues so it is left out for now on those
* [ENHANCEMENT] Decreased font size inside popup bubbles
* [BUGFIX] Fix issue with escape key not updating in preview window
* [BUGFIX] Fix issue with ' key outputting incorrect text in preview window

### 0.1.1

* [BUGFIX] Add new landing page to hopefully prevent redirect loop (not allowing browser back button to leave site)
* [BUGFIX] Fix firefox crosshair preview window width and image position
* [BUGFIX] Fix select boxes getting hidden behind other elements
* [BIGFIX] Update default values for a few keys that were incorrect
* [ENHANCEMENT] Change base font size to 16px
* [ENHANCEMENT] Change button font size and padding for download and save buttons
* [ENHANCEMENT] Clear data store when visiting landing page
* [ENHANCEMENT] Change crosshair preview to not overlap fields on desktop, remove fixed preview for smaller devices
* [ENHANCEMENT] Add Mouse over to expand crosshair preview on desktop
* [ENHANCEMENT] Improve info bubble pop-up descriptions with command name
