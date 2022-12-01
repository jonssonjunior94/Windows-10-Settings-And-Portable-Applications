### Windows Settings

- ##### Windows Settings

  - [Performance Options](#performance-options) - Remove Animations.
  - [Power Options](#power-options) - Lets your PC use more energy. (Balanced is better)
  - [Mouse Properties](#mouse-properties) - Remove the feature that calculates the velocity of the mouse and adjusts the DPI.

   ##### Registry Hacks
  - [Taskbar Clock](#taskbar-clock) - Show Seconds.
  - [Context Menu](#context-menu) - Add Any Application to the Windows Desktop Right-Click Menu.
  - [Require UAC Password](#require-uac-password) - Promt password for every approval. Even as Administrator. Further steps to stop malicious programs or malware to find ways to obtain admin privileges.


<!-- vim-markdown-toc -->




### Portable Applications


- [7-Zip](https://www.7-zip.org/download.html) - File archiver with a high compression ratio and built-in encryption functionality.
- [ShareX](https://github.com/ShareX/ShareX/releases) - Lets you take screenshots of any selected area with a single key.
- [Discord portable](https://github.com/portapps/discord-portable) - Portable instead of the regular auto install.
- [Open Hardware Monitor](https://openhardwaremonitor.org/downloads/) - Free open source software that monitors temperatures, fans, voltages, load and clock.
- [Geek Uninstaller](https://geekuninstaller.com/) - Geek Uninstaller is a perfectly functional uninstaller. Also removes attached registry keys.
- [Notepad++](https://notepad-plus-plus.org/downloads/) - Notepad++ is a great replacement for Windows notepad. It's a good choice for beginners.
- [VLC](https://www.videolan.org/vlc/download-windows.html) - VLC is a free and open source cross-platform multimedia player and framework that plays most multimedia files, and various streaming protocols.


#### Extras
- [Scrcpy](https://github.com/Genymobile/scrcpy) - This application provides display and control of Android devices connected via USB.
- [yt-dlp](https://github.com/yt-dlp/yt-dlp) - A youtube-dl fork with additional features and fixes. Works great with [youtube-dl-gui](https://github.com/oleksis/youtube-dl-gui).
- [Twitch GUI](https://github.com/streamlink/streamlink-twitch-gui) - A multi platform Twitch.tv browser for [Streamlink](https://github.com/streamlink/streamlink). Works great with [VLC](https://www.videolan.org/vlc/download-windows.html).
- [Everything](https://www.voidtools.com/) - Locate files and folders by name instantly. Plus [Everything Toolbar](https://github.com/stnkl/EverythingToolbar) for the taskbar.

#### Useful Websites
- [Send](https://github.com/timvisee/send-instances/#instances) - Share encrypted files with ease.
- [Gmailnator](https://www.emailnator.com/) - Temporary Disposable Gmail.
- [Redirect Detective](https://redirectdetective.com/) - URL redirection checker, see the complete path a redirected URL goes through.
- [Have i been pwned](https://haveibeenpwned.com/) - Check if your email or phone is in a data breach. Only knows publicly discovered breaches.
- [IsThereAnyDeal](https://isthereanydeal.com/?currency=USD) A useful little web tool that tracks PC game prices across a variety of sources, including Steam and third-party.
- [VirusTotal](https://www.virustotal.com/gui/home/upload) Free service that analyzes files and URLs for viruses. It's not advisable to upload sensitive/personal files.

#### Browser Extensions
- [Decentraleyes](https://decentraleyes.org/) - Protects privacy by evading large delivery networks that claim to offer free services.  [Firefox](https://addons.mozilla.org/en-US/firefox/addon/decentraleyes/), [Chrome](https://chrome.google.com/webstore/detail/decentraleyes/ldpochfccmkkmhdbclfhpagapcfdljkj)
- [Imagus]() - With a simple mouse-over you can enlarge images and display images/videos from links. [Firefox](https://addons.mozilla.org/en-US/firefox/addon/imagus/), [Chrome](https://chrome.google.com/webstore/detail/imagus/immpkjjlgappgfkkfieppnmlhakdmaab?hl=en)
- [Ublock Origin](https://ublockorigin.com/) - Free and open-source browser extension for content filtering, ad blocking. [Firefox](https://addons.mozilla.org/en-US/firefox/addon/ublock-origin/), [Chrome](https://chrome.google.com/webstore/detail/ublock-origin/cjpalhdlnbpafiamejdnhcphjbkeiagm?hl=en)
- [SponsorBlock](https://sponsor.ajay.app/) - SponsorBlock is a crowdsourced extension that lets anyone submit the start and end times of sponsored segments and other segments of YouTube videos [Firefox](https://addons.mozilla.org/en-US/firefox/addon/sponsorblock/), [Chrome](https://chrome.google.com/webstore/detail/sponsorblock-for-youtube/mnjggcdmjocbbbhaepdhchncahnbgone?hl=en)

_______________________________________________________________________________________________________________________________________________________


### Performance Options

Press the Windows + R keys to open the Run dialog box.

Type `systempropertiesperformance` and then press Enter.

Copy these settings:

![image](https://user-images.githubusercontent.com/25332460/188121561-56314c8e-6644-4251-97d0-81d018cb137c.png)


_______________________________________________________________________________________________________________________________________________________


### Power Options

Press the Windows + R keys to open the Run dialog box.

Type `powercfg.cpl` and then press Enter.

Click the arrow "Show additional plans" and choose High performance.

![image](https://user-images.githubusercontent.com/25332460/188212951-e8af5842-b11b-4f66-a72e-5f45fbb97ae4.png)

If it is missing, you can manually add the High Performance plan:

Press the Windows + R keys to open the Run dialog box.

Type `powershell` and then press Enter.

Type `powercfg -duplicatescheme 8c5e7fda-e8bf-4a96-9a85-a6e23a8c635c` in Powershell and press Enter.


_______________________________________________________________________________________________________________________________________________________


### Mouse Properties

Press the Windows + R keys to open the Run dialog box.

Type `main.cpl` and then press Enter.

Click the "Pointer Options" tab and unclick "Enhance pointer speed"



![rundll32_c59SKJeOTp](https://user-images.githubusercontent.com/25332460/188221061-d85f4c16-c487-4e4c-89d7-ffe48c0c49c2.jpg)

Done.


_______________________________________________________________________________________________________________________________________________________


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

Done.











_______________________________________________________________________________________________________________________________________________________

### Require UAC Password

Press the Windows + R keys to open the Run dialog box.

Type `Regedit` and then press Enter.

Look for `HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Policies\System`

Double-click `ConsentPromptBehaviorAdmin`

![regedit_K4dIJafjCK](https://user-images.githubusercontent.com/25332460/204880320-fe3e242e-fe7a-4e16-8d98-fdbc5a451c99.png)

And set the value to `3`. (Default value is `5`)

![regedit_Seezn86Crb](https://user-images.githubusercontent.com/25332460/204880315-10c1a541-711c-4140-9cec-6a9f2ac5a491.png)

And click Ok.

_______________________________________________________________________________________________________________________________________________________
