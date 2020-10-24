# mifitxiaomipiholelist
MiFit by Xiaomi PiHole Block List

Block List for PiHole to block the countless connections made by the MiFit App to Chinese webservices like amap, weibo, qq, etc. E.g. Mifit is constantly trying to connect to amap services, even if it's running in the background. Indicates that it is sending your location data to amap.


Note: I won't add most of the Xiaomi/Huami connections to the list (like api-mifit-de.huami.com ), as Xiaomi apps won't be able function properly then. This list is for unwanted connections to third-party Chinese services. Only a handful Xiaomi connections have been added.

Examples:
amap
umeng
qq
weibo
etc.

As of 02/04/2020, no new third party connections to Chinese services have been detected or found in the apk.

Update 2020/05/26: removed abroad.apilocate.amap.com so weather updates are working again. Add abroad.apilocate.amap.com to your blacklist if you need it blocked.

YOU'RE WELCOME TO CONTRIBUTE! I'll review your commits and may accept them.

Copy this into your Blocklist:
https://raw.githubusercontent.com/SweetSophia/mifitxiaomipiholelist/master/mifitblocklist.txt

