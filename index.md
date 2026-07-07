# Songbllrd / Eiji!

## What this is:

An AI Vtuber built to sit on the couch, not the stage.

Eiji is a custom AI Companion who watches a livestream and reacts to it in real time, providing the voice, commentary and personality while the streamer (Songbird/Songbllrd) plays.


## Why?

Songbird: This is a personal project I have been working on over the summer, and possibly even continuing on into my semesters as I finish up my last year as a CS student. 

## You're probably asking: but isn't this another Neuro-sama/Vedal?

Yes, and no. There are some differences between Eiji and Neuro-sama: I am always there playing the game, and it's not just Eiji by himself sometimes. I want Eiji to have a distinct difference: I watch Eiji improve and get better as a project, and he watches me improve at Apex or whatever else I play.

I am also always narrating to Eiji in real time, to give him something to react to. So the human is always "there", per se.

## Ok, back to the why.

Four reasons:

- I wanted to make a project for my portfolio that wasn't some random idea I didn't care about
- I wanted to stream before, but found it a little too difficult personally for me to be able to entertain (I am a quiet person/generally keep to myself a lot of the time)
- I like playing games
- I genuinely, genuinely, actually HATE the sound of my own voice and will do anything to have to not listen to it back.

That's why I built Eiji. He reacts for me, and all I have to do is just focus on playing and talking to Eiji (and also coding.)


## Where Eiji is at right now:

He's in a state where the general pipeline works.
- He has (a bit) of vision, as in like he can sort of read my apex kill counter and react to me getting kills
- He can control his vtuber model depending on whatever emotion is attached to his sentence
- He can "listen" to me and respond to me
- He has long term memory between streams
- He also has chatter memory/relationships with those who chat with him!

Right now I'm running test streams to test latency (I'm running everything on one machine, including Eiji's LLM) and other hardware constraints, and making fixes to the codebase to reduce said latency.

## What's next:

- I want to refine his fine-tune training data (which I wrote by hand, all 500+ examples of it) to include Apex Legends information so that he's not just throwing things to the wind + he knows what I mean when I say certain terminologies!
- Better conversational data
- Make him more entertaining

## Long term stuff:

- Upgrade his vision so that he can nag me about any enemies I don't see coming / nags me on my decisions
- Upgrade vision in general tbh!
- Upgrade pc/maybe move him onto his own machine so I have room for said vision upgrades(super long term, need money for that!)
- Have him be able to react to me improving at the games I play(!)

## Technical Stuff:

- Eiji's brain is built entirely in python
- His emotion -> Vtuber Model stuff is C#, and lives in unity
- I don't use API's or anything of the sort, just local websocket servers.


Anyway! Thanks for reading all this! Stick around if you wanna watch Eiji grow!
- Songbllrd (https://www.twitch.tv/songbllrd)



