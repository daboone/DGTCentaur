CHANGELOG

A developer friendly with pull request numbers mentioned.

2022 January 
* New structure in build folder elimination of service files.
* Bluetooth fixes 

2021 December
* Bluetooth postinstall fixes.
* **Feature** Autoinstaller to automatically build the boot image using Powershell script.
* Powershell script autoinstaller code tidy
* **Feature** Autoinstaller - extraction of centaur.tar from original SD card 
* Fixing automatic updating and upgrade on first boot and make it active
* **Feature** Autoinstaller - Standalone utilities 7Zip, Win32DiskImager,Raspberry Pi Imager. It works standalone.
* Fix libsqllite-dev dependency enabling Stockfish builds on new image of Rasbian 
* **Feature** Backup of original stockfish engine from centaur 
* **Feature** New Chess engines maia, zahak and rodentiv in the install process
* **Feature** RodentIV configuration on web page http://<PiZeroIPAddress>:5000/rodentivtuner
* **Feature**  Alter build process to speed up Stockfish 

2021 November
* Adding auto build of stockfish and installing to right place #87 
* **Feature**  Feature adding all three engiens maia, zahak,rodentiv in the install proess, engine default files.  Personality feature dealt with for Rodent IV #83
* Build process always grabs latest source that's available git checkout. #75 
* Build process asks about Stockfish integration #75

2021 October

* Code tidy to facilitate group module handling #71
* **Feature**  Discord widget on the web interface  #70 
* Automating bluetooth settings  #69 
* Adding git as a dependency for dgtcentaurmods #69
* Enabling bluetoothd daemon and rfcomm.service #69
* **Feature**  Bluetooth: Turning on, making discoverable and pairable using bluetoothctl #69
* **Feature**  Fixing hostname dgtcentaur  in hosts and hostname  #69
* **Feature**  Adding Bluetooth machine name /etc/macine-info PCS-REVI-081500 #68
* Post install hook fix #68
* SPI bus fix to turn on spi and overlay spi1-3cstuirn on uart #67
* Refactor disabling console on ttyS0 #67
* Adding empty bluetoth pin to config /etc/bluetooth/pin.conf #67
* Visual tidy of post install sript #67
* Adding python3-pip dependency #66
* Adding manipulation of boot command line #66
* Disable console on ttyS0 #66 
* Build automation #65
* First version of build.sh, postinstall to add lichess key as part of build setup services and enable ntp, DGTCenaturMods, centaur service, centaurmods web service. First package dependencies ntp, ssmpt    
* Major naming refactor of module names #64
* **Feature**  Display Lichess menu item based on centaur.ini file  #63
* **Feature**  Disable centaur software menu option if not present #60
* SQLLite base structure #57
* New Python dependendies casttube,click,,ifaddr,importlib-metadata,itsdangerous,Jinja2,MarkupSafe,protobuf,PyChromecst Achemy,typing-extensions,Werkzeug,zeroconf,zipp #57 
* Typo errors in dependencies Flask, PyChromecast fixed  #57
* **Feature**  Better implementation of poweroff as part of board functions removal of epaper.jpg #55
* **Feature**  WPS Connect #53
* Enable WPS connect and Recover wifi menu option. Backup of wifi configuration script. #52
* Settings menu #50 
* **Feature**  Adding Help button support  #48 
* Activating  WPS connect logic #48
* **Feature**  Adding QR code for Support for button help #48
* Using fen.log to drive web view of board #43
* Reduce epaper display refresh to match the page refresh on web view  #43
* First Service files for systemd DGTCentaurMods, centaur #42
* Start service files through systemd and start and enable them reload of systemd #41
* **Feature**  Logo preservation on turn off of display #41 
* Extend wifi menu beginnings with wps,wpa2 support. Adding support menu option #39
* WPS library Functions added (network.py) #36 
* **Feature**  Major feature adding Flask for web interface for basic web app and live board view on browser #34 
* Adding new python libs certifi,charset-normalizer,Deprecated,idna,ndjsonpython-dotenv,requests,urllib3,wrapt 
* Code tidy package names #30 
* Consistent packages across all devices, relative pathnaming. Deploy python environment script. #27
* Refactor of project structure adding rc.local to start #21
* Pretty print the board state for debugging #17
* Adjusting LED intensity of board consistent with DGT original behaviour #15 menu option todo 
* README.md info #11
* Shutdown sequence fixing to turn off the board controller too as well as sound . #7
* A bit of code tidy refactoring some logic to functions #6
* Checksum function for modifying board led behaviour #5










    





