=== JQuery Slick Menu Widget ===
Contributors: Remix4
Donate link: http://www.designchemical.com
Tags: jquery, flyout, sliding, menu, vertical, horizontal, animated, navigation, widget
Requires at least: 3.0
Tested up to: 3.10
Stable tag: 1.0

jQuery Slick Menu creates a sticky, sliding menu widget from any Wordpress custom menu.

== Description ==

Creates a widget, which adds a sticky, sliding menu from any standard Wordpress custom menu using jQuery. Can handle multiple slick menus on each page and the location of each menu can be easily set from the widget control panel using a combination of the "location" option and the "offset".

= Menu Options =

The widget has several parameters that can be configured to help cutomise the sliding menu:

* Tab Text - Enter the text that you would like to use for the menu tab.
* Location - This sets the location of the slide out menu in the browser window. There are 6 different locations to choose from:
	* Top Left
	* Top Right
	* Bottom Left
	* Bottom Right
	* Left
	* Right
* Offset - The number of pixels from the edge of the browser window.
* Animation Speed - The speed at which the slide out menu will open/close
* Auto-Close Menu - If checked, the menu will automatically slide closed when the user clicks anywhere in the browser
* Skin - 8 different sample skins for styling the slick container are available to give examples of css that can be used to style your own slick menu.

[__See demo__](http://www.designchemical.com/lab/demo-wordpress-jquery-slick-menu-plugin/)

== Installation ==

1. Upload the plugin through `Plugins > Add New > Upload` interface or upload `jquery-slick-menu` folder to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress
3. In the widgets section, select the jQuery Slick Menu widget and add to one of your widget areas
4. Select one of the WP menus, set the required settings and save your widget

== Frequently Asked Questions ==

= The menu appears on the page but does not work. Why? =

One main reason for this is that the plugin adds the required jQuery code to your template footer. Make sure that your template files contain the wp_footer() function.

Another likely cause is due to other non-functioning plugins, which may have errors and cause the plugin javascript to not load. Remove any unwanted plugins and try again. Checking with Firebug will show where these error are occuring.

== Screenshots ==

1. JQuery Slick Menu widget in edit mode
2. Locations For Menu Settings

== Changelog ==

= 1.0 = 
* First release

== Upgrade Notice ==
