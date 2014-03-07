![OpenSpritz](http://i.imgur.com/LOtmyf9.gif)

Bookmark this link:

   javascript:(function()%7B cb %3D function()%7B create_spritz()%3B%7D%3B var script%3Ddocument.createElement(%27SCRIPT%27)%3Bscript.src%3D%27https://msbarry.github.io/OpenSpritz/spritz.js%3Fcallback%3Dcb%3Fcallback%3Dcb%27%3B script.onload%3Dcb%3B document.body.appendChild(script)%3B%7D)()%3B

# OpenSpritz

OpenSpritz is an extremely crude implementation of [Spritz](http://www.spritzinc.com/) in JavaScript. It works as a bookmarklet to add Spritz-type speed reading to every page.

### Testimonials

* "I'm not easily impressed, but this blew me away. You can have very good understanding of the text and still read
blazingly fast." - [norswap](https://news.ycombinator.com/item?id=7349966), HackerNews

* "Super cool reading tool that helps you read at 800wpm. Kind of like watching television, only with words." - [@janeka](https://twitter.com/janeka/status/441375832309637121), Twitter

* "Crushing my inbox with @GUNdotIO's OpenSpritz. If only it extracted data from my brain as well." - [@climb23k](https://twitter.com/climb23k/status/441330307636031488), Twitter

## Installation

To install OpenSpritz, follow [this guide at **gun.io**](https://gun.io/blog/openspritz-a-free-speed-reading-bookmarklet).

## Features

* Spritz-type speed reading
* Word length and grammar-aware speed reading
* WPM selector
* Cross-browser bookmarklet
* Text-selection aware
* Readabilty-based article extraction

## Contributing

OpenSpritz needs you! If you find bugs, have feature requests, or have other needs, please help out!

The best way to contribute is to start a new ticket, or to work on an existing ticket. If you find a website which doesn't work with OpenSpritz, [add it to this ticket](https://github.com/Miserlou/OpenSpritz/issues/8) so that it can be diagnosed and fixed.

OpenSpritz currently needs a little more love to make it work with JSONP and needs a better method of detecting the presence of jQuery, so those are some good places to start.

Once you have tested your changes and confirmed they work, send a pull request. Add yourself to the list of contributors below as well!

### Contributors

* [Rich Jones](https://github.com/Miserlou)
* [Nick R](https://github.com/niroyb)

## Sister Projects

* [OpenSpritz-Android](https://github.com/OnlyInAmerica/OpenSpritz-Android) - An Android Spritz ePub Reader by [@OnlyInAmerica](https://github.com/OnlyInAmerica) 
* [SpritzerTextView](https://github.com/andrewgiang/SpritzerTextView) - An Android Spritz View by [@andrewgiang](https://github.com/andrewgiang)
* [speedread](https://github.com/pasky/speedread) - A terminal Spritzer. by [@pasky](https://github.com/pasky)
* [jetzt](https://github.com/ds300/jetzt) - jetzt, a Spritz Chrome extension by [@ds300](https://github.com/ds300)

#### A Note About the Name

OpenSpritz has nothing to do with [Spritz Incorporated](http://www.spritzinc.com/). This is an open source, community created project, made with love because Spritz is such an awesome technique for reading with. _(Please don't send us a DMCA take down request! That'll only backfire on you anyway. We love you.)_
