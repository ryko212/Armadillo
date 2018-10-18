# Armadillo
A layered approach to portable security.

1. Threat References:
    1. https://www.eff.org/deeplinks/2017/08/how-captive-portals-interfere-wireless-security-and-privacy
    1. https://www.consumer.ftc.gov/blog/2015/02/hotel-wi-fi-weigh-risk
    1. https://www.wired.com/story/russian-spies-indictment-hotel-wi-fi-hacking/ 
    1. https://www.independent.co.uk/travel/news-and-advice/travel-website-hackers-cyber-crime-phishing-holidays-a8382771.html 
    1. https://www.theregister.co.uk/2014/08/04/hotel_booking_phish/ 
    1. https://www.wired.com/story/fancy-bear-hotel-hack/
    1. https://www.consumer.ftc.gov/blog/2015/02/hotel-wi-fi-weigh-risk
    1. https://www.bbb.org/northern-alabama/news-events/news-releases/2017/07/hackers-target-hotel-wi-fi/

1. Mitigations that Armadillo provides:
    1. Does:
        1. Prevent scanning
        1. Allow users to selectively filter traffice
    1. Does not:
        1. Prevent MITM
        1. Prevent traffic capture/examination
1. Get stuff
    1. Router
        1. Nexx 3020F
        1. https://www.aliexpress.com/item/New-Smallest-WT3020F-300M-Portable-Mini-Router-802-11-b-g-n-AP-Repeater-Wifi-Wireless/32217024405.html
    1. Switch
        1. Diewu 5 port 10/100
        1. https://www.aliexpress.com/item/5-Ports-Fast-Ethernet-RJ45-10-100Mbps-Network-Switch-Switcher-Hub-Desktop-laptop-Portable-Travel-Lan/32771625897.html
    1. Pi
        1. Pi 3 B+
        1. https://www.adafruit.com/product/3775
    1. Case/Rack
        1. 3d Printed Rack
            1. https://www.thingiverse.com/thing:2795195 
            1. Several other options
                1. Search thingiverse.com
    1. Power
        1. USB power supply
            1. Consierations
                1. Power consumption with everything running
                    1. Pi ~2A
                    1. Nexx 3020F ~0.5A
                    1. Diewu Switch ~0.5A
                1. Number of usb ports
                    1. usb port for each device
    1. Support equipment
        1. Ethernet cables
        1. Micro usb cable/device
                
1. Configure stuff
    1. Install DDWRT
        1. https://wiki.openwrt.org/toh/nexx/wt3020
        1. Things to watch out for:
            1. 
            
    1. Configure Network Firewall Rules
        1. Uncheck all rules except for "Allow DHCP on WAN."
        1. IPTables
        
    1. Install Raspian
    1. Install SMB
    1. Install Plex
1. Employment
