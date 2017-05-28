# Buid OpenWRT for routers I have

# Plan 

1. Linksys WRT54G https://wiki.openwrt.org/toh/linksys/wrt54g
1. Netgear WNR3500v2/U/L https://wiki.openwrt.org/toh/netgear/wnr3500
1. MiWifi R1D https://wiki.openwrt.org/toh/xiaomi/start https://github.com/zdndanny/miwifi
1. TP-Link WDR6500

# Workflow - GitHub flow
* The master is initialized by cloning upstream OpenWRT; and keep updated by pulling from upstream
* A branch is created when I start experiment on a device
* Until the build for that device works, I will create pull request and merge it back to my master
* If needed, create pull requset to merge my changes back to upstream
