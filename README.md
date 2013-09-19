openwrt-libircclient
====================

Add this to your feeds.conf:

    src-git libircclient git://github.com/narced133/openwrt-libircclient.git

Then update and install the feed and use menuconfig to add the package:

    ./scripts/feeds/update libircclient
    ./scripts/feeds/install libircclient
    make menuconfig
