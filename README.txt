# InternetSecurity

Topic: Internet-Router
------------------
Use common WLAN-Router like TP Link Archer BE550 Tri-Band Wi-Fi 7
Use common WLAN-Repeater/Extender like TP-Link RE655BE Tri-Band Wi-Fi 7
Use common Network-Switches like TP-Link TL-SG108-M2
Enable Two-factor authentication (2FA) on your WLAN-Router if possible
Update and check the firmware of your WLAN-Router fequently/automatically
Change the default admin password via a password-generator on your WLAN-Router, -Repeater/Extender to a new one (20 digits) 
Change the DNS server on your WLAN-Router to Quad9 (Primary DNS 9.9.9.9 / Secondary DNS 149.112.112.112). It's privacy focused and blocks stinky ad- and malware-stuff (https://www.quad9.net/)

Topic: WIFI
------------------
Choose a strong / long unique wlan-name (ssid) and password (20 digits) for every active wlan  
Choosing your name, adress, other personal or ISP-information as a wlan-name or as a wlan-password not smart.
Switch to valid and not occupied WiFi-Channel, aviod the "WiFi auto selection" for 2,4 GHz, 5 GHz, 6 GHz, 7 GHz
Enable the Firewall on your WLAN-Router if possible
Enable the Quality of Service (QoS) on your WLAN-Router if possible
Enable a VPN (like Wireguard) on your WLAN-Router if possible and select the fastest VPN connection
Enable MAC Filtering on your WLAN-Router if possible
Enable WPA3 Security (WPA3 AES) or WPA2 Security (WPA2 AES) on your WLAN-Router for any of all of your WLANs
Disable WLANs if you don't need them (Guest-WLANs, etc, Turn off WLANs from 01:00 AM to 07:00 AM, holidays, weekend-trips, etc)
Disable WLAN/UPnP (Universal Plug and Play) if you don't need it
Disable WLAN/WPS if you don't need it
Gaming over WiFi is possible but not smart. Use LAN cables if you can (CAT 7 LAN Cable)
Things like microwaves, WLAN-sensors / -cameras can interfere with your Wi-Fi network’s ability

Reboot your WLAN-Router and check the changed settings
Visit "https://on.quad9.net/" via a browser to check your actual DNS Server
Visit "https://dnsleaktest.com/" via a browser and run a "Standard Test" to check actual DNS Leaks

