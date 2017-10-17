# AutoFi
Auto-login assistant for WiFi captive portal.  
Download: [[latest-apk](https://github.com/harsgak/AutoFi/blob/master/factory/kids/AutoFi.32.apk?raw=true)]

## Why AutoFi?
On IISER Wifi network it is not uncommon to get disconnected and reconnected automatically while moving or due to signal fluctuations. When this happens, old session dies and often a new captive portal requests you for login again.

Sometimes it just fails silently, you are connected to network but login has expired. This can be very frustrating and interrupt critical tasks such as WhatsApp, Facebook, IISERMail etc and leave you without updates until you remember to log in again.


## How to use AutoFi?
After installing just enter your username and password and toggle the Activate AutoLogin switch on. Then start your WiFi and connect to any supported network.

As long as the switch stays on IISER-AutoFi will automagically login for you every time your phone connects to any IISER Pune WiFi network. You can now blissfully forget about captive portal logins on your android device and go straight to browsing.

When temporarily not needing AutoFi's services or need to change credentials just toggle the Activate AutoLogin switch off. 
_Don't forget to toggle it back on later_


## Compatibility and support. 
This app should work on any device with WiFi and Android version 5.0 and up. Currently supported IISER networks are ~~IISERUG1, IISERUG5, IISERPG~~ `Students` and `Guest`. Note that Faculty, Alpha, IISERCONF are currently **not** supported by default.  

Experimental support is available for private hotspots. If you rename your hotspot to `AutoFi-free` then AutoFi will treat it like `Students` and should automatically log you in. Please report issues if any. 


For support, feature request or sending kudos you can send an email by long tapping the developer tags in the app. If you use Github I would prefer you just star this repo and open an [issue](https://github.com/harsgak/AutoFi/issues) for whatever you need.

## Notice
As of 28 September 2017, IISER has discontinued various student network SSIDs and opened a singular `Students` SSID for all students. To address this change an update to AutoFi is forthcoming. In the meanwhile AutoFi users can continue getting logged in automatically by switching to `Guest` network.

Update: `Students` SSID is now supported from version 1.29 onwards. Link to latest-apk is provided at beginning of this readme.
