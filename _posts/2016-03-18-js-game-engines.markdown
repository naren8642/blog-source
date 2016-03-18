---
layout: post
title:  "Game Engines for the Web"
date:   2016-03-13 23:05:55
categories: web, game
location: Houston, TX
tags: web game
---

My son likes to play some of the casual games on Facebook. I am not a big fan of the ads he ends up watching to play the game.
I don't know if that bothers me more or less than the fact these games are made using flash.

So I figured what if I could make some of these simple games - without ads, and a lot less gaudy.

I started my search for game engines [here](http://buildnewgames.com/game-engine-comparison/). This was such a well written article
I was ready to believe whatever they were going to say... but I also looked at this [comparison tool](https://html5gameengine.com/).

### [CraftyJS](http://craftyjs.com/)

Best thing about Crafty seems to be its component oriented design. The Build New Games link above describes it well.
This might actually be a good place for me to start. Need to compare this with CreateJS.

### LimeJS

From the Build New Games review

> Lime is a very “safe” choice in that it will for sure be able to handle just about any 2D game you could throw at it.
> But Lime is also a bit tedious at times, and also sometimes very general.
> Lime can be seen more as a “game framework” from which you could build specific game engines on top of.
> One area that Lime really excels is its node graph. Just about everything in Lime derives from the base Node class, and nodes can contain child nodes.
> This allows you to build complicated entities that can have many children, yet address them from a high level.
> For example you might add a character node as a child of a vehicle node it is riding in.
> The character node might also have an armor node that he is wearing.
> Whenever the parent vehicle node moves, the character and his armor will move right along with it, making them act as a cohesive whole.

### [MelonJS](http://melonjs.org/)

Another good looking open source engine, with physics support. Check out [this tutorial](http://melonjs.github.io/tutorial-space-invaders/)
for creating a space invaders clone. Melon also seems to have more recent activity than some of the others.

### [ImpactJS](http://impactjs.com/)

Mainly suited for 2D Platformers and action games. Plus it is not free. So maybe this is not going to be the first engine I try.

### [CreateJS](http://www.createjs.com)

It seems like these libraries give you drawing tools, but the interactions have to be provided by the developer.
This library may be great for animated websites, I think!

Wild Kratts games with CreateJS - [http://pbskids.org/wildkratts/games/](http://pbskids.org/wildkratts/games/)

## With AngularJS

Not much on details here (which isn't a bad thing), but a good inspiration for connecting up a game engine with Angular.

[https://www.toptal.com/web/making-html5-canvas-based-game-with-angularjs-and-createjs](https://www.toptal.com/web/making-html5-canvas-based-game-with-angularjs-and-createjs)

### Not gonna work out

[Egret](http://www.egret.com/)
