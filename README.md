# Learning Emscripten
## Overview
I've been learning the C-to-WebAssembly/JS compiler "Emscripten".
I've heard a lot of good (or at least interesting) things about
WebAssembly, and those of you who read my blog know I'm a huge C
fan.  I've also heard Emscripten works with SDL (an awesome game
engine) and also HTML5 APIs (which WASM apparently can't do by
itself).  I've even seen websites where people have built ENTIRE
OPERATING SYSTEMS using Emscripten.  Not just retro emulators - 
I'm talking Linux and early Windows!  That's ridiculous IMO, but
Emscripten looks really cool, so here we go! :)

## Project goals
I normally don't put experimental projects like this on my GitHub,
but I figured it might help others.  I will consider this project
"done" when:

1. I have a working game using SDL; maybe something simple like Pong.
    This game will have ports for Linux, the web, and (most likely)
    Windows, and be hosted on [Geek on Skates Games](http://www.geekonskates.com/games).
2. I have a working web page that uses one or more HTML5 APIs.  This
    is an interesting thought; I want to see how well the finished
    page will work on my Raspberry Pi 3B+.  I've heard there are some
    huge performance drawbacks with Emscripten, so the idea of using
    it for anything other than porting existing C code seems to be 
    considered a dumb idea.  But if the Pi can take it - if it can
    play my game and this web app without crashing or slowing to a
    grinding halt, then this might be something I want to try on other
    projects.  For those of you who don't know, the Raspberry Pi is a
    $35 computer, and mine isn't even the latest model.  Smartphones
    are similar in size but are way more powerful - the Pi is as cheap
    as computers get, and really struggle with resource-hogging sites
    like YouTube or Amazon (it can use both, but tends to be sluggishly
    slow or just plain crash).

    As far as the actual project, I'm thinking a form that speaks what
    you give it using the Web Speech API.  Or maybe it'll be something
    using Canvas, or Web Audio, or some combination of these.  But the
    compiled code will create the form, and do something cool with it.

## Unlicense

Yes, I'm unlicensing this project.  IMO this is the best way to make
software truly freed.  Nothing against the great work the GNU guys are doing, but even the GPL is basically, "this is freed software IF you do {x}" (still trying to learn what the different {x}'s are for the different licenses, which ones are compatible or not etc.).  But the Unlicense puts my work in the public domain - no ifs, ands, or buts.  Of course if you use my work as the foundation for something much bigger and cooler, a credit to the Geek on Skates (ideally with [my website](http://www.geekonskates.com), would be AWESOME.  But it's not REQUIRED.  It's freed software.

**NOTE:** I use "freed" to mean _<span lang="es">libre</span>_ and "free" for
_<span lang="es">gratis</span>_.  I love that someone felt the need to use Spanish to clarify that difference, but in reality that's just kind of silly. _Yo entiendo bien el espa&ntilde;ol, pero &iquest;realmente la necesitamos para explicar la diferencia?  &iquest;No tiene el idimoa ingl&eacute;s suficientes palabras para explicarla?_ 😀).

## Contributing

If I ever get stuck on something (and I'm sure I will), I'll be putting it in the issues section.  If you know what you're doing with Emscripten and want to help me through those things, please feel free to do that.  
