# MediaKiosk
Play and queue digital videos in a media jukebox, art installation, etc.


Written for the Multimedia Jukebox with Luke J. and Peter K. at MHC 2018

Designed to listen for keystrokes and play or queue up MP4 video files

Use a raspberry pi or arduino as a keyboard emulator to add 
custom buttons or other controls

Type 0-9 to queue up videos from the vidFile and vidTitle arrays

Special keys: r=reload, s=skip to next

Use query string to adjust video size, padding, font size on the fly:
media-kiosk.html?w=960&p=40&f=20

Public domain video samples courtesy of the Prelinger Archives: 
https://archive.org/details/Televisi1960

Don't forget to adjust Chrome's new video autoplay policy:
chrome://flags/#autoplay-policy - set to "No user gesture is required"

Enjoy! -Nick
