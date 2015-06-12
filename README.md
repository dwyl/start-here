Start Here
==========

![sho+shin](http://i.imgur.com/p538Ld2.jpg)

> Start where you are. Use what you have. Do what you can.
> ~ [Arthur Ashe](http://en.wikipedia.org/wiki/Arthur_Ashe)

A Quick-start Guide for People who want to build awesome apps.

## (Start with) Why?

The world is not perfect. <br />
We have all worked somewhere we *didn't* ***love***. <br />
We have all experienced using products that had/have flaws. <br/>
Rather than *waiting* for someone else to solve our "problems"
we are taking on the challenge ourselves.

**We simplify. We enable people to get through their _need-tos_ efficiently so they can get to their _want-tos_.** If you'd like to know more, take a look at **our [manifesto](/manifesto.md)**.

## Who?

Who is "We"? <br />
For now we are just four people:
[@iteles](https://twitter.com/iteles), [@nelsonic](https://twitter.com/nelsonic),
[@edwardcodes](https://github.com/edwardcodes)
and
[@hyprstack](https://github.com/hyprstack)

***Join us*** in finding something you want to ***solve*** and will
***love*** working on.


## What?

We are building the web/mobile applications that we wish existed.

- Card App [working title]
- ideaQ [record, prioritise, share & collaborate on your ideas]
- time [time tracking]
- *What question do* ***you*** *want to answer...*?


### Scratching Your Own Itch

We believe in scratching our own itches.
Scratching your own itch means solving a problem you (or someone *close* to you) *personally* have.
If you (or someone close to you) don't have any personal experience in a field
you aren't going to do a good job of spotting/solving a problem in that area.

Read:
https://gettingreal.37signals.com/ch02_Whats_Your_Problem.php

## What do I need?

- [x] ***Curiosity*** - "I have no special talent. I am only passionately curious." ~ Albert Einstein
- [x] ***Enthusiasm*** - "Enthusiasm spells the difference between mediocrity and accomplishment." ~ Norman Vincent Peale
- [x] [***Shoshin***](http://en.wikipedia.org/wiki/Shoshin) (**Beginner's Mind**)
  + "*I'm not young enough to know everything*" ~ [J. M. Barrie](http://en.wikiquote.org/wiki/J._M._Barrie)
  + “*Your mind is like a parachute; it only works when it is open*.”  ~ Anthony D'Angelo
- [x] ***Persistance*** - “If you wish to be out front, then act as if you were behind.” ~ Lao Tzu
- [ ] Time (work [**super hard** ... ***every waking hour***](https://www.youtube.com/watch?v=NU7W7qe2R0A))
- [x] **Awareness** of how you're spending your time and learning to work to your productive hours and habits
- [ ] Knowing when to ask for help and when to persevere through to find the answer yourself

### What tools will I need?

- [x] ***A computer*** (preferably a *recent* one)
- [x] A text editor. e.g. [Atom](https://atom.io/)
- [x] [Node.js](http://nodejs.org/download/) for building server-side apps.


## Web Development *Fun*damentals


### Touch Typing

***Before*** you dive into programming, learning how to touch-type on your
computer is the *single* ***best investment*** you can make.
All this means is *practicing* typing with the "*correct* fingers" until you don't have to think about where the keys are. Some of the best programmers we know can type faster than *most* people can *think* ... take a moment for that to settle in.

[![playing piano blindfolded](http://i.imgur.com/4dzAeSz.jpg)](https://www.youtube.com/watch?v=Z-iyiWHI2nA "playing piano blindfolded")

You need to be able to type ***blindfolded*** to become a true maestro.


### HTML5

You can learn 90% of what you need to know in HTML in a couple of hours (*from scratch*):

+ HTML Tutorial for Beginners in 1 Hour: https://www.youtube.com/watch?v=5TBU_jLZuG4
+ Learn HTML**5** from Scratch in 1 Hour: Learn HTML5 in 1 Hour: https://www.youtube.com/watch?v=s37GTK6JFcI


### CSS

**C**ascading **S**tyle **S**heets (***CSS***) is what makes the web attractive. If you want to see the power of CSS, visit ZenGarden:  http://www.mezzoblue.com/zengarden/alldesigns/

+ CSS Tutorial for Beginners in 1 Hour: https://youtu.be/hChVrWENonE?t=9s

### JavaScript

Love it or hate it, **JavaScript is** ***Ubiquitous***. Becoming a ***JS Ninja*** is ***essential***.
[Ines](http://github.com/iteles) has prepared a great notes on
[JavaScript The Good Parts](https://github.com/iteles/Javascript-the-Good-Parts/blob/master/Notes-on-Javascript-the-Good-Parts.md)
Keep "**The Good Parts**" in mind while you are *writing* (*and reading*) JS.

Watch this 1h intro tutorial: https://www.youtube.com/watch?v=fCa7yTZV4tQ

#### Server-Side = Node.js

+ What is Node.js and why is it useful? https://www.youtube.com/watch?v=pU9Q6oiQNd0
- Download: http://nodejs.org/download/ (all platforms)
- Beginners guide: http://www.nodebeginner.org/
- Udemy Tutorial: https://www.udemy.com/nodejs-tutorial-from-scratch-by-examples
- Node.js (books): https://github.com/Pana/node-books
- Node.js style guide: https://github.com/felixge/node-style-guide

> Investigate: http://tableflip.io/building-a-dnode-rpc-server-in-50-lines-of-code/

### Testing

Testing is often left as an afterthought or ommitted completely from
"beginner" tutorials or books. That will not be the case here.
You will learn *why* testing is not just a "nice-to-have".

### Service Oriented Architecture with (REST) APIs

We will be building our apps with RESTful
[Service Oriented Architecture](http://en.wikipedia.org/wiki/Service-oriented_architecture)
Backend. This has *several* advantages:

1. Each piece of functionality is run as a service (so its easy to isolate, test and scale)
2. The client we build (web app or mobile app) both (independently) "consume" the same service via REST API
(which means that the font-end is completely decoupled from the backend of the app - easier to change/itterate)
3. If our app/product gets popular we already have an API built and can allow 3rd party integration/extensions.


I'm busy preparing a *detailed* tutorial for doing exactly this using Hapi.js
at: https://github.com/nelsonic/learn-hapi
You can already get started reading it and the supporting links
And watch as the tutorial progresses.


> Watch: https://www.youtube.com/watch?v=uDzME15UxVM (Share.js)


### Which Client MVC Framework?

- Angular.js - Mature and full-featured.
- ~~Backbone.js~~
- Riot.js - Minimalist (learn it in 2h)

Right now I'm toying with the idea of using either Angular or Riot.

Ultimately we want to wrap our JS as PhoneGap app (see mobile below)
so that the app can be run as a semi-native app (download from app store,
local/offline storage, etc.) and it makes sense to keep it as small as possible.



### Which Database?

- Postgres - The best relational dabase for
- MongoDB  - Good balance of features, performance and ease of use.
- CouchDB  - Great reliability, master-master replication and simplicity.

Having recently used MongoDB for a client project I'm swaying towards using it
for my next app. But I'm a huge fan of CouchDB.
We need to spend a bit of time investigating features before deciding...



## Mobile

### Phonegap

We are using PhoneGap to *rapidly prototype* "hybrid" mobile applications.

- PhoneGap Tutorial: http://www.smashingmagazine.com/2014/02/11/four-ways-to-build-a-mobile-app-part3-phonegap/

#### What is the Difference between Native and Hybrid Apps?

- Jacob Nielson explains Native vs Hybrid:
http://www.nngroup.com/articles/mobile-native-apps
- Is Hybrid ready? http://venturebeat.com/2013/11/20/html5-vs-native-vs-hybrid-mobile-apps-3500-developers-say-all-three-please/ (the short answer is ***Yes***!)

A good (but *long*) intro tutorial to PhoneGap V.3 was recorded
[@LXJS](http://2013.lxjs.org/guide) in October 2013:
http://phonegap.com/blog/2013/11/12/lxjs-workshop/
