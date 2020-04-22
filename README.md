## Automation Tool to Open repository in IDE directly from Web Page
![Working Screenshot](https://user-images.githubusercontent.com/31308705/79685056-61078280-8253-11ea-8ac1-aab1531ca0ab.gif)
- To **install** simply clone and execute **`./install`**
- Use our  **Browser Extension** To Enable Browser Functionality(availabele in Chrome Extension Directory)[Load Unpacked]
- To understand **git automation and IDE launcher** view the **source file**([starfish.java](https://github.com/fahad-israr/github-automation-and-open-in-ide/blob/master/starfish.java))
- Rest files are intended to **natively register** custom protocol and its handler.
- Opens up **VsCode as IDE**, for the rest  **an editable configuration file** will be added soon.
- Only **Linux Supported Currently (Other OS in Dev)**
- **Terminal Testing using** `xdg-open ide://https://github.com/user-name/repo.git`
- **Native Binary** genrated using `native-image -H:EnableURLProtocols=ide --no-server starfish`
