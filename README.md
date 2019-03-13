# ![logo](https://raw.githubusercontent.com/mattlag/Azure-Icon-Downloader/master/dev/icons/icon32.png) Azure Icon Downloader

Chrome (and future-Edge!) extension to easily find and download 
SVG icons from the Microsoft Azure portal.

### Basically does two things:
 - When you're on portal.azure.com, it lists all the icons that are in the current view.
 - You can give each icon a name, and download it from the extension's popup.
 - In the background, the extension adds `fill="#"` color attributes that correspond to the CSS-based fill colors, so that the SVG icons can be used outside of the Azure portal.