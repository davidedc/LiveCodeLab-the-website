Livecodelab-website
===================

Just the website for LiveCodeLab (website at: http://livecodelab.net/ ). Nothing to follow or star in here, you probably want to take a look at the proper LiveCodeLab code here: https://github.com/davidedc/livecodelab

What's with that "play" directory?
==================================

It contains a build obtained from the sources in the livecodelab repo (where the actual livecodelab engine is). We used to have this as "submodule" but we found it easier to put it in by hand.

How do I serve this?
====================

Any webserver is good. The classic SimpleHTTPServer works fine.

Is there a build process for this?
====================

No, the website on its own has no build process. The LiveCodeLab build follows a build process instead, documented in the LiveCodeLab "engine" github proper, linked above. We then copy the build in here and we are done.

Browser compatibility
====================
Let's cut to the chase and talk about IE: LiveCodeLab works on IE10 and following, so ideally this website should look OK in those versions...
