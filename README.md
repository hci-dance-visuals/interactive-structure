# interactive-structure
The "interactive-structure" prototype demonstrates one possible way of visualizing an artificial digital character interacting with a live performer on stage. This prototype uses Isadora (a real-time media manipulation software by Mark Coniglio / Troika Ranch, see: https://troikaranch.org/).

### dependencies

You need to download Isadora software version v2.6.1 (Mac and Windows)to work with the provided patch: https://support.troikatronix.com/support/solutions/articles/13000029004-where-can-i-download-older-versions-of-isadora-

You can ignore the message coming up when opening the patch (which asks for missing plug-ins) to work with this patch. However, if you want to try out the mocap-avatar prototype as well, you need to have the plug-ins installed. They can be found here:

https://troikatronix.com/plugin/rutt-etra-for-isadora-2/;
https://troikatronix.com/plugin/tt-ffgl-for-isadora-2-3/ and 
https://support.troikatronix.com/support/solutions/articles/13000047284-isadora-2-troikatronix-freeframegl-pack


### instructions to run

After installing Isadora v2.6.1 (and eventually) the plug-ins listed above, you work with the interactive-structure patch. There is a simple GUI (called control interface in Isadora), which allows you to make choices suggested by the artificial digital character in each scene. To see the programming level "underneath" go to the menu/view/Actor/Control Split. Note that this patch only serves to demonstrate the prototype. In the (real world) rehearsal scenario you would create contents and interaction strategies according to your own dramaturgical ideas and needs. You can also substitute the controll interface with OSC controllers (We have worked with TouchOSC).
