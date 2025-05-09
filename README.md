# webinterface.xbmciphone addon for XBMC

This is a [XBMC](https://xbmc.tv) iPhone Remote interface addon.

[![License: GPL-2.0-or-later](https://img.shields.io/badge/License-GPL%20v2+-blue.svg)](LICENSE.md)

![screenshot](https://raw.githubusercontent.com/xbmc4xbox/webinterface.xbmciphone/refs/heads/master/resources/screenshot-01.png)

Xbox Media Center iPhone Remote
===============================


Introduction
------------


This project aims to provide an easy to use yet powerful remote control for Xbox Media Center using Apple's [iPhone](http://www.apple.com/iphone). [Xbox Media Center](http://www.xboxmediacenter.com/) is an open source application that can be run on a modified Xbox to play audio, video, DVDs, photo slideshows, and other media.

iPhone's web browser (based on [WebKit](http://www.webkit.org)) can display full interactive webpages, and Xbox Media Center (XBMC) contains a simple web server that can store web page and react to various commands like pause, play, and many more. The remote is written entirely in JavaScript, HTML, and CSS, and makes use of [iUI](http://www.joehewitt.com/iui/), a framework for iPhone-like interfaces on web apps, written by Joe Hewitt.

Using iUI allowed us to create an interface very similar to the iPhone's native interface, which is also very easy to use.


Features
--------

XBMC iPhone Remote is still a work in progress. Listed below are the partially and fully implemented features, as well as some future features.

### Current Features ###

- Transport controls, including pause/play, next/previous track in playlist, and volume controls.
- Automatic switching between file browsing mode and transport controls mode via iPhone's built in tilt sensor (file browsing in portrait, transport controls in landscape).
- Viewing information on the currently playing media, including title, ID3 tags, album artwork, and much more.
- Browsing of audio, video, photo, and file shares.
- Playing audio, videos, and slideshows.
- Managment of the audio, video, and slideshow playlists, including adding/removing media and playing of playlists.
- Launching of scripts within the Scripts directory.
- Restart, shutdown, eject, mute and various other controls,

### Future Features ###

- More comprehensive transport controls.
- Saving of playlists.
- Settings.
- Searching.


Requirements
------------

Xbox Media Center is, of course, required. This has only been tested on recent (2007) versions of XBMC. The interface works best on an actual iPhone, but will also function on Safari 3.0 Beta for Mac OS X or Windows. It has not been tested on any other browsers, but should work on Firefox and others.


Installation
------------

You can use the automated web installer (modified from [LiquidIce's](http://www.liquidicelabs.com/xbmc/installAJAX.php)) or follow the manual instal instructions.

### Web Installer ###

Please visit http://tlrobinson.net/projects/xbmciphone/ for the web installer.

### Manual Install ###

If you would prefer to manually install XBMC iPhone Remote, follow these instructions:

1. [Download](http://tlrobinson.net/projects/xbmciphonexbmciphone-0.1.zip) the latest version
2. Unzip it
3. FTP into your Xbox and upload the "iphone" directory to the "web" directory on your Xbox (so it should be located at Q:\web\iphone\).

To access the application, point your web browser to http://xbox/iphone/ where "xbox" is replaced with your Xbox's actual IP address.

Instructions
-------------

Using the remote is simple and easy to figure out, but here's a few tips:

- To use the transport controls rotate the iPhone to landscape orientation (please note the bug mentioned below). Rotate back to portrait orientation to use the file browser.
- To view media shares, click one of the media categories (Audio, Video, Pictures, Files) on the main screen.
- Tap folders to view the contents or play the file (if there's a play button to the right) and click the plus buttons on the left to add a file or entire folder to a playlist. In Files shares, items are added to the most recently used playlist, either Audio or Video. In all other shares files are added to their appropriate playlist (however no filtering is done, so it's possible to add videos to the audio playlist, etc).
- Tap a playlist on the main screen to view it. Here you can view, edit, clear, and play the playlist.
- To remove an item from a playlist, tap the red delete button to the left of an item in a playlist.
- To immediately play an item in a playlist simply tap it (please note the bug mentioned below).
- Tap the title at the top of each page to return directly to the main screen.


Known Issues / Bugs / TODO
---------------------------

- After deleting an item in a playlist you must reload the playlist before trying to use.
- Transport controls are partially or fully hidden by sub-pages (but not the main page).
- There are several GUI bugs, especially when clicking items to add to or remove from playlists.
- "Now Playing" doesn't automatically update.

Please contact me at <script type="text/javascript">email_link();</script> if you find any other bugs not mentioned here, or if you have any other comments or suggestions.

Download
--------

[Xbox Media Center iPhone Remote](http://tlrobinson.net/projects/xbmciphone/xbmciphone-0.1.zip) - version 0.1


Screenshots
-----------

Please visit http://tlrobinson.net/projects/xbmciphone/ for screenshots.


Version History
---------------

### Version 0.1 (7/27/2007) ###

- Initial Release


License
-------

Both XBMC iPhone Remote and the modified version of iUI included with it are released under the BSD license.