Topic: Time-settings 
------------------
Set and maintain the correct time-settings incl. timezone on all your smart-devices like pc's, router, switches, phones, tablets, watches, radios, etc. 
Use nearest timesserver from your location like "uk.pool.ntp.org", "de.pool.ntp.org" or "europe.pool.ntp.org" (https://www.ntppool.org/en/?lang=en-gb)

Topic: Network and TV-Cables 
------------------
Use proper cables for Networks, USB-C or USB 3.x, Monitor , Audio or TV/Console - https://thekabeldirekt.com/

Topic: Firewall (Hardware)
------------------
If you need extra protection buy a real Firewall with pfSense (https://pfsense.org/) and put it between your ISP router and your network. 
The Firewall/pfSense will become your new internet-router and will block intruders, trackers and Ad-Malware in your whole internal network 

Topic: Bluetooth 
------------------
Disable Bluetooth on all your devices if you don't need it

Topic: Internet Browser
------------------------------
Use the Brave-Browser, it's privacy focused (https://brave.com)
Install and make the Brave-Browser default on your pc
Install and make the Brave-Browser default on smartphone/tablet (iOS and Android Apps availiable)
Get started > On startup > Open the New Tab Page
Shields > Trackers & ads blocking > Shields > Agressive 
Shields > Upgrade connections to HTTPS >  Strict
Shields > Forget me when I close this site -> Checked -> Save
Shields > Block Fingerprinting -> Checked -> Save
Shields > Block Cookies-> Block third party cookies -> Checked -> Save
Shields > Content filtering -> Update list 
Shields > Content filtering -> Filter Lists -> EasyList -> All of it -> Save
Shields > Content filtering -> Filter Lists -> Fanboy -> All of it -> Save
Shields > Content filtering -> Filter Lists -> AdGuard -> All of it -> Save
Shields > Content filtering -> Filter Lists -> Youtube -> All of it -> Save
Shields > Content filtering -> Filter Lists -> Brave Twitch -> All of it -> Save
Shields > Social media blocking > Disable all > Save    
Privacy and security -> Clear browsing data -> Basic -> Time Range -> All Time -> Clear Data
Privacy and security -> Clear browsing data -> Basic -> Time Range -> Advanced-> All of it -> Clear Data
Privacy and security -> Clear browsing data -> On exit -> All of it -> Save
Privacy and security -> Tor windows -> Disable all
Privacy and security -> Data collection  -> Disable all
Brave Search Discussions -> Disable
Search Engine -> Normal Window -> Brave
Search Engine -> Private Window -> Brave
Settings -> Sync -> Manage your synced devices > Sync Settings > Add your devices
Settings -> Sync -> Manage your synced devices > Sync Settings > Sync everything
Settings -> Leo -> Show Leo icon in the sidebar > Disable
Settings -> Leo -> Tab Focus Mode > Disable
Settings -> Leo -> Store my conversation history > Disable
Settings -> Leo -> Delete all Leo AI conversation data -> ok
Settings -> Autofill and passwords -> Password Manager -> Settings -> Offer to save passwords and passkeys -> Disable
Settings -> Autofill and passwords -> Password Manager -> Settings -> Sign in automatically -> Disable
Settings -> Privacy and security -> Data collection -> Disable all
Settings -> Autofill and passwords -> Payment methods -> Disable all

Useful Extensions -> Proton Pass: Free Password Manager (if you're using ProtonPass) - https://proton.me/pass/download/chrome
Restart the Brave-Browser and check your changed settings

There is no complete in Brave at the moment and maybe new brave version will activate Leo again
Exit the Brave-Browser the proper way -> Exit, just closing it or shutting down your PC will not work  

Topic: Speedtest Internet
------------------------------
Choose Speedtest by Ookla (https://www.speedtest.net/)
Choose SpeedOfMe (https://speedof.me/)
Run both Speedtests sequentially and compare the results
Ping time should be under 50 milliseconds (ms)
Download-/Uploadrate should be over 80% of your payed internet connection
Otherwise update your router and windows pc to the latest level
Rerun both Speedtests
Contact your internet-Provider if the messurements are still bad

Topic: Internet Latency
------------------------------
If your router must handle several streams and other connections at the same time it may result in some serious latency-problems (office or family scenario). 
You can check that with the follwing link - https://www.waveform.com/tools/bufferbloat
BUFFERBLOAT GRADE A/B - Good 
BUFFERBLOAT GRADE not A/B - Not so good. Check / Enable the Quality of Service (QoS) and MAC Filtering on your WLAN-Router if possible. Contact your ISP

Topic: Data Breach
------------------------------
Check frequently (monthly) if your email address is in a data breach - https://haveibeenpwned.com

Topic: Virus-Defender
------------------------------
Windows Defender is good against viruses, malware and other nasty stuff. You don't need another security-scanner like Avira, McAfee, etc if you are a private user

Topic: VPN (Virtual Private Network)
------------------------------
Use a end-to-end encrypted and secure VPN service like ProtonVPN 24/7 on all your devices - https://proton.me
Edit the settings of your default VPN-Account
Settings -> Profiles -> Fastest
Settings -> Protocol -> Stealth
Settings -> NetShield -> Block malware, ads & trackers
Settings -> Always-on-VPN -> checked
Settings -> Kill-Switch -> checked
Settings -> Allow alternative routing -> checked
Settings -> VPN Accelerator -> checked
Settings -> Custom DNS -> unchecked

Apps for iOS and Android avaliable - https://apps.apple.com/de/developer/proton-ag/id979659484

Topic: Passwords
------------------------------
Use a end-to-end encrypted and secure Password generator service like ProtonPass - https://proton.me
iOS and Android Apps avaliable - https://apps.apple.com/us/app/proton-pass-password-manager/id6443490629

Visit https://www.passwortcheck.ch/en/ if you don't know how good your passwords are
Choose all available dictionaries
Copy and paste your password (exept the last digit) in the above field
If the "Entropy" value is under "100" change your password
Use different passwords for every account

Topic: 2FA-Authenticator 
------------------------------
Use a end-to-end encrypted and secure 2FA-Authenticator service like ProtonAuthenticator - https://proton.me
Settings -> Backup -> activate
Settings -> Sync between devices -> activate
Settings -> Biometric lock -> activate

Edit the settings of each account and safe the settings
Advanced options -> Digits -> 6
Advanced options -> Time interval -> 30 sec
Advanced options -> Algorithm -> SHA256
Advanced options -> Type -> TOTP

iOS and Android Apps avaliable - https://apps.apple.com/us/app/proton-authenticator/id6741758667

Topic: Passkey
------------------------------
If a Passkey (https://fidoalliance.org/passkeys/) is availiable on a site it would be smart to set-up Passkey, Password and 2FA-Authenticator for backup 

Topic: Yubi-Key (Hardware) 
------------------------------
A Yubi-Key is a geat soulution storing all your Passkeys or for multi-factor authentication (MFA) - https://www.yubico.com/
You neet at least two Yubi-Keys. One for daily use and one for backup, fequently sync nessesary 

Topic: E@Mail
------------------------------
Use a end-to-end encrypted and secure email service like ProtonMail - https://proton.me/mail
iOS and Android Apps avaliable - https://apps.apple.com/de/developer/proton-ag/id979659484

Topic: Calendar
------------------------------
Use a end-to-end encrypted and secure calendar service like ProtonCalendar - https://proton.me/calendar
iOS and Android Apps avaliable - https://apps.apple.com/de/developer/proton-ag/id979659484

Topic: Backup & Restore Data (Cloud)
------------------------------
Use a end-to-end encrypted and secure cloud service like ProtonDrive - https://proton.me/drive
iOS and Android Apps avaliable - https://apps.apple.com/de/developer/proton-ag/id979659484

Topic: Proton-Family 
------------------------------
Protect your whole family wth Proton-VPN, -Calendar, -E@Mail, -Drive -2FA-Authenticator - https://proton.me/family

Topic: AI / KI
------------------------------
Use a end-to-end encrypted and secure AI/KI service like Proton Lumo - https://lumo.proton.me/guest
Enable Ghost Mode in "Settings" so chat will be erased after using Proton Lumo
Enable WebSearch Mode unter the Chat-Windows (Looks like a globe)

Topic: Social Media
------------------------------
Try to avoid Social Media at all or use alternatives for Facebook, Twitter, TikTok and Whatsup if possible 
Mastodon – Twitter Alternative https://mastodon.social/explore
Pixelfed – Instagram Alternative https://pixelfed.org/
Loops - TikTok Alternative https://joinloops.org/
Signal – WhatsApp Alternative https://signal.org/
Threema – WhatsApp Alternative https://threema.com/en
Storygraph - GoodReads Alternative https://thestorygraph.com/
