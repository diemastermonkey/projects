# projects
The evolving, loosely-specified, seminal list of things I plan to make, am making, or will never make because they're ridiculous.
In no order.

## [Dial-O-Tron](https://codepen.io/Unhacker/full/VwowxWL) (Javascript/Android?)
This is already well underway! You can try it at [my CodePen](https://codepen.io/Unhacker/full/VwowxWL). 

The whole thing will be documented here on GitHub at [diemastermonkey/dial-o-tron](https://github.com/diemastermonkey/dial-o-tron)

It's like [Doors](https://github.com/diemastermonkey/doors), but instead of a maze it's a local area code full of phone numbers. The user interface is a phone, complete with DTMF dialing and old-school phreaking features.

Discover and interact with NPCs, voicemail, control systems, dead-drops. Collect clues, solve puzzles, acquire mods, gain access - take over the world! Since you've come this far, you can peek at one of its [secret artifacts!](https://pastebin.com/raw/sudbDdHF)

Ultimately, I will wrap this and get it onto Android for the Play store.

## CTF Scene Zine (PDF)
A simple digital zine devoted *only* to the CTF scene itself, at a meta level. Less about the writeups and more about the movers and shakers, competition results, events, trends in the scene, and gossip. Maybe a few writeups. And anonymous letters. 

Keep it short, obscure, and snarky. It should read like the #memes channel of a live CTF.

## Space Pirate Radio (Android/JS prototype)
Actually a variation of my secret "Entroscope" app for Android. Using the same engine, but the navigational data used are the sky coordinates pointed *at* by the player (as opposed to their geolocation). Users will 'tune in' to broadcasts 'coming from' specific areas of the sky, which will rotate in and out of range as the earth rotates and their view of the stars changes. 

In other words, a radio for tuning-into transmissions from space. 

The transmissions will be a mix of procgen'd alien 'language', 'music', advertisements - everything you expect from a radio. And of course approprately strange static between bands. Some tunings can result in just odd or even pleasing 'white/brown/pink noise' effects.

Radio shows should also follow procgen'd schedules, like the NPCs in 'Entroscope'.

## Death Clock (Javascript?)
No, not the band. A simulated 'real-time' representiation of 'all the people dying right now and from what'. I've envisioned various ways of presenting it, but one simple example is of bodies falling from the top of the screen onto growing piles, each of which represents a death from a particular cause. This is easily calculated based on the top causes of death to arrive at "how many die from X per second". I think it will be an interesting way of visualizing where human priorities should be, and of the global state of human survivability. It should also be able to group by region or level of industrialization, because causes of death vary greatly among pre- and post-industrialized nations.

See a working prototype over [on CodePen](https://codepen.io/Unhacker/full/ZEgweWV)


## BrawlOS: Doors + Bash + Suicide-OS (Python/Shell/C?)
Another variant of [Doors](https://github.com/diemastermonkey/doors), except instead of navigating a procgen map, you're navigating your system directories, files, processes, etc - and the environments, NPCs, items, and events are procgen'd from the properties of those things. 

It should look and act like just using Linux, except fantasy version. Maybe hacker themed. 

Also some Suicide-OS in there too, so that typos are fatal. 

## Middleverse (Raspberry Pi, C/Python, Javascript)
A Raspberry Pi represents any detected Bluetooth device as an object or character in animated re-interpretations of reality, using procedural generation to produce consistent 'translations'.

![Middleverse Diagram](gad_rpi_middleverse_01.png)

## Tubehose (Javascript/YouTube API)
I've always wanted to know "what's coming-in to YouTube right now, this moment?" and to see that in real-time: As if the world was pouring out of YouTube's firehose. This is actually pretty easily accomplished with the "YouTube Embedded Player" API, if a bit inelegantly. That actually might be the right approach. 

Or go overboard and write an XScreensaver plugin that does it fancier.

## Hunt (Android)
Yet another ProcGen gadget I've always wanted to make: You're hunting invisible phantoms/agents/etc with your phone. Track them down 'metal detector' style, combat them "in the electromagnetic realm", locate and collect treasure and items, etc. Upgrade your 'detector' (your phone) with buffs to increase scanning range/accuracy/resilience/etc. Could almost just be a re-skinning of Entroscope.

## Flapper Check (Google Chrome Extension)
Perform basic heuristics on a commentor or poster on YouTube, etc, by hovering over them or equivalent. By scoring against common spammer/bot/misinformation attributes (new accounts, fake content, repeated posts, created/managed as a herd/etc) and cross-referencing other sources, arrive at a likelyhood that the source is disingenious/misinformation/fake/automated. 

This really shouldn't be that difficult; Perform some research on the kinds of YouTube commenters that make MAGA statements and you'll see the common elements. Many bot herd accounts are registered years ago, but on the same day. A very thorough analysis of these traits and their scoring will be the trick to making this valuable. 

The name is a reference to Gulliver's Travels.

## unScript 2.0 (Javascript, Processing, or C?)
This is my weird scripting language that acts kinda like assembler, from PalmOS. Yes...PalmOS. It centered on very small, simple scripts with a minimal command set that spawned objects as independent, self-managing threads, with minimal intercommunication capabilities through a 'global whiteboard' approach. Intended for visual animations (such as moving sprite animations).

It was cool and I want to reincarnate it as a Javascript library or something else. 

## Interactive Magazine
Yes, I've been talking about this for years and no, it's not The Internet - it's different. 

Basically I think content should be more interactive. If I'm given a statistic, I want hover over it and have immediate access to source materials, references, tables, calculators appropriate to working with that data, etc. If an article mentions a famous writer, I want to hover over that name and get rabbit holes to everything I am most likely to be wondering about that name, that made me want to hover over it. NO table of data should EVER be presented in any article without accompanying, built-in tools for re-arranging it, sorting it, visualizing it, comparing it to data from other sources, etc. 

I realize this is a little bit Wolfram-type territory, and I think that's why it's Not A Thing yet; Everyone wants you to come 'do this in their thing', when it should just be in the browser and content already.

Maybe this is Browser Plugin territory, or maybe it has to be an App.  This is probably the most ambitious idea on this list.



