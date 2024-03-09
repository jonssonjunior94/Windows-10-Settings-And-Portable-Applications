
&nbsp;

&nbsp;

### Windows Settings

  - [Performance Options](#performance-options) - Remove Animations.
  - [Power Options](#power-options) - Lets your PC use more energy. (Balanced is better)
  - [Mouse Properties](#mouse-properties) - Remove the feature that calculates the velocity of the mouse and adjusts the DPI.
  - [Disable Fast Startup](#disable-fast-startup) 


   ##### Registry Hacks
  - [Taskbar Clock](#taskbar-clock) - Show Seconds.
  - [Context Menu](#context-menu) - Add Any Application to the Windows Desktop Right-Click Menu.
  - [Require UAC Password](#require-uac-password) - Promt password for every approval. Even as Administrator. Further steps to stop malicious programs or malware to find ways to obtain admin privileges.

&nbsp;

&nbsp;

### Portable Applications


- [7-Zip](https://www.7-zip.org/download.html) - File archiver with a high compression ratio and built-in encryption functionality.
- [ShareX](https://github.com/ShareX/ShareX/releases) - Lets you take screenshots of any selected area with a single key.
- [Discord portable](https://github.com/portapps/discord-portable) - Portable instead of the regular auto install.
- [Open Hardware Monitor](https://openhardwaremonitor.org/downloads/) - Free open source software that monitors temperatures, fans, voltages, load and clock.
- [Geek Uninstaller](https://geekuninstaller.com/) - Geek Uninstaller is a perfectly functional uninstaller. Also removes attached registry keys.
- [Notepad++](https://notepad-plus-plus.org/downloads/) - Notepad++ is a great replacement for Windows notepad. It's a good choice for beginners.
- [VLC](https://www.videolan.org/vlc/download-windows.html) - VLC is a free and open source cross-platform multimedia player and framework that plays most multimedia files.


##### Extras (Still Portable)
- [Scrcpy](https://github.com/Genymobile/scrcpy) - This application provides display and control of Android devices connected via USB.
- [yt-dlp](https://github.com/yt-dlp/yt-dlp) - A youtube-dl fork with additional features and fixes. Works great with [yt-dl-gui](https://github.com/oleksis/youtube-dl-gui).
  Also [FFmpeg.](https://github.com/BtbN/FFmpeg-Builds/releases) copy the bin folder content to the folder that yt-dlp.exe is located at `(ffprobe, ffplay and ffmpeg)`. Settings to download with h264 or h265 codec `$ yt-dlp -f "(bv*[vcodec~='^((he|a)vc|h26[45])']+ba) / (bv*+ba/b)"` And Filename Format `%(autonumber)02d. %(title)s` Works like a charm with Plex.
- [Twitch GUI](https://github.com/streamlink/streamlink-twitch-gui) - A multi platform Twitch.tv browser for [Streamlink](https://github.com/streamlink/streamlink). Works great with [VLC](https://www.videolan.org/vlc/download-windows.html).
- [Everything](https://www.voidtools.com/) - Locate files and folders by name instantly. Plus [Everything Toolbar](https://github.com/stnkl/EverythingToolbar) for the taskbar.
- [SuperSlicer](https://github.com/supermerill/SuperSlicer) - Developed to provide users more control over their slicer than what was possible with PrusaSlicer.
- [NVIDIA Profile Inspector](https://github.com/Orbmu2k/nvidiaProfileInspector) - Open source third-party tool created for pulling up and editing application profiles within Nvidia display drivers.

&nbsp;

&nbsp;

##### Emulators and ROMs
- [Yuzu](https://github.com/yuzu-emu/yuzu-mainline) (Switch) To make Yuzu portable create a folder named "user" inside the installation directory.
  RIP 04-03-2024.
- [Dolphin](https://dolphin-emu.org/download/) (GameCube/Wii) To make Dolphin emulator portable create a .txt file named "portable" inside the installation directory.
- [Cemu](https://wiki.cemu.info/wiki/Release_1.26.2f) (Wii U) Cemu is already portable.

&nbsp;

#### USB Operating Systems

- [Rufus](https://rufus.ie/downloads/) Rufus is a utility that helps format and create bootable USB flash drives.
- [Ventoy](https://github.com/ventoy/Ventoy/releases) Ventoy is an open source tool to create bootable USB drive for ISO/WIM/IMG/VHD(x)/EFI files.
- [Tails](https://tails.net/install/) Is a portable operating system that protects against surveillance and censorship.

&nbsp;

##### DNS Blocklists
- [Crazy Max's WindowsSpyBlocker - Hosts spy rules](https://raw.githubusercontent.com/crazy-max/WindowsSpyBlocker/master/data/hosts/spy.txt)
- [HaGeZi's Blocklist - Big Broom](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/pro.txt)
- [HaGeZi's DoH/VPN/TOR/Proxy Bypass - Prevent methods to bypass your DNS](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/doh-vpn-proxy-bypass.txt)
- [HaGeZi's Threat Intelligence Feeds](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/tif.txt)
- [HaGeZi's Windows/Office Tracker DNS Blocklist](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/domains/native.winoffice.txt)
- [hBlock - Adblock](https://hblock.molinero.dev/hosts_adblock.txt)
- [OISD BIG - Blocklist](https://big.oisd.nl/)
- [Someone Who Cares](https://someonewhocares.org/hosts/zero/hosts)

&nbsp;

&nbsp;

&nbsp;

### Browsers

#### Firefox

- [Mozilla FTP](https://ftp.mozilla.org/pub/firefox/releases/) 
- [Firefox Profilemaker](https://ffprofile.com/) Tool to create a Firefox profile with the defaults you like.
- Extras: [Compact Mode](https://support.mozilla.org/en-US/kb/compact-mode-workaround-firefox)
- Addons: [uBlock Origin](https://addons.mozilla.org/de/firefox/addon/ublock-origin/) [Imagus](https://addons.mozilla.org/en-US/firefox/addon/imagus/) [SponsorBlock](https://addons.mozilla.org/en-US/firefox/addon/sponsorblock/) [ClearURLs](https://addons.mozilla.org/en-US/firefox/addon/clearurls/) [User-Agent Switcher](https://addons.mozilla.org/en-US/firefox/addon/uaswitcher/) 

#### Chrome

- [Ungoogled-Chromium](https://github.com/ungoogled-software/ungoogled-chromium-windows/releases)
Disable "Clear Cookies" to save settings and login information at visited sites. `chrome://settings/cookies`
- [Extensions](https://github.com/jonssonjunior94/Windows-10-Settings/releases/tag/Extensions) Personal backup of extensions. 
- [Chrome Bookmarks Recovery Tool](https://rongjiecomputer.github.io/chrome/bookmark-recovery/#windows) Best way i have found to back up bookmarks from Google Chrome as a .html file to easily use with Ungoogled Chromium.

&nbsp;

&nbsp;

#### Useful Websites
- [Send](https://github.com/timvisee/send-instances/#instances) - Share encrypted files with ease.
- [Gmailnator](https://www.emailnator.com/) - Temporary Disposable Gmail. (Use Adblock)
- [Redirect Detective](https://redirectdetective.com/) - URL redirection checker, see the complete path a redirected URL goes through.
- [Have i been pwned](https://haveibeenpwned.com/) - Check if your email or phone is in a data breach. Only publicly discovered breaches.
- [IsThereAnyDeal](https://isthereanydeal.com/?currency=USD) - A useful little web tool that tracks PC game prices across a variety of sources, including Steam.
- [VirusTotal](https://www.virustotal.com/gui/home/upload) - Free service that analyzes files and URLs for viruses. It's not advisable to upload sensitive files.
- [NMHDDS](https://doyou.needmorehdd.space/?fileType=&query=chrome#) NMHDDS Google Open Directory Search Tool. Get direct download links to (almost) anything.
  
&nbsp;

- [Test Ad Block](https://d3ward.github.io/toolz/adblock.html) This tool allows you to check if your adblock solution is blocking enough hosts.
- [dnscheck.tools](https://dnscheck.tools/) Identifies your DNS resolvers, checks DNSSEC validation, and more.
- [ipaddr.tools](https://myip.addr.tools/help) get your public IP address.
- [RDAP data](https://info.addr.tools/me) Displays relevant DNS records and RDAP registration data.

&nbsp;

&nbsp;

&nbsp;

___


&nbsp;

&nbsp;

### Performance Options

Press the Windows + R keys to open the Run dialog box.

Type `systempropertiesperformance` and then press Enter.

Copy these settings:

![image](https://user-images.githubusercontent.com/25332460/188121561-56314c8e-6644-4251-97d0-81d018cb137c.png)

And click Ok.

Done.

&nbsp;

&nbsp;

_______________________________________________________________________________________________________________________________________________________

&nbsp;

&nbsp;

### Power Options

Press the Windows + R keys to open the Run dialog box.

Type `powercfg.cpl` and then press Enter.

Click the arrow "Show additional plans" and choose High performance.

![image](https://user-images.githubusercontent.com/25332460/188212951-e8af5842-b11b-4f66-a72e-5f45fbb97ae4.png)

If it is missing, you can manually add the High Performance plan:

Press the Windows + R keys to open the Run dialog box.

Type `powershell` and then press Enter.

Type `powercfg -duplicatescheme 8c5e7fda-e8bf-4a96-9a85-a6e23a8c635c` in Powershell and press Enter.

Done.

&nbsp;

&nbsp;

_______________________________________________________________________________________________________________________________________________________

&nbsp;

&nbsp;

### Mouse Properties

Press the Windows + R keys to open the Run dialog box.

Type `main.cpl` and then press Enter.

Click the "Pointer Options" tab and unclick "Enhance pointer speed"



![rundll32_c59SKJeOTp](https://user-images.githubusercontent.com/25332460/188221061-d85f4c16-c487-4e4c-89d7-ffe48c0c49c2.jpg)

And click Ok.

Done.

&nbsp;

&nbsp;

_______________________________________________________________________________________________________________________________________________________

&nbsp;

&nbsp;

### Taskbar Clock

Press the Windows + R keys to open the Run dialog box.

Type `Regedit` and then press Enter.

Look for `HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Explorer\Advanced`

Right-click the “Advanced” key in the left panel and select New > DWORD (32-bit) Value.

![image](https://user-images.githubusercontent.com/25332460/188941115-dd8e3244-75e1-49a9-b266-40144f98bcf2.png)


Name the value `ShowSecondsInSystemClock` and press Enter.

![image](https://user-images.githubusercontent.com/25332460/188942366-19ff5571-dffb-4853-afce-758c6ae96b57.png)


![image](https://user-images.githubusercontent.com/25332460/188942134-c946af69-ace8-495c-b4fc-4ee5dc3b0bf5.png)


Double-click the value you just created, enter a value data of `1` and click OK.

![image](https://user-images.githubusercontent.com/25332460/188941507-a2b2548b-174e-410b-bf88-eb96dff227e2.png)


You can now close the Registry Editor. You will now have to sign out and in again or do the following command:

Press the Windows + R keys to open the Run dialog box.

Type `cmd` and then press Enter.

Then type `taskkill /F /IM explorer.exe & start explorer` in cmd to restart Windows Explorer.exe

And click Ok.

Done.

&nbsp;

&nbsp;

_______________________________________________________________________________________________________________________________________________________

&nbsp;

&nbsp;

### Require UAC Password

Press the Windows + R keys to open the Run dialog box.

Type `Regedit` and then press Enter.

Look for `HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Policies\System`

Double-click `ConsentPromptBehaviorAdmin`

![regedit_K4dIJafjCK](https://user-images.githubusercontent.com/25332460/204880320-fe3e242e-fe7a-4e16-8d98-fdbc5a451c99.png)

And set the value to `3`. (Default value is `5`)

![regedit_Seezn86Crb](https://user-images.githubusercontent.com/25332460/204880315-10c1a541-711c-4140-9cec-6a9f2ac5a491.png)

And click Ok.

Done.

&nbsp;

&nbsp;

_______________________________________________________________________________________________________________________________________________________




