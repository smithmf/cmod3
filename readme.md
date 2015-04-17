# cmod3

cmod3 is a module music player built by Josep Llodrà (aka herotyc^modulez).

Don't you know what tracked music is? [Look here](http://en.wikipedia.org/wiki/Music_tracker).

## Download cmod3

* Mac OSX x64: soon
* Windows: soon
* Linux: soon


## Features

* Play/Stop/Pause/Seek...
* Drag and drop (folders and files)
* Metadata for the current module
* Nectarine Radio player built-in!
* Repeat and shuffle modes
* Classic VU meter

## How does cmod3 work?

cmod3 is entirely written in **Javascript**, works on node-webkit (nwjs) and uses libopenmpt compiled with emscripten plus closure-compiler. The UI stuff is angular+bootstrap. Despite all that, and after a hard work, it performs really well.

## Things yet to improve

* Audio is decoded on the main thread, which is not ideal, it should be done on a background worker/thread and see if it performs better.
* Settings are not saved yet.
* Keyboard shortcuts would be great.

## Versions

17/04/2015: 0.0.5 - first release


