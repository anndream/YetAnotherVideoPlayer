# Yet Another Video Player
Yet Another Video Player (YAVP for short) is a Android Video Player based on Exoplayer V2


# Features

* **Open Source**
* **Playback  of Video- and Audio Files and Streams**
	* currently only mp4, more to come
* **Swipe Gestures for Volume & Brightness**
* **Kind of nice UI**, I guess...
* **It is just a Video Player, what did you expect?**


## Things you should Know

* __YAVP does not require any app permissions*__
	* Storage Permissions are ony needed for playing local files
* At least Android 7.0 (Nougat) is required (this may change)
* YAVP currently does not feature a (real) Launcher Activity
	* Open YAVP by opening a supported file or URL and selecting YAVP
* While Anime4K is great at making Anime (-Style) Videos look great, it is also great at eating into your battery.
	* Expect (much) shorter battery life when Anime4K is enabled.
	* Limiting FPS is a option to prolong your battery life. You can enable it in the settings.
	* *But YAVP is nice enough to warn you before your phone dies.*

* I'm currently redesigning the UI, and I won't add any screenshots before that is done.
* This is my first Android App & My first project public on Github
	* *If I did/do anything wrong or could do something better, let me know :)*

* *Not any = not any __unreasonable__. Obviously, YAVP can't stream videos if it can't access the Internet...*

## Issues, Feature Requests and Contributing

Please make sure to read these guidelines. Your issue may be closed without warning if you don't.

#### Issues
* **Before reporting a new issue, take a look at  already opened [issues](https://github.com/shadow578/YetAnotherVideoPlayer/issues).**

#### Bugs

* **Include the App Version**
	* If not on the latest App Version, try updating the app. The Issue may have already been solved
* **Include Steps to reproduce the Bug** (if not obvious from the Description)
* **Include Screenshot** (if needed)
* **If you suspect the Bug may be device specific, try reproducing on another device** (if possible)
* For large logs use [pastebin.com](https://pastebin.com/) or similar
* Don't group unrelated requests into one issue

#### Feature Requests
* Write a detailed issue, explaining what (or how) the Feature should
	* Avoid writing "...like (this) app does"
* Include Screenshots (if needed)


## Why use YAVP?

YAVP is not meant to compete with players like VLC or MX Player.
I do not maintain it for the sake of being better than other apps. It is meant as a simple Video Player you can use to Stream Videos over the Internet.
That said, here are some reasons to pick YAVP over other apps:

* **Free with no Ads**
	* *looking at you, MX Player*
* **YAVP is built using the most recent SDK build tools** for best compatibility with both phones and tablets
* **It requires no app permissions**, so it can't spy on you
	* Storage Permissions are needed to play back local Videos, but granting those permissions is not needed if you just want to stream
* **YAVP is a native Android App written in Java using Android Studio**
	* so no Xamarin/Visual Studio🎉


## Credits

* [google/ExoPlayer](https://github.com/google/ExoPlayer)
* [google/Material-Design-Icons](https://github.com/google/material-design-icons)
* [pnikosis/materialish-progress](https://github.com/pnikosis/materialish-progress)
* [svenwiegand/time-duration-picker](https://github.com/svenwiegand/time-duration-picker)
* [MasayukiSuda/ExoPlayerFilter](https://github.com/MasayukiSuda/ExoPlayerFilter)


This Application uses a custom implementation of [Anime4K v0.9](https://github.com/bloc97/Anime4K/)