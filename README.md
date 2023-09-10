# SOR Tech Stack
1. [🍎 macOS: Misc](#1-macos-misc)
2. [💻 macOS: Personal](#2--macos-personal)
    * 2.1 [🛜 Browsers](#21-browsers)
    * 2.2 [☁️ Storage](#22-storage)
    * 2.3 [🎙️ Social](#23-social)
    * 2.4 [🍿 Media](#24-media)
    * 2.5 [⌨️ Dev Tools](#25-dev-tools)
    * 2.6 [🛠️ Misc Tools](#26-misc-tools)
    * 2.7 [⚙️ Services](#27-services)
    * 2.8 [👔 Work](#28-work)
3. [🖥️ macOS: Server](#3--macos-server)
4. [🦊 Firefox Plugins](#4--firefox-plugins)
5. [🤖 Android](#5--android)
6. [🖥️ Synology NAS](#6--synology-nas)
7. [🥧 Raspberry Pi](#7--raspberry-pi)
8. [🎮 Nintendo Switch](#8--nintendo-switch)
9. [📲 iPadOS]((#9--ipados))

<br><br>

#  1. 🍎 macOS: Misc



## 1.1. Enable latest macOS updates, on depricated hardware:
- OpenCore Legacy Patcher 
    - [Github](https://github.com/dortania/OpenCore-Legacy-Patcher) 

<br>

## 1.2. Remove Screenshot Shadow
Run both commands in Terminal:
> defaults write com.apple.screencapture disable-shadow -bool true

> killall SystemUIServer

<br>

## 1.3. Enable Sidecar, on unsupported Mac models:
Run this in Terminal:
>defaults write com.apple.sidecar.display AllowAllDevices -bool true; defaults write com.apple.sidecar.display hasShownPref -bool true; open /System/Library/PreferencePanes/Sidecar.prefPane


## 1.4. Fix Slow macOS Wifi, by disabling AWDL ('Apple Wireless Direct Link', Airdrop etc)
Run this in Terminal:
>sudo ifconfig awdl0 down

<br><br><br>


# 2. 💻 macOS: Personal
## 2.1. 🛜 Browsers
| What?               	| What                         							 	| Link                        		|
|-----------------	|---------------------------------------------|-------------------------------|
|Brave Browser	 	| Privacy-focused Browser, with TOR support							| [Site](https://brave.com/download/)									|
|Firefox          	| Privacy-focused Browser								 			|[Site](https://www.mozilla.org/en-US/firefox/mac/)           	|
|Google Chrome		| Standard															| [Site](https://www.google.com/chrome/)	|

<br>

## 2.2. ☁️ Storage
| What?        | Why?                       | Link |
|--------------|----------------------------|------|
| Dropbox      | Screenshots Backup                |[Site](https://www.dropbox.com/desktop)      |
| Google Drive | Documents                  |[Site](https://www.google.com/drive/download/)      |
| OneDrive     | Larger File Storage, via M365 1TB Sub |[macOS App Store](https://apps.apple.com/us/app/onedrive/id823766827)      |

<br>

## 2.3. 🎙️ Social
| What?    | Why?            | Link                                                              |
|----------|-----------------|-------------------------------------------------------------------|
| Ferdium  | Chat aggregator |  [Github](https://github.com/ferdium/ferdium-app)                            |
| Signal  | Messaging |  [Site](https://www.signal.org/download/macos/)                            |
| WhatsApp | Messaging        | [macOS App Store](https://apps.apple.com/us/app/whatsapp-desktop/id1147396723) |

<br>

## 2.4. 🍿 Media
| What?           	| Why?                    	| Link                                                             	|
|-----------------	|-------------------------	|------------------------------------------------------------------	|
| Adobe Lightroom 	| Photo Editing           	| [macOS App Store](https://apps.apple.com/us/app/adobe-lightroom/id1451544217) 	|
| calibre         	| EBook Management        	| [Site](https://www.calibre-ebook.com/download_osx)                       	|
| Cemu            	| WiiU Emulator           	| [Github](https://github.com/cemu-project/Cemu)                             	|
| Dolphin         	| Gamecube / Wii Emulator 	| [Site](https://dolphin-emu.org/download/)                                	|
| GIMP            	| Image Editor            	| [Site](https://www.gimp.org/downloads/)                                  	|
| OpenEmu         	| Multi-console Emulator  	| [Site](http://openemu.org/)                                              	|
| Plex Client       | Plex Player Client      	| [Site](https://www.plex.tv/media-server-downloads/#plex-app)              	|
| RetroArch       	| Multi-console Emulator  	| [Site](https://www.retroarch.com/?page=platforms)       	|
| Spotify         	| Music                   	| [Site](https://www.spotify.com/us/download/)            	|
| VLC             	| Video Player            	| [Site](https://code.videolan.org/videolan/vlc/)         	|

<br>

## 2.5. ⌨️ Dev Tools
| What?                          | Why?             | Link                                                         |
|--------------------------|------------------|-------------------------------------------------------------|
| Android platform tools    | Android Dev CLI Suite      | [Site](https://developer.android.com/tools/releases/platform-tools) |
| Brew                      | CLI App Store      | [Site](https://brew.sh/)                                                             |
| Gas Mask                  | Host File Editor       | [Github](https://github.com/2ndalpha/gasmask)                         |
| iTerm                     | macOS Terminal enhancer        | [Site](https://iterm2.com/)   |
| Microsoft Remote Desktop  | RDP Client                  | [macOS App Store](https://apps.apple.com/us/app/microsoft-remote-desktop/id1295203466)                                                  |
| PixelFlasher              | App for flashing Pixel Phone updates, and retaining Magisk                 | [Github](https://github.com/badabing2005/PixelFlasher)   |
| Python                    |  Python runtime                 | [Site](https://www.python.org/downloads/)   |
| Visual Studio Code        | Code Editor                  | [Site](https://code.visualstudio.com/) |
| YT-DLP                    | CLI for ripping online videos                   |[Github](https://github.com/yt-dlp/yt-dlp)   |

<br>

## 2.6. 🛠️ Misc Tools
| What?                   | Why?                         | Link                                                       |
|-------------------------|------------------------------|------------------------------------------------------------|
| 1Password                 | Password Manager                             | [macOS App Store](https://apps.apple.com/us/app/1password-7-password-manager/id1333542190)                                                            |
| AppCleaner                | Uninstall Manager                             | [Site](https://freemacsoft.net/appcleaner/)                                                            |
| Authy Desktop             | 2FA Manager                             | [Site](https://authy.com/download/)                                                           |
| balenaEtcher              | Flash ISOs to USB                             | [Github](https://github.com/balena-io/etcher)                                                           |
| BetterDisplay           | Manage Screen resolutions, and override SideCar| [Github](https://github.com/AikoCute-Offical/BetterDisplay#readme)                                                           |
| ColorSlurp              | Pick the HEX code from anywhere on your screen                             |[macOS App Store](https://apps.apple.com/us/app/colorslurp/id1287239339)|
| Fing              | Network Scanner                             |[macOS App Store](https://apps.apple.com/us/app/fing-network-scanner/id430921107)|
| Gapplin              | SVG Manager                             |[macOS App Store](https://apps.apple.com/us/app/fing-network-scanner/id430921107)|
| Handbrake              | Video File Converter                             |[Github](https://github.com/HandBrake/HandBrake)|
| ImageOptim              | Bulk-converter for lossy images                             |[Site](https://imageoptim.com/mac)|
| LanScan              | Network scanner                             |[macOS App Store](https://apps.apple.com/us/app/lanscan/id472226235)|
| Microsoft To Do         | To-Dos                             | [macOS App Store](https://apps.apple.com/us/app/microsoft-to-do/id1274495053)                                                            |
| NordVPN                 | VPN with origin servers Globally                          | [macOS App Store](https://apps.apple.com/us/app/nordvpn-vpn-fast-secure/id905953485)                                                            |
| OnyX                    | macOS deep cleaning                             | [Site](https://titanium-software.fr/en/onyx.html)                  |
| Parallels Desktop       | Windows VM on macOS                             |[Fake Github](https://git.icrack.day/somebasj/ParallelsDesktopCrack)                                                            | 
| Skype                   | Cheap landline phone-calls |[Site](https://www.skype.com/en/get-skype/download-skype-for-desktop/)                                                          |
| TeamViewer              | Remote Desktop Viewer                             |[Site](https://www.teamviewer.com/en-us/download/macos/)                                                            |
| WireGuard               | VPN Client                   | [macOS App Store](https://itunes.apple.com/us/app/wireguard/id1451685025)     |

<br>

## 2.7. ⚙️ Services
| What?                   | Why?                         | Link                                                       |
|-------------------------|------------------------------|------------------------------------------------------------|
| Aerial             | Apple TV Screensavers, on macOS                          | [Github](https://aerialscreensaver.github.io/)                                                           |
| Amphetamine             | Prevent macOS from sleeping                             | [macOS App Store](https://apps.apple.com/us/app/amphetamine/id937984704)                                                           |
| Docker             | Virtualisation                             | [Site](https://docs.docker.com/desktop/install/mac-install/)    
| Flux                    | Removes Blue light, to help eyesight                     |[Site](https://justgetflux.com/news/pages/macquickstart/)                                                            |
| Irvue                   | Desktop Background Image Manager                             |[macOS App Store](https://apps.apple.com/us/app/irvue/id1039633667)                                                  |
| Java                  | JDK 11 runtime                             |[Site](https://www.oracle.com/java/technologies/downloads/#java11-mac)
| Keka                    | Archive (zip, rar) Manager                             |[Site](https://www.keka.io/)                                                            |
| MacMediaKeyForwarder    | Stops macOS play (⏯️) key from defaulting to Apple Music, and use Active Player (Spotify/Browser) instead                              | [Github](https://github.com/milgra/macmediakeyforwarder)             |
| Menu World Time         | App for showing timezones in Menu Bar                             | [macOS App Store](https://apps.apple.com/us/app/menu-world-time/id1446377255) |
| Muse Bar         | Touchbar controls for Spotify                             | [Github](https://github.com/planecore/MuseBar) |
| Muzzle         | Auto-DND when on calls                             | [Site](https://muzzleapp.com/) |
| Oh My Zsh         | Zsh Shell addons                          | [Github](https://github.com/ohmyzsh/ohmyzsh) |
| PiBar                   | Menu Bar for Pi Hole                             | [Github](https://github.com/amiantos/pibar)                          |
| Postman                   | API Validation + Testing                             | [Website](https://www.postman.com/downloads/)     
| Rectangle               | Window re-sizer                              | [Github](https://github.com/rxhanson/Rectangle/)                     |
| ToothFairy              | Bluetooth Headphones Manager |[Site](https://apps.apple.com/us/app/toothfairy/id1191449274)                                                            |
| YouType              | Locale Flags in Menu Bar |[Github](https://github.com/freefelt/YouType)                                                            |

<br>

## 2.8. 👔 Work 

| What?                                                                                                             | Why?     | Link                                                         |
|-------------------------------------------------------------------------------------------------------------------|----------|--------------------------------------------------------------|
| Evernote                                                                                                          | Word book         | [macOS App Store](https://apps.apple.com/us/app/evernote/id406056744)           |
| Figma                                                                                                             | Crayons  | [Site](https://www.figma.com/downloads/)                             |
| Microsoft Edge                                                                                                    | Work Browser | [Site](https://www.microsoft.com/en-us/edge/download)                |
| Microsoft Teams                                                                                                   | 🤮  | [Site](https://www.microsoft.com/en-us/microsoft-teams/download-app) |
| Office 365 <br>- Excel <br>- OneNote <br>- Outlook <br>- PowerPoint <br>- Word | Standard          | [Site](https://www.office.com/)                                     |
| zoom.us                                                                                                           | Video Calls | [Site](https://zoom.us/download)                                     |


<br><br><br>


# 3. 🖥️ macOS: Server
| What?                   | Why?                         | Link                                                       |
|-------------------------|------------------------------|------------------------------------------------------------|
| Radarr | Movies Scanner | [Github](https://github.com/Radarr/Radarr)
| Sonarr | TV Show Scanner | [Github](https://github.com/Sonarr/Sonarr)
| UTorrent | Torz  |
| FlareSolverr | Cloudflare Challenge Solver | [Gihub](https://github.com/FlareSolverr/FlareSolverr)


<br><br><br>


# 4. 🦊 Firefox Plugins
| What?                   | Why?                         | Link                                                       |
|-------------------------|------------------------------|------------------------------------------------------------|
|  Tab-Suspender | Suspend tabs to save RAM | [Github](https://github.com/dvalter/ff-thegreatsuspender)
|  AdBlock Pro


<br><br><br>


# 5. 🤖 Android
| What?                   | Why?                         | Link                                                       |
|-------------------------|------------------------------|------------------------------------------------------------|
| Magisk | Mods | [Github](https://github.com/topjohnwu/Magisk) | 
| Wireguard |VPN | [Play Store](https://play.google.com/store/apps/details?id=com.wireguard.android) | 
| Adaway | Adblocker | 
| Energised Blocker | Domain shitlist | 
| Microsoft Launcher | Best Android home Launcher | 


<br><br><br>


# 6. 🖥️ Synology NAS
| What?                   | Why?                         | Link                                                       |
|-------------------------|------------------------------|------------------------------------------------------------|
| Docker | Virtualization | 
| Plex Server | Media Steaming | 
| Docker: Whoogle | Stripped Google Search | [Github](https://github.com/benbusby/whoogle-search) <br><br> [Docker Image](https://registry.hub.docker.com/r/benbusby/whoogle-search#!)|
| Docket: Heimdall | Dashboard for Local Network Services | [Github](https://github.com/linuxserver/Heimdall) <br><br> [Docker Image](https://registry.hub.docker.com/r/linuxserver/heimdall)|
| Docker: Joplin | Note Taking + To-Do | [Github](https://github.com/laurent22/joplin) <br><br> [Docker Image](https://registry.hub.docker.com/r/joplin/server)|
| Docker: Portainer | Virtualised Image Management | [Github](https://github.com/portainer/portainer) <br><br> [Docker Image](https://registry.hub.docker.com/r/portainer/portainer-ce) |
| Docker: Minio | S3 Emulated Storage | [Github](https://github.com/minio/minio) <br><br> [Docker Image](https://hub.docker.com/r/minio/minio/#!)|
| Docker: Tautulli | Plex Monitoring + Stats | [Github](https://github.com/Tautulli/Tautulli) <br><br> [Docker Image](https://hub.docker.com/r/tautulli/tautulli) |
| Docker: Calibre Web | Calibre in a browser | [Github](https://github.com/janeczku/calibre-web) <br><br> [Docker Image](https://hub.docker.com/r/linuxserver/calibre-web)  |
| Docker: Kitana | Plex Pluin manager | [Github](https://github.com/pannal/Kitana) <br><br> [Docker Image](https://hub.docker.com/r/pannal/kitana) |
| Docker: Photoprism | Photo Manager | [Github]() <br><br> [Docker Image](https://hub.docker.com/r/photoprism/photoprism) |


<br><br><br>


# 7. 🥧 Raspberry Pi
| What?                   | Why?                         | Link                                                       |
|-------------------------|------------------------------|------------------------------------------------------------|
| Log2RAM | Writes log data to RAM vs SD Card, so your SD card lasts longer  | [Github](https://github.com/azlux/log2ram) | 
| PiHole | DNS Shitlist sinkhole / Adblocker | [Github](https://github.com/pi-hole/pi-hole) | 
| PiVPN | VPN Server | [Github](https://github.com/pivpn/pivpn) | 
| Raspotify | Spotify cast on old Speakers | [Github](https://github.com/dtcooper/raspotify) | 


<br><br><br>


# 8. 🎮 Nintendo Switch
| What?                   | Why?                         | Link                                                       |
|-------------------------|------------------------------|------------------------------------------------------------|
| Browser Boot Payload Injector | Works on Chrome only | [Site](https://webcfw.sdsetup.com/) | 
| NS-Loader | NSP Loader | [Github](https://github.com/developersu/ns-usbloader) | 
| ⚓️⚓️ DeepSea: Advanced ⚓️⚓️ | Package with all the things | [Github](https://github.com/Team-Neptune/DeepSea) | 
| ⚓️ AIO-switch-updater | All-in-one Updater | ^
| ⚓️ Atmosphère | CFW | ^ |
| ⚓️ DeepSea Assets | Pack Tools | ^ |
| ⚓️ DeepSea Cleaner | Pack Tools | ^ |
| ⚓️ DeepSea CPR | Pack Tools | ^ |
| ⚓️ DeepSea Toolbox | Pack Tools | ^ |
| ⚓️ EdiZon-SE | Save Manager | ^ |
| ⚓️ EdiZon-Overlay | Save Manager | ^ |
| ⚓️ Emuiibo | Virtual amiibo  | ^ |
| ⚓️ Hekate | NX Bootloader | ^ |
| ⚓️ Homebrew App Store | App Store | ^ |
| ⚓️ JKSV | Save Manager | ^ |
| ⚓️ ldn_mitm | LAN Injector | ^ |
| ⚓️ MissionControl | 3rd Party Controllers - Bluetooth | ^ |
| ⚓️ nx-ovlloader | Tesla Overlay Helper | ^ |
| ⚓️ NX-Shell | File Manager | ^ |
| ⚓️ ovlSysmodules | Tesla Overlay Helper | ^ |
| ⚓️ Status Monitor Overlay | Tesla Overlay | ^ |
| ⚓️ sys-clk | Tesla Clock Overrides | ^ |
| ⚓️ sys-con | 3rd Party Controllers | ^ |
| ⚓️ sys-ftpd-light | Background FTP | ^ |
| ⚓️ TegraExplorer | File Managers | ^ |
| ⚓️ Tesla-Menu | Overlays | ^ |
| ⚓️ TinWoo | Game Installer | ^ |
| Awoo-Installer | Loader | [Github](https://github.com/Huntereb/Awoo-Installer) |
| breeze | Game Cheating Tool | [Github](https://github.com/tomvita/Breeze-Beta) |
| Checkpoint | Save Manager | [Github](https://github.com/BernardoGiordano/Checkpoint) |
| FTPD4SXOS | FTP Server| |
| Goldleaf | Loader | [Github](https://github.com/XorTroll/Goldleaf) |
| Lockpick | Key file Support App | [Github](https://github.com/SpaceNX/Lockpick_RCM)|
| MelonDS  | NDS Emulator | [Github](https://github.com/melonDS-emu/melonDS) |
| NX-Activity-Log | Gameplay Data + Stats | [Github](https://github.com/tallbl0nde/NX-Activity-Log) |
| OpenLara | FOSS Tomb Raider 1 | [Github](https://github.com/XProger/OpenLara)|
| RetroArch | Emulators | [Site](https://www.retroarch.com/?page=platforms) |
| SimpleModManager | Mods | [Github](https://github.com/nadrino/SimpleModManager) |
| SysDVR | Streamer | [Github](https://github.com/exelix11/SysDVR) |
| Tinfoil | Shop Browser | [Site](https://tinfoil.io/Download) |



<br><br><br>


# 9. 📲 iPadOS
| What?                   | Why?                         | Link                                                       |
|-------------------------|------------------------------|------------------------------------------------------------|
| Wireguard  | B  | C
| VLC | |