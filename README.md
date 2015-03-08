# CoolirisView Component
CoolirisView Component for Oracle WebCenter Content

Overview
---------------------

This component incorporates the Cooliris image viewer (www.cooliris.com) into the WebCenter Content search results.  
This new version of the component, embed the CoolIris as a Search Results and DO NOT need to install the plugin.

Now works offline, no internet access needed.

This really helps show off the digital asset management capabilities. 

You still can utilizes their free browser plug-in to provide a very graphical and easy to use slideshow.  

Installation:
1. Install the CoolirisView component
2. Restart Content Server

Now when you do a search result, you will have an additional Search Result view called 'CoolIris View'.



Please check the coolirisview_environment.cfg for aditional parameters and configurations




Roadmap: Admin Page to change options such as # lines. Central Media RSS/Geo RSS provider. HTML5 Wall (No need to use flash anymore). iPad/iPhone Support.

Notes
------

1) Some users have reported that the Build 3, if installed on the UCM 11g and tried to uninstall, could corrupt the weblayout dir
    - To solve this, just install a higher build. If you need to uninstall, just uninstall the component.

Change Log
----------
03/08/2015 - [Build 9] 11.1.1.8.8 Tested. CoolIris Flash Object updated to use the cleaner build, without any analitics or external calls. Now using builds from https://github.com/cooliris/embed-wall. Remove the option to use the hosted build, because will be shutdown in 3/31/2015. cooliris.swf build r900 implemented.

01/19/2012 - [Build 8] CoolIris Flash Object updated to build r42925.

05/18/2011 - [Build 7] PS4 Tested. XML Constructor Template changed. Thumbnail problem solved. Thanks aasami for the insight. CoolIris Flash Object updated to build r42415.

03/29/2011 - [Build 6] Ability to change the location of the Cooliris Object, from local (Standalone, no internet access needed)
to use the cooliris website (Internet access needed, latest published version of the Flash Object). CoolIris Flash Object updated to
build r41829. Now reflects the new logo "LiveShare by Cooliris". Media RSS redesigned.

03/01/2011 - [Build 5] Minors bugs fixed. Security Improved, support to use tokens. CoolIris Flash Object updated to build r33888.
Using the swfobject library to instantiate the Flash Object. 

02/28/2011 - [Build 4] Completely changed from the last build, now works like a new Search Results template
with the 3D wall embeded on the page. Do not need the external plugin anymore. SiteStudio Gallery removed
from this build, you can embed your own 3D wall using the search results feed service. Minors bugs fixed.
Support for the UCM 11g.

02/19/2009 - [Unofficial] [Build 3] Added FLV video support, for rendentions or for primary file. 
Coded added to support FLV videos of VM_BASE 6.5 without thumbnails.

02/17/2009 - [Unofficial] Small fixes. xComments = Media Description. PicLens Lite 1.3.1.
Roadmap: Video support, dynamic background, Lytebox, New SS fragment for 10gR4, Galleries...

01/10/2009 - [Unofficial] Changed the name to CoolIrisView. Changes to support new cooliris version. 
PicLens Lite 1.2. Included multilanguage support. Oracle Logo. XML Template Changed.

05/09/2008 - Changed the logic so that users using Firefox and the 'Trays' layout in UCM will not see
the PicLens View search result choice.  PicLens does not appear to work correctly when called from a 
frame.  Internet Explorer seems to work fine.

04/02/2008 - Initial release
