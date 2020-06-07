SpringArtwork-Public
=================
## This repo
This repo serves as the place to report bugs found within SpringArtwork. Having them all at one place, it's easier for everyone else to see progress about an issue. It's also easier for me instead of having everything spread out across Reddit, Twitter and emails.

If you're experiencing a bug, please open an issue and I'll look at it as soon as I can. Please include iOS version, device model and any other usable information needed to reproduce the problem.

### Troubleshooting / FAQ
#### I would like to request different settings for LS and HS.
That's a good request! The only problem is that the implementation for it is rather complex. Currently when sharing wallpaper between the homescreen and the lockscreen, so is SpringArtwork's view. That means that the same view needs to be altered between every unlock/lock as opposed to simply hiding/showing it (as is happening now when SpringArtwork is only enabled in one of the modes). I might look into it, but it's a low priority for now.

#### Spotify Canvas videos aren't showing up?
* SpringArtwork only works with the official version of Spotify. Make sure you're running the latest and official version.

* Make sure you're not using a tweak injection blocker such as HideJB or Unsub that blocks SpringArtwork from loading into Spotify.

## Short description
*Compatible with iOS 11 to 13*

SpringArtwork uses the current artwork as wallpaper on both the lockscreen and the homescreen. Works with all media apps. If using Spotify, it uses the video artwork if applicable. 

Currently available on my [beta repo](https://http://henrikssonbrothers.com/cydia/repo).
