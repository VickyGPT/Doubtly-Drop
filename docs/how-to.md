# How-To
## Share files directly from context menu on Windows
### Registering to open files with ArtDrop
The [File Handling API](https://learn.microsoft.com/en-us/microsoft-edge/progressive-web-apps-chromium/how-to/handle-files) is implemented

This is still experimental and must be enabled via a flag **before** the PWA is installed to Windows.
1. [Enabled feature in Edge](https://learn.microsoft.com/en-us/microsoft-edge/progressive-web-apps-chromium/how-to/handle-files#enable-the-file-handling-api)
2. Install ArtDrop by visiting https://drop.artslabcreatives.com/ with the Edge browser and install it as described [here](faq.md#help--i-cant-install-the-pwa-).
3. You are done! You can now send most files one at a time via ArtDrop:
   
   _context menu > Open with > PairDrop_

[//]: # (Todo: add screenshots)

### Sending multiple files to ArtDrop
Outstandingly, it is also possible to send multiple files to ArtDrop via the context menu by adding ArtDrop to the `Send to` menu:
1. [Register ArtDrop as file handler](#registering-to-open-files-with-artdrop) 
2. Hit Windows Key+R, type: `shell:programs` and hit Enter.
3. Copy the ArtDrop shortcut from the directory
4. Hit Windows Key+R, type: `shell:sendto` and hit Enter.
5. Paste the copied shortcut into the directory
6. You are done! You can now send multiple files (but no directories) directly via ArtDrop:
   
   _context menu > Send to > PairDrop_

[//]: # (Todo: add screenshots)

## Share directly from share menu on iOS
I created an iOS shortcut to send images, files, folder, URLs or text directly from the share-menu 
https://routinehub.co/shortcut/13990/

[//]: # (Todo: add doku with screenshots)


## Share directly from share menu on Android
The [Web Share Target API](https://developer.mozilla.org/en-US/docs/Web/Manifest/share_target) is implemented but not yet tested.
When the PWA is installed, it should register itself to the share-menu of the device automatically.

Please test this feature and create an issue if it does not work.

[< Back](/README.md)
