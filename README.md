# CoolirisView Component
CoolirisView Search Results Component for Oracle WebCenter Content


Date: 	Mar, 2015
Component Version: 	2015_01_08(build 9)
Product and Version: 	Oracle WebCenter Content Server
Author: 	Adao.Junior
Info: www.ateam-oracle.com / blog.contentra.com

Component Information
-------

This sample component is AS-IS based, without any kind of support.

This component incorporates the Cooliris image viewer (www.cooliris.com) into the WebCenter Content search results.

An included Flash Object in embedded to the Search Results and do not need to install any plugin.

Works offline, no internet access needed.

This really helps show off the digital asset management capabilities.

You still can utilizes their free browser plug-in to provide a very graphical and easy to use slideshow.

Installation Instructions:
-------
Warning: The recommendation was you perform all necessary backups prior to applying this component.

For additional information see the Content Server Getting Started Guide which contains information on System Maintenance and Backup Strategies.

1. Install the CoolirisView component

2. Restart Content Server

Now when you do a search result, you will have an additional Search Result view called 'CoolIris View'.

Please check the coolirisview_environment.cfg for additional parameters and configurations.

How to Uninstall this Component:
-------
Just uninstall the component from the WebCenter Content Admin Server or Component Wizard.

Compatibility:
-------
    Oracle WebCenter Content 11g PS5+
    Oracle UCM 11g+.
    Oracle UCM 10gR3.

Notes:
-------
    Issues with Build 3

    - Some users have reported that the Build 3, if installed on the UCM 11g and tried to uninstall, could corrupt the weblayout dir, to solve this, just update to a higher build, and then uninstall.

Roadmap:
-------
Admin Page to change options such as # lines. Central Media RSS/Geo RSS provider. HTML5 Wall (No flash, yeah!!!). iPad/iPhone Support.

Release History:
-------
    2015_03_08(build 9) -
        11.1.1.8.8 Tested
        Cooliris logo is back.
        Resources publishing updated.
        No external calls or analytics. Cleaner and faster build.
        Hosted (coolirisonline) support removed.
        Now using builds from https://github.com/cooliris/embed-wall.
        CoolIris Flash Object updated to build r900.
    2012_01_19(build 8) -
        PS5 Tested.
        WebCenter Content Rebranding.
        Resources publishing updated.
        Changed CoolIris.swf and SWFObject places.
        CoolIris Flash Object updated to build r42945.
    2011_05_18(build 7) -
        PS4 Tested.
        XML Constructor Template changed.
        Thumbnail problem solved (Thanks aasami for the insight).
        CoolIris Flash Object updated to build r42415.
    2011_03_29(build 6) -
        Added ability to change the location of the Cooliris Object, from local (Standalone, no internet access needed) to use the cooliris website (Internet access needed, latest published version of the Flash Object).
        Now reflects the new logo "LiveShare by Cooliris".
        Media RSS redesigned.
        CoolIris Flash Object updated to build r41829.
    2011_03_01(build 5) - Minors bugs fixed. Security Improved, support to use tokens. CoolIris Flash Object updated to build r33888. Using the swfobject library to instantiate the Flash Object.
    2011_02_28(build 4) - Completely changed from the last build, now works like a new Search Results template with the 3D wall embeded on the page. Do not need the external plugin anymore. SiteStudio Gallery removed from this build, you can embed your own 3D wall using the search results feed service. Minors bugs fixed. Support for the UCM 11g.
    2009_02_19(build 3) - Added FLV video support, for rendentions or for primary file. Coded added to support FLV videos of VM_BASE 6.5 without thumbnails.
    2009_02_17(build 2)- Small fixes. xComments = Media Description. PicLens Lite 1.3.1. Roadmap: Video support, dynamic background, Lytebox, New SS fragment for 10gR4, Galleries...
    2009_01_10(build 1) - Changed the name to CoolIrisView. Changes to support new cooliris version. PicLens Lite 1.2. Included multilanguage support. Oracle Logo. XML Template Changed.
    2008_05_09 [PicLens View] - Changed the logic so that users using Firefox and the 'Trays' layout in UCM will not see the PicLens View search result choice. PicLens does not appear to work correctly when called from a frame. Internet Explorer seems to work fine.
    2008_04_02 [PicLens View] - Initial release

