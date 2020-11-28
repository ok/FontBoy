Fontboy
=======

© 1999-2003 Oliver 'Madison' Kohl

Introduction
============
Fontboy is a small application to show your installed fonts in Haiku. You can get additional information of the selected font and a preview of the complete Unicode charset. Fontboy allows you to adjust the appearence to your desired needs and it's fast because Haiku is.

![FontBoy screenshot](FontBoy.png "FontBoy")


Features
========
- Watch all your installed fonts
- Browse the complete Unicode charset of a font
- Magnified view of single characters
- Drag & drop support
- Tooltips
- Highly customizeable


How to use Fontboy
==================
In the main window all installed fonts will be displayed by a sample text and their name and style. Use single click to select a font. Use double click to get detail information about a font. A right mouse click will show a popup menu where you can also open the detail window or refresh the fontlist after installing new fonts.

The detail window shows you further information about the selected font and graphical view of its Unicode character set. The selected character in the matrix will be shown in a bigger view on the left side. Use mouse or cursorkeys to change the selection. Use upper right navigation buttons or PageUp/PageDown keys to change page. Try drag & drop of characters!


Preferences
===========
To change the application settings open the preferences from the menu Edit.  
General let you toggle the splashscreen when starting Fontboy and turn off the ToolTips.  
List let you adjust the appearance of the fontlist in the main window.  
Details let you adjust the appearance of the detail window.  
When Live update! is selected all settings will be applied immediately.


Tips
====
- Drag & drop of a font in main window also sends a FFont object but there are not a lot of applications that support it.


Contact
=======
Web: http://fontboy.sourceforge.net  
EMail: fontboyapp@gmail.com  


Credits
=======
Splashscreen image by Thomas 'tHOM!' Einweg  
Coding & additional graphics by Oliver 'Madison' Kohl

Thanks and regards must go to:
- Dianne Hackborn (and others) for the FFont
- Marco Nelissen for his BubbleHelper class
- Eric Shepherd for his TPreferences class
- YNOP Talton for SplitPane class

