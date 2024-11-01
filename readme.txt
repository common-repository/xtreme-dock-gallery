=== Xtreme Dock Gallery ===
Contributors: Flashtuning 
Tags: flash, swf, menu, dock, gallery, banner, xml, photo, autoplay, horizontal, vertical, zoom, flashvars, tooltip, as3, scroll, scroller, free, plugin, images, transitions, effects, fullscreen
Requires at least: 2.9.0
Tested up to: 3.0.1
Stable tag: trunk

The most advanced Dock Image Gallery application for Flash. Clean OOP source code - No Flash Knowledge required to insert the Banner SWF inside the HTML page(s) of your site.

== Description ==

XML Image Dock Gallery / XML Photo Gallery Rotator / XML Image SlideShow.

**Features**

* Fully customizable XML driven content
* Customizable width, height and item size
* Unlimited number of images ( JPG, PNG, BMP, GIF ) and SWF support
* Easy to use XML file for images / titles / descriptions and links
* View banner images by using the number buttons and left / right end arrow
* AutoPlay / AutoScroll / Previous / Next with global or individual timer for each image
* Time period adjustable from the XML file (in seconds)
* Both horizontal and vertical dock menu orientation support
* Dynamic image reflection with transparency, distance and direction settings
* Zoom amount and zoom speed setting on mouseover with zoom/position influence option on adjacent items
* Optional menu image highlighting feature for the active / inactive items
* Items alignment and rollover mouse movement speed options
* Define menu image borders size/color from within the XML configuration file
* Custom Horizontal / Vertical / Matrix orientation support for the navigation buttons
* Multiple mask transition effects such as Move, Fade, Tile, Radial Fade …
* Global or individual timer and transition definition for each text paragraph
* HTML / CSS driven descriptions, tooltips, text wrapping, font embedding, background and border color / size support
* Set URL links within the description text or when pressing on individual images
* Display the items in the order they appear in your XML file or in a random order
* Optional you can show / hide the navigation buttons and adjust each button position
* Optionally set the XML settings file path in HTML using FlashVars
* Full Screen mode support, you can use it as a banner and slidewhow and image gallery

== Installation ==

1. Download the plugin and upload it to the **/wp-content/plugins/** directory. Activate through the 'Plugins' menu in WordPress.
2. Download the [Free XtremeDockGallery](http://www.flashtuning.net/flash-samples/XtremeDockGalleryFree.zip "Xtreme Dock Gallery") and copy the content of the archive in **wp-content** folder. (e.g: "http://www.yoursite.com/wp-content/flashtuning/xtreme-dock-gallery")
3. Insert the swf into post or page using this tag: `[xtreme-dock-gallery]`. The default values for width and height are 595 420. If you want other values write the width and height attributes into the tag like so: `[xtreme-dock-gallery width="yourvalue" height="yourvalue"]`
4. To configure the dock gallery general parameters use the dockgallery-settings.xml. For individual dock gallery items use the dockgallery-contents.xml file. (tooltips, image path, image link and more)
5. If you want to use multiple instances of Xtreme Dock Gallery on different pages. Follow this steps:
   a. There are 2 xml files in **wp-content/flashtuning/xtreme-dock-gallery** folder: **dockgallery-settings.xml**, used for general settings, and **dockgallery-content.xml**, used for individual items.
   b. Modify the 2 xml files according to your needs and rename them (eg.: **dockgallery-settings2.xml**, **dockgallery-content2.xml**)
   c. Open the **dockgallery-settings2.xml**, search for this tag `< object param="contentXML"	value="dockgallery-content.xml" />` and change the attribute **value** to **dockgallery-content2.xml** .
   d. Copy the 2 modified xml files to **wp-content/flashtuning/xtreme-dock-gallery** .
   e. Use the **xml** attribute `[xtreme-dock-gallery xml="dockgallery-settings2.xml"]` when you insert the dock gallery on a page.
6. Optionally for custom pages use this php function: `xtremeDockGalleryEcho(width,height,xmlFile)` (e.g: **xtremeDockGalleryEcho(595,420,'dockgallery-settings.xml')** )



= Remove the Flashtuning.net logo =

 If you don’t want to have the Flashtuning.net logo on the top left corner, you'll have to purchase the [commercial package](http://www.flashtuning.net/flash-xml-image-viewers-galleries/x-treme-dock-gallery.html "FT Xtreme Dock Gallery"). You'll also have access to the fla file. After downloading the commercial archive, overwrite the swf file from the `/wp-content/flashtuning/xtreme-dock-gallery` directory.

== Screenshots ==

1. Fully customizable XML driven content. No Flash Knowledge required to insert the Dock Gallery SWF inside the HTML page(s) of your site.

