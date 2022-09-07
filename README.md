### Windows Settings

- ##### Windows Settings
  - [Performance Options](#performance-options) - Remove Animations.
  - [Power Options](#power-options) - Lets your PC use more energy.
  - [Mouse Properties](#mouse-properties) - Remove the feature that calculates the velocity of the mouse and adjusts the DPI.

   ##### Registry Hacks
  - [Taskbar Clock](#taskbar-clock) - Show Seconds.
  - [Context Menu](#context-menu) - Add Any Application to the Windows Desktop Right-Click Menu.


<!-- vim-markdown-toc -->




### Portable Applications


- [7-Zip](https://www.7-zip.org/download.html) - File archiver with a high compression ratio and built-in encryption functionality.
- [ShareX](https://github.com/ShareX/ShareX/releases) - Lets you take screenshots of any selected area with a single key.
- [Discord portable](https://github.com/portapps/discord-portable) - Portable instead of the regular auto install.
- [Open Hardware Monitor](https://openhardwaremonitor.org/downloads/) - Free open source software that monitors temperatures.
- [Geek Uninstaller](https://geekuninstaller.com/) - Geek Uninstaller is a perfectly functional uninstaller. Also removes attached registry keys.



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


_______________________________________________________________________________________________________________________________________________________

### Performance Options

Press the Windows + R keys to open the Run dialog box.

Type `systempropertiesperformance` and then press Enter.

Copy these settings:

![image](https://user-images.githubusercontent.com/25332460/188121561-56314c8e-6644-4251-97d0-81d018cb137c.png)

If it isnt an alternative you can manually add High Performance plan

Press the Windows + R keys to open the Run dialog box.

Type `powershell` and then press Enter.

`powercfg -duplicatescheme 8c5e7fda-e8bf-4a96-9a85-a6e23a8c635c`

Now it shows in Control Panel






_______________________________________________________________________________________________________________________________________________________


### Power Options

Press the Windows + R keys to open the Run dialog box.

Type `powercfg.cpl` and then press Enter.

Click the arrow "Show additional plans" and choose High performance



![image](https://user-images.githubusercontent.com/25332460/188212951-e8af5842-b11b-4f66-a72e-5f45fbb97ae4.png)

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

### Context Menu

Press the Windows + R keys to open the Run dialog box.




_______________________________________________________________________________________________________________________________________________________

