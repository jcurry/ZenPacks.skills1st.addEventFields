==================================================================================================
ZenPack to create fields to display in an Event Console and to package Triggers and Notifications
==================================================================================================

Description
===========

All you need are valid files in the zep directory of the ZenPack.
The zep.json file defines new event attributes to be selectable to be
displayed as a column in an Event Console.

The actions.json file defines Notifications and Triggers.

Ensure you read the README_zep_json in the json directory.

zep.json.example and actions.json.example are created automatically as
samples when you create a new ZenPack in the GUI.


Requirements & Dependencies
===========================

    * Zenoss Versions Supported: 4.x
    * External Dependencies: 
    * ZenPack Dependencies:
    * Installation Notes: Restart zenhub and zopectl after installation
    * Configuration:

The result of this is that all devices should have a "My Example Menu 1" left-hand menu
but ExampleDevice objects have a slightly different page from all other devices.


Download
========
Download the appropriate package for your Zenoss version from the list
below.

* Zenoss 4.0+ `Latest Package for Python 2.7`_

ZenPack installation
======================

This ZenPack can be installed from the .egg file using either the GUI or the
zenpack command line but, since it is demonstration code that you are likely to 
want to modify, it is more likely installed in development mode.  From github - 
https://github.com/jcurry/ZenPacks.skills1st.addEventFields  use the ZIP button
(top left) to download a tgz file and unpack it to a local directory, say,
$ZENHOME/local.  Install from $ZENHOME/local with:

zenpack --link --install ZenPacks.skills1st.addEventFields

Restart zenhub and zopectl after installation.



Change History
==============
* 1.0.0
   * Initial Release

Screenshots
===========

.. External References Below. Nothing Below This Line Should Be Rendered

.. _Latest Package for Python 2.7: https://github.com/jcurry/ZenPacks.skills1st.addEventFields/blob/master/dist/ZenPacks.skills1st.addEventFields-1.0.0-py2.7.egg?raw=true

