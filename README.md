RemoteMetadataProvider
================

This project aims to provide a unified library which merges support for the API<18 and API18
versions of RemoteMetadataProvider by DrBreen.
The library makes it possible to use the hidden interface IRemoteControlDisplay and hidden methods
of AudioManager in order to do the same work that the official RemoteController API does on API19.

http://developer.android.com/reference/android/media/RemoteController.html:

"The RemoteController class is used to control media playback, display and update media metadata and playback status, published by applications using the RemoteControlClient class.

A RemoteController shall be registered through registerRemoteController(RemoteController) in order for the system to send media event updates to the RemoteController.OnClientUpdateListener listener set in the class constructor. Implement the methods of the interface to receive the information published by the active RemoteControlClient instances. 
By default an RemoteController.OnClientUpdateListener implementation will not receive bitmaps for album art. Use setArtworkConfiguration(int, int) to receive images as well.

Registration requires the RemoteController.OnClientUpdateListener listener to be one of the enabled notification listeners (see NotificationListenerService)."

###Original project: https://github.com/DrBreen/RemoteMetadataProvider

###Further work done by: https://github.com/WisdomWolf/RemoteMetadataProvider

###DrBreen's Awesome RemoteMetadataProvider Guide: http://forum.xda-developers.com/showthread.php?t=2432267

