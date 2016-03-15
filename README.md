# TouchDesigner Collector
TouchDesigner 088 component that collects all assets in a project and copies them to a specified path.

##Usage
Drag and drop the tox file into your project. Open the parameters window and go to the 'Collector' page. This page has 2 parameters. The first is the path that you'd like all your media to be copied to. The second is a pulse button that triggers the copying.

Once you click 'Copy', because there is no threading, TouchDesigner will look like it is frozen, but Windows is copying in the background. Sit tight, and wait for TouchDesigner to respond. All status messages will be printed out to the Textport when all the copying is complete.

##Build and version
Tested on TouchDesigner 088 64-bit build 58910.

##Contribution
Feel free to fork, create issues, request features in the issues, or pull request if you find any bugs. If you end up using this, feel free to give us (nVoid) a shoutout! Enjoy!
