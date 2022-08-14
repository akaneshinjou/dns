# HOW TO UNBLOCK BLOCKED SITES USING SECURE DNS
 
## Introduction
Whenever you open a website, your device will send DNS request, most internet connection uses ISP's DNS servers by default, this mean your ISP & Government can affect how you access website. This is how site blocking mostly happen, and also if your ISP have technical problem it may result in some website become inaccesible. The workaround for this is encrypting the DNS request so your ISP can't interfere what sites you are accessing. More info on DoH : https://en.wikipedia.org/wiki/DNS_over_HTTPS.

Read guide below to unblock blocked sites, if doesn't work please read the next section on how to deal with it.
 
 
## Easy App Solution (Windows/macOS/Linux/iOS/Android)
Cloudflare 1.1.1.1
1. Install 1.1.1.1 app from https://one.one.one.one/.
2. Open the app.
3. Enable it, tap OK (one-time).  
4. Done.  
Note: try with & without warp feature enabled, see what work best.  

## IF DOESN'T WORK
If that doesn't work, try 'other options' section before trying next option.  
  
Try use tools like PowerTunnel (Bypass more block method but more complicated to setup)  
1. Download & Install Java (https://www.java.com/en/download/)
2. Download https://github.com/krlvm/PowerTunnel/releases/latest (.jar file)
3. Run .jar file
4. Click start server  

Android version : https://github.com/krlvm/PowerTunnel-Android/releases/latest 
  
If all method still doesn't work you can use VPN, it almost guarantee will work, the only downside is it's not free. There is free VPN but we can't guarante the speed, privacy, or quality of the service. This should be the last resort.  
free VPN : https://proprivacy.com/vpn/comparison/free-vpn-services (any VPN will work, even not from this article)
 
## OTHER OPTIONS (IF YOU HAVE PROBLEM WITH 1.1.1.1 APP)

###### #Browsers Only (May not as effective)

Google Chrome 83+
1. Open Menu > Settings.
2. Open Security or `chrome://settings/security`.
3. Enable Use secure DNS.
4. Select With and click the dropdown next to it.
5. Choose Cloudflare or Google or other provider.
 
Mozilla Firefox 60+
1. Open Menu > Options.
2. Scroll down to the bottom.
3. Click Settings under Network Settings.
4. Check Enable DNS over HTTPS.
5. Choose Cloudflare or NextDNS or other provider.

Other browsers might also have this feature, try find it in settings.  
Other desktop app : Simple DNSCrypt & Yoga DNS 
  
  
###### #Android

Trust DNS
1. Install Trust DNS - DNS Changer from Play Store or F-Droid.
2. Open the app.
3. Tab connect button.  
Note: You can't use VPN app while using this app.
 
Built-in DNS-over-TLS resolver (Android 9+)*
1. Open Settings.
2. Tap Network & internet > Advanced > Private DNS.
3. Select Private DNS provider hostname.
4. Enter 1dot1dot1dot1.cloudflare-dns.com or dns.quad9.net or other provider you prefer.  
Note: Device restart may be required to clear DNS cache.
* This tutorial is for vanilla Android, steps may be different for other OSes.
 

###### #iOS

DNS Cloak
1. Install DNS Cloak from App Store.
2. Open the app.
3. Select DNS server you want, Cloudflare DNS are recommended.
4. Tap Play/Start button on the top left.  
Note: You can't use VPN app while using this app.
  
  
###### #Gaming Consoles

DNS Change  
Full guide : https://developers.cloudflare.com/1.1.1.1/setup-1.1.1.1/gaming-consoles  
Note: This is just normal DNS change, may not work to ublock, but this the only thing console can do

DoH on Router  
setup the secure DNS on your internet router. The guide is vary between router device. You need to search specifically yourself or ask your ISP for help.
example guide : https://mariushosting.com/synology-router-how-to-enable-dns-over-https/  
