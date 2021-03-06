SnooScreens
=============

SnooScreens allows you to change your wallpaper based on the front page of the subreddit or mulitreddit of your choice. You simply pick a subreddit or multireddit and an activation method using Activator and you’re good to go! There are also options for allowing or blocking NSFW images, setting to the home screen, lock screen, or both, saving to the photo library, and using the top image post on a subreddit, or a random one from the front page (top 25).

There are 5 separate Activator listeners, so you can get wallpapers from different subreddits at different times or occasions. Each listener has its own independent settings, so one can set your lock screen to the top post of /r/spaceporn at 6:30 AM, save it to your library, and block NSFW images, while another could set your home screen to a random post from the front page of /r/wallpaper when you shake your phone, allowing NSFW images and not saving it to your photo library. And you can have any permutation of these settings with 5 different listeners.

While SnooScreens is a commercial tweak, it is still open source.

Special thanks to HASHBANG Productions for DailyPaper, Ben Rosen and CPDigitalDarkroom for Faces, CPDigitalDarkroom for help with the preference bundle, and uroboro for lots of stuff :)

###TODO:

* ~~Prevent duplicate photo saves (CFPreference Utils) - biggest hoop: what if they change the wallpaper on their own in between?~~
* Resize images
* ~~Prevent downloading the same image (CFPreference Utils)~~
* Skip wallpaper option (some sort of timer to keep looking if you’re not happy. I want it to be unintrusive and let the user do nothing if they’re happy with the wallpaper)
* Bring up wallpaper view (Look into [SBSUIWallpaperPreviewViewController](http://developer.limneos.net/index.php?ios=8.0&framework=SpringBoardUIServices.framework&header=SBSUIWallpaperPreviewViewController.h) and [PLWallpaperImageViewController](http://developer.limneos.net/index.php?ios=8.0&framework=PhotoLibrary.framework&header=PLWallpaperImageViewController.h)).
* Save into a specific album.
* ~~Individual save wallpaper button~~

![Settings pane](/screenshots/1.jpg?raw=true) ![Subreddit settings](/screenshots/2.jpg?raw=true) ![Activator](/screenshots/3.jpg?raw=true)

Licensed under MIT License

    The MIT License (MIT)
    
    Copyright (c) [year] [fullname]
    
    Permission is hereby granted, free of charge, to any person obtaining a copy
    of this software and associated documentation files (the "Software"), to deal
    in the Software without restriction, including without limitation the rights
    to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
    copies of the Software, and to permit persons to whom the Software is
    furnished to do so, subject to the following conditions:
    
    The above copyright notice and this permission notice shall be included in all
    copies or substantial portions of the Software.
    
    THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
    IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
    FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
    AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
    LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
    OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
    SOFTWARE.
