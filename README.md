# interactive-structure
The "interactive-structure" prototype demonstrates one possible way of visualizing an artificial digital character interacting with a live performer on stage. This prototype uses Isadora (a real-time media manipulation software by Mark Coniglio / Troika Ranch, see: https://troikaranch.org/) for image processing and interaction design with incoming data streams (video and OSC data). 

### dependencies

1. You need to download Isadora software version v2.6.1 (Mac and Windows)to work with the provided patch: https://support.troikatronix.com/support/solutions/articles/13000029004-where-can-i-download-older-versions-of-isadora-

2. Please download and install these plug-ins: https://troikatronix.com/plugin/rutt-etra-for-isadora-2/ https://troikatronix.com/plugin/tt-ffgl-for-isadora-2-3/ and https://support.troikatronix.com/support/solutions/articles/13000047284-isadora-2-troikatronix-freeframegl-pack


### instructions to run

After installing Isadora v2.6.1 and the plug-ins listed above, you can run and work with the mocap-avatar patch. There is a simple GUI (called controll interface in Isadora), which allows you to manipulate certain parameters in each scene. To see the programming level "underneath" go to the menu/view/Actor/Control Split. Note that this patch serves to demonstrate the prototype. In the (real world) rehearsal scenario you would create contents and interaction strategies according to your own dramaturgical ideas and needs. You can also substitute the controll interface with OSC controllers (We have worked with TouchOSC).
