### 0.9
* Optional bold label for current desktop
* Some changes regarding default configuration
* Some irrevelant changes to the configuration dialog

### 0.8
* Plus button (new desktop button) has now some customization options
* Advanced section of the configuration dialog now contains the applet version

### 0.7.1
* Added an option to show only current desktop

### 0.7.0
* Added more desktop label styles
* Added partial support for vertical panel layout
* Changed default desktop label style
* Changed default value for vertical margins
* Plus button position and size has been arguably improved
* Plus button is no longer displayed when it can't be even used
* Fixed a bug with mouse wheel desktop switching after using a touchpad
* Some minor label and checkbox changes to the configuration dialog

### 0.6.0
* It's now possible to precisely set button dimensions and spacing in pixels
* Plus button for adding new desktops is no longer displayed as a yellow emoji
* Improved responsiveness by making KWin scripts compatibility mode disabled by default

### 0.5.1
* Added a new indicator style that just colors the desktop label
* Added an option to not override the opacity of custom indicator colors
* Fixed broken desktop button animation when removing a desktop
* Fixed black color desktop label flashing when adding or removing a desktop
* Changed the plus button opacity to follow the idle desktop label dimming option
* Changed the renaming desktop popup to be more compact

### 0.5.0
* Added an option to execute a command after adding a desktop
* Added an option to set no spacing between desktop buttons
* Added an option to disable desktop label dimming for idle desktops
* Added an option to choose a different desktop indicator style (line, side, block, rounded, full)
* Added an option to set custom desktop indicator color for idle desktops (or hide, if alpha = 0)
* Changed the plus button symbol to be better aligned with the rest of used font's characters
* Fixed broken empty desktop indicators when moving some shell related dialogs between desktops
* Fixed broken compilation on older systems (Kubuntu 18.04)

### 0.4.6
* Fixed broken empty desktop indicators once again...
* Fixed broken automatic desktop creation when moving a window to an empty desktop
* Added an option to automatically rename desktops once they become empty (disabled by default)

### 0.4.5
* Added some things regarding KWin scripts compatibility
* Fixed some race conditions related to async signal handling

### 0.4.4
* Fixed initially missing empty desktop indicator after loading the applet

### 0.4.3
* Added an option to decrease or increase desktop entry width
* Fixed default spacing between desktop entries to be medium instead of large
* Fixed some context menu actions and keyboard shortcuts to be disabled when using GNOME-like features

### 0.4.2
* Fixed unwanted margin at the right side of the applet
* Added an option to decrease or increase spacing between desktop entries
* Added an option to distinct desktop indicator for occupied idle desktops (enabled by default)
* Added an option to set custom desktop indicator color for occupied idle desktops
* Changed desktop indicator color for desktops other that the current one to match label color

### 0.4.1
* Added support for mouse wheel desktop switching
