looper.js - fluid function runner

looper.js provides a way for javascript developers to create isolated, heavily controllable execution environments to run continuous processes. looking at it from a low level perspective, it acts as a complex recursive setTimeout, with its base functionality being the execution of a chain of functions. 

from a developer’s perspective you are gaining the ability to run a series of functions, with varying delay times when needed, as well as the ability to bidirectionally control its execution process. similar to something like controls for a video player, at any time during your execution process you can do things like: start, stop, pause, play, replay, rewind, fast forward, and more. you can also provide callbacks to execute before and after each function as well as before and after each execution process.

written with vanilla javascript, this tool can be applied on the front end of a site as well as on the backend using systems such as node.js. further, by having the ability to control your function chain throughout its execution you can help to avoid the usual async concerns such as large sets of nested callbacks and timing issues. 

