#BCM53125 Driver for Mainline Kernel and swconfig utility

I managed to port the OpenWRT B53 driver to the mainline kernel. It wasn't a huge job, just updating a few lines of code to make it compatible. I have it running and working with 3.19 rc3.

I can't remember all the steps exactly, but I've included as much as I can remember. The code within this repo is taken directly from the source files which were successfully built.

I wasn't able to create a patch for the Makefiles and Kconfigs, but I added a patch from a pullrequest by Florian Fainelli which can be found here http://thread.gmane.org/gmane.linux.network/288039.

If anyone manages to get this working, please make a pull request to make this easier to do in the future.