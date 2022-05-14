# STIBle / MIVBle

STIBle / MIVBle is a WorLdle clone, except that you don't guess a country, but
a stop in the STIB's (Brussels' public transport company) network.

## Requirements

+ [npm](https://nodejs.org)

## Installation

Clone the repository.

```bash
git clone https://www.github.com/piracope/STIBle.git
```

Install the necessary dependencies.

```bash
npm install
```

## Usage

If you don't have a PORT defined in your environment, it will run on port 3000.

If you're running it locally, first run the server with this command : 

```bash
npm start
```
You should see some weird stuff appear, then "Listening on port 3000" (or whatever
port you're listening to). Btw that weird stuff is the secret stop generated which
is useful for ~~cheating~~ debugging.
Then, open your browser to [http://localhost:3000](http://localhost:3000). And then, do some heavy gaming 😎.

## Features

+ Generates a new secret stop to guess every midnight (midnight being your system's
midnight)

+ You can switch from French to Dutch and everything gets translated accordingly

+ uhhh like play it i guess, i mean it's yet another wordle clone so like play it
and find out

+ There's a funny 404 page

## Contributing

**TL;DR** I made this while not knowing anything about networking so please
notify me of any security flaw.

I discovered how to make HTTP requests, how to make an API, how to make a
(somewhat) MVC webapp in like, two sleepless nights. I have not yet seen this at 
school, and as such, have valued the "if it works it works" mindset rather
than valuing security. I still did my best tho, but this thing surely has
enough security flaws to pay for the living expenses of a cybersecurity expert
for at least two days (the codebase is pretty small (1100+ LOC)).

I don't have to deal with storing user info or anything like that, so there's
nothing much to compromise... I think. Anyways, if you notice a security risk,
please, please tell me/PR me something about it.

Oh yeah and added functionality would be funny ig.

## Trivia

> Why did you do this ?

This is the story of three people :
[@REXAG0NE](https://www.twitter.com/rexag0ne) (REXA)
[@Hatsenaa](https://www.twitter.com/hatsenaa) (Hatsena)
and me.

So one day, the STIB Twitter account tweets a rebus, where you had to guess the
name of the stop. Hatsena replied with something in the lines of "lmao imagine
a STIB wordle", to which REXA replied "that'd be cool, but we'd need a dev". And
after posting an adequately timed "hi", I slaved my nights away to make this !

Honestly it was pretty fun, I learned a lot of things doing this so worth it.

> Why the 95 line as logo ?

Because it's the best one.

> No it's not ! What about the 71 ?

I know who you are, where you are, and I am approaching rapidly. Start running.

## Authors and acknowledgments

Well obviously REXA and Hatsena for the initial idea. I've picked a lot of
concepts from @teuteuf's WORLDLE, which was also very inspired from Josh Wardle's Wordle.

This is hosted on REXA's Elitios network (well, not currently, but soon).

The inner functionment was inspired by cémantix's source code, which gave me the
idea of doing a front-end and a back-end for the first time.

The data (stops, lines, ...) required to make the datasets that the game
runs on came from the [STIB's API](https://opendata.stib-mivb.be/store/data).

## License

Haven't decided on that yet :/