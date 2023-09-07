# Tech Tools
Random list of things I use across:
1. macOS: Misc
2. macOS: Personal
3. macOS: Server
4. Firefox Plugins
5. Android
6. Switch
7. Synology NAS
8.  Raspberry Pi
9. iPadOS

# 1. macOS: Misc
### 1. Enable latest OS updates, on unsupported Mac models:
- OpenCore Legacy Patcher 
- [Github](https://github.com/dortania/OpenCore-Legacy-Patcher) 

### 2. Remove Screenshot Shadow
Run this in Terminal:
> defaults write com.apple.screencapture disable-shadow -bool true
> killall SystemUIServer

### 3. Enable Sidecar, on unsupported Mac models:
Run this in Terminal:
>defaults write com.apple.sidecar.display AllowAllDevices -bool true; defaults write com.apple.sidecar.display hasShownPref -bool true; open /System/Library/PreferencePanes/Sidecar.prefPane


# 2. macOS: Personal
## 2.1 BROWSERS
| What?               	| What                         							 	| Link                        		|
|-----------------|---------------------------------------------|-------------------------------|
|Brave Browser	 	| Privacy-focused Browser, with TOR support		| Official Site									|
|Firefox          | Privacy-Focused Browser								 			|"Isn't this fun?"            	|
|Google Chrome		| Standard																		|	-- is en-dash, --- is em-dash	|

-  Tab-Suspender: https://github.com/dvalter/ff-thegreatsuspender
-  AdBlock Pro


## 2.2 DEV TOOLS
| What?                          | Why?             | Link                                                         |
|--------------------------|------------------|-------------------------------------------------------------|
| Android-platform-tools   | Tools for Android Dev Connectivity                 | [Official Site](https://developer.android.com/tools/releases/platform-tools) |
| Brew                     | CLI App Store                 | [Official Site](https://brew.sh/)                                                             |
| Gas Mask                 | Host File Editor | [Github](https://github.com/2ndalpha/gasmask)                         |
| iTerm                    | macOS terminal enhancer                  | [Official Site](https://iterm2.com/)                                                            |
| Microsoft Remote Desktop | RDP Client                  | [macOS App Store](https://apps.apple.com/us/app/microsoft-remote-desktop/id1295203466)                                                  |
| PixelFlasher             | App for flashing Pixel Phones, and retaining Magisk                 | [Github](https://github.com/badabing2005/PixelFlasher)                |
| Python 3.11              |  Python runtime                 | [Official Site](https://www.python.org/downloads/)                                                            |
| Visual Studio Code       | Code Editor                  | [Official Site](https://code.visualstudio.com/)                                                            |
| YT-DLP                   | CLI for ripping Online Vids                   |[Github](https://github.com/yt-dlp/yt-dlp)                            |

    
## 2.3 STORAGE
| What?        | Why?                       | Link |
|--------------|----------------------------|------|
| Dropbox      | Screenshots Backup                |[Official Site](https://www.dropbox.com/desktop)      |
| Google Drive | Documents Repoo                  |[Official Site](https://www.google.com/drive/download/)      |
| OneDrive     | Large Storage via M365 Sub |[macOS App Store](https://apps.apple.com/us/app/onedrive/id823766827)      |


## 2.4 SOCIAL
| What?    | Why?            | Link                                                              |
|----------|-----------------|-------------------------------------------------------------------|
| Ferdium  | Chat aggregator |  [Github](https://github.com/ferdium/ferdium-app)                            |
| WhatsApp | Baseline        | [macOS App Store](https://apps.apple.com/us/app/whatsapp-desktop/id1147396723) |




## 2.5 WORK 

| What?                                                                                                             | Why?     | Link                                                         |
|-------------------------------------------------------------------------------------------------------------------|----------|--------------------------------------------------------------|
| Evernote                                                                                                          | Scrapbook         | [macOS App Store](https://apps.apple.com/us/app/evernote/id406056744)           |
| Figma                                                                                                             | Crayons  | [Official Site](https://www.figma.com/downloads/)                             |
| Microsoft Edge                                                                                                    | Work Browser | [Official Site](https://www.microsoft.com/en-us/edge/download)                |
| Microsoft Teams                                                                                                   | 🤮  | [Official Site](https://www.microsoft.com/en-us/microsoft-teams/download-app) |
| Office 365 <br>-- Excel <br>-- OneNote <br>-- Outlook <br>-- PowerPoint <br>-- Word | Standard          | [Official Site](https://www.office.com/)                                     |
| zoom.us                                                                                                           | Calls | [Official Site](https://zoom.us/download)                                     |


## 2.6 UTILITIES:
| What?                   | Why?                         | Link                                                       |
|-------------------------|------------------------------|------------------------------------------------------------|
| 1Password               | Password Manager                             | [macOS App Store](https://apps.apple.com/us/app/1password-7-password-manager/id1333542190?mt=12)                                                            |
| Aerial             | Apple TV Screensavers, on macOS                          | [Github](https://aerialscreensaver.github.io/)                                                           |
| Amphetamine             | Stop macOS from sleeping                             | [macOS App Store](https://apps.apple.com/us/app/amphetamine/id937984704)                                                           |
| AppCleaner              | Uninstall Manager                             | [Official Site](https://freemacsoft.net/appcleaner/)                                                            |
| Authy Desktop           | 2FA Manager                             | [Official Site](https://authy.com/download/)                                                           |
| ColorSlurp              | Pick the HEX code from anywhere on your screen                             |[macOS App Store](https://apps.apple.com/us/app/colorslurp/id1287239339)|
| Flux                    | Removes Blue light from macOS                     |[Official Site](https://justgetflux.com/news/pages/macquickstart/)                                                            |
| Irvue                   | Desktop Background Image Manager                             |[macOS App Store](https://apps.apple.com/us/app/irvue/id1039633667?mt=12)                                                  |
| Keka                    | Archive Manager                             |[Official Site](https://www.keka.io/)                                                            |
| MacMediaKeyForwarder    | Stops macOS play (⏯️) key from defaulting to Apple Music, and use Active Player (Spotify/Browser) instead                              | [Github](https://github.com/milgra/macmediakeyforwarder)             |
| Menu World Time         | App for showing timezones in Menu Bar                             | [macOS App Store](https://apps.apple.com/us/app/menu-world-time/id1446377255) |
| Microsoft To Do         | To-Dos                             | [macOS App Store](https://apps.apple.com/us/app/microsoft-to-do/id1274495053?mt=12)                                                            |
| NordVPN                 | VPN with origin servers Globally                          | [macOS App Store](https://apps.apple.com/us/app/nordvpn-vpn-fast-secure/id905953485)                                                            |
| OnyX                    | macOS deep cleaning                             | [Official Site](https://titanium-software.fr/en/onyx.html)                  |
| Parallels Desktop       | Windows VM on macOS                             |[Fake Github](https://git.icrack.day/somebasj/ParallelsDesktopCrack)                                                            | 
| PiBar                   | Menu Bar for Pi Hole                             | [Github](https://github.com/amiantos/pibar)                          |
| Rectangle               | Window re-sizer                              | [Github](https://github.com/rxhanson/Rectangle/)                     |
| Skype                   | Cheap landline phone-calls |[Official Site](https://www.skype.com/en/get-skype/download-skype-for-desktop/)                                                          |
| TeamViewer              | Remote Desktop Viewer                             |[Official Site](https://www.teamviewer.com/en-us/download/macos/)                                                            |
| ToothFairy              | Bluetooth Headphones Manager |[Official Site](https://apps.apple.com/us/app/toothfairy/id1191449274)                                                            |
| WireGuard               | VPN Client                   | [macOS App Store](https://itunes.apple.com/us/app/wireguard/id1451685025)     |

## 2.7 MEDIA:
| What?           	| Why?                    	| Link                                                             	|
|-----------------	|-------------------------	|------------------------------------------------------------------	|
| Adobe Lightroom 	| Photo Editing           	| [macOS App Store]https://apps.apple.com/us/app/adobe-lightroom/id1451544217 	|
| calibre         	| EBook Management        	| [Official Site](https://www.calibre-ebook.com/download_osx)                       	|
| Cemu            	| WiiU Emulator           	| [Github](https://github.com/cemu-project/Cemu)                             	|
| Dolphin         	| Gamecube / Wii Emulator 	| [Official Site](https://dolphin-emu.org/download/)                                	|
| GIMP            	| Image Editor            	| [Official Site](https://www.gimp.org/downloads/)                                  	|
| OpenEmu         	| Multi-console Emulator  	|[Official Site](http://openemu.org/)                                              	|
| Plex            	| Plex Player Client      	| [Official Site](https://www.plex.tv/media-server-downloads/#plex-app)              	|
| RetroArch       	| Multi-console Emulator  	| [Official Site](https://www.retroarch.com/?page=platforms)       	|
| Spotify         	| Music                   	| [Official Site](https://www.spotify.com/us/download/)            	|
| VLC             	| Video Player            	| [Official Site](https://code.videolan.org/videolan/vlc/)         	|



# 3. macOS: Server
- RADARR
- SONARR
- UTorrent
- 


# 4. Firefox Plugins
- Plugins

# 5. Android
- Magisk | [Github](https://github.com/topjohnwu/Magisk)
- Wireguard | https://play.google.com/store/apps/details?id=com.wireguard.android
- Adaway
- Energised Blocker
- Microsoft Launcher

# 6. Nintendo Switch
- DeepSea | [Github](https://github.com/Team-Neptune/DeepSea)
- RetroArch | [Official Site](https://www.retroarch.com/?page=platforms)


# 7. Synology NAS
- Docker |
- Plex Server | 


# 8. Raspberry Pi
- Log2RAM | [Github](https://github.com/azlux/log2ram)
- PiHole | [Github](https://github.com/pi-hole/pi-hole)
- PiVPN | [Github](https://github.com/pivpn/pivpn)
- Raspotify | [Github](https://github.com/dtcooper/raspotify)



# 9. iPadOS
- 
