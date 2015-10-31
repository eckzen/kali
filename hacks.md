to check if your card can do packet injection after creating the monitor mode interface open a terminal and type in:

aireplay-ng -9 mon0

This will tell you your percentage of injection.

##Check airmon
airmon-ng check kill (this will exit network manager,wpasuplicant and dhclient )
airmon-ng start wlan0mon (or whatever your interface is)

iwconfig wlan0mon           #fishy

Start / Stop Networking service

    /etc/init.d/networking stop
    /etc/init.d/networking start

Stop and Start Networking Manager

    /etc/init.d/network-manager stop
    /etc/init.d/network-manager start
Restart
    /etc/init.d/network-manager restart

Bring up network interface

    # ifconfig or
    # ifup eth0

http://www.blackmoreops.com/2015/03/26/setup-dhcp-or-static-ip-address-from-command-line-in-linux/

