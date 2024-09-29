# InternetSecurity

Topic: DNS Settings
------------------------------
Change the DNS settings on your internet-router to NextDNS/Quad9, it's privacy focused (https://www.quad9.net/)
Find the IP-adress on the back at your router (https://fritz.box or https://192.168.0.1)
Find the Name of the Admin-User on the back of your router
Find the Password on the back of your router
Webbrowser -> Router-Adress -> DNS -> Primary DNS 9.9.9.9 (Quad9)
Webbrowser -> Router-Adress -> DNS -> Secondary DNS 149.112.112.112 (Quad9)

Reboot your router and check the DNS settings
Visit "https://on.quad9.net/" via a browser to check your actual DNS Server
Visit "https://dnsleaktest.com/" via a browser and run a "Standard Test" to check your actual DNS Server

Topic: Internet Browser
------------------------------
Use the Brave-Browser, it's privacy focused (https://brave.com)
Install and make the Brave-Browser default on your pc
Install and make the Brave-Browser default on smartphone/tablet (iOS and Android Apps availiable)
Shields > Trackers & ads blocking > Shields > Agressive 
Shields > Upgrade connections to HTTPS >  Strict
Shields > Forget me when I close this site -> Checked -> Save
Shields > Content filtering -> Update list (frequently)
Shields > Content filtering -> Filter Lists -> EasyList -> All of it -> Save
Shields > Content filtering -> Filter Lists -> Fanboy -> All of it -> Save
Shields > Content filtering -> Filter Lists -> Youtube -> All of it -> Save
Privacy and security -> Clear browsing data -> Basic -> Time Range -> All Time -> Clear Data
Privacy and security -> Clear browsing data -> Basic -> Time Range -> Advanced-> All of it -> Clear Data
Privacy and security -> Clear browsing data -> On exit -> All of it -> Save
Privacy and security -> Data collection  -> Disable all
Search Engine -> Normal Window -> Brave
Search Engine -> Private Window -> Brave
Useful Extensions -> Dark Reader and Proton Pass: Free Password Manager (if you're using ProtonPass)

Restart the Brave-Browser and check your changed settings

Topic: Speedtest Internet
------------------------------
Choose Speedtest by Ookla (https://www.speedtest.net/)
Run the the Speedtest
Choose SpeedOfMe (https://speedof.me/)
Run the the Speedtest
Compare both results
Ping time should be under 50 milliseconds (ms)
Download-/Uploadrate should be over 80% of your payed internet connection
Otherwise update your router and windows pc to the latest level
Rerun both Speedtests
Contact your internet-Provider if the messurements are still bad

Topic: Internet Latency
------------------------------
If your router must handle several streams and other connections at the same time it can result in some serious latency-problems. 
You can check that with the follwing link: 

Test-Site https://www.waveform.com/tools/bufferbloat

Less than 5 ms latency increase - A+
Less than 30 ms latency increase - A
Less than 60 ms latency increase - B
Less than 200 ms latency increase - C
Less than 400 ms latency increase - D
400 ms or greater latency increase - F

The easiest and quickest way for most people to fix bufferbloat is to upgrade their WiFi router. A small number of modern, high-end routers 
come with a feature called "Smart Queue Management" – also known as SQM. 

Topic: Passwords
------------------------------
If you don't know how good your passwords are
Visit https://www.passwortcheck.ch/en/
Choose all dictionaries
Paste your password (exept the last digit) in the above field
If the "Entropy" value is under "100" change your password
Long passwords are not good passwords, complexity is key.
Try "Password0123456789" in the above field and check the "Entropy" value
Use a password manager like v (https://proton.me/pass)
Use the password manager as a password generator (20 characters with special characters)
Use different passwords for every account
Use two-factor authentication (2FA) if avaliable (https://authy.com/)
Use a Yubi-Key with FIPS/NFC (https://www.yubico.com/gb/product/yubikey-5-nfc/)
Buy another Yubi-Key with NFC in case of loosing the first one
Slot 1 - Password generated for your Windows Account from ProtonPass
Slot 2 - Password generated for your Internetrouter Account from ProtonPass
Clone the frist Yubi-Key to the second Yubi-Key
Store the second Yubi-Key in a safe place

Topic: VPN (Virtual Private Network)
------------------------------
Get Proton for 9,99 / month (https://protonvpn.com/pricing?ref=home)
Install and run the ProtonVPN Client on your PC
Go to your downloads folder and double click the protonvpn.exe installation file
If a new window pops up asking “Do you want to allow this app to make changes to your device?”
Click ‘Yes’
If installing for the first time, the OpenVPN TAP adapter installation will appear.
In the window, click ‘Next
During the installation process, installation of Windows .NET might be required as well.
If prompted, follow the instructions to install Windows .NET as well.
Click I Agree and then Next
Finally click Install
Once the installer window is open, click install on the first screen.
The installer will proceed with the process automatically
Once installed, the Proton VPN application will start, and appear in a new window.
A shortcut to the application will also appear on your desktop for the ease of access.

Topic: Virus-Defender
------------------------------
Windows Defender is good. You don't need another virus-scanner like Avira, McAfee, etc

Topic: Backup & Restore Data
------------------------------
Buy a good USB Drive like a WD_BLACK P10 
Copy your data frequently to the USB-Drive
Store the USB Drive in a safe place
Use a end-to-end encrypted and secure cloud service like ProtonDrive (https://proton.me/drive)

Topic: Mail
------------------------------
Use a end-to-end encrypted and secure email service like ProtonMail (https://proton.me/mail
iOS and Android Apps for ProtonMail avaliable

Topic: Calendar
------------------------------
Use a end-to-end encrypted and secure calendar service like ProtonCalendar (https://proton.me/calendar)
iOS and Android Apps for ProtonCalendar avaliable

Topic : SSH-Keys (Linux-Users)
------------------------------
Generate valid ssh-keys with or without a yubikey and distribute the generated keys with #ssh-copy-id to your target-servers
# ssh-keygen -a 31415 -t ed25519 -f /$HOME/.ssh/id_ed25519 -q -N "" (without a yubikey)
# ssh-keygen -a 31415 -t ed25519-sk -O resident -O verify-required -f /$HOME/.ssh/id_ed25519-sk -q -N "" (with a yubikey, generates also a pin)

# ssh-keygen -a 31415 -t edcdsa -b 256 -f /$HOME/.ssh/id_edcdsa -q -N "" (without a yubikey)
# ssh-keygen -a 31415 -t edcdsa-sk -b 256 -O resident -O verify-required -f /$HOME/.ssh/id_edcdsa-sk -q -N "" (with a yubikey, generates also a pin)

Topic : Disable direct root-access (Linux-Users)
------------------------------
Activate the "#PermitRootLogin no" to "PermitRootLogin no" in the /etc/ssh/sshd_config
Restart the sshd via systemctl or reboot the system

Topic : Generate valid Passwords with OpenSSL (Linux-Users)
------------------------------
# openssl rand -base64 20
