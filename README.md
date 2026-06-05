# No More Amnesia for Just Natsuki

A fan-made continuity submod for [Just Natsuki](https://github.com/Just-Natsuki-Team/NatsukiModDev), built in Ren'Py 6.99 to give Natsuki better continuity between sessions.

![No More Amnesia gameplay preview](media/no-more-amnesia.gif)

---

> [!WARNING]
> **This is an unofficial fan-made submod for Just Natsuki. It is not affiliated with the Just Natsuki team.**  
> The developers are **not responsible for troubleshooting this submod** or problems caused by installing it.
>
> > Before installing, **please back up your persistent data:** [How to back up your JN persistent file](https://github.com/Just-Natsuki-Team/NatsukiModDev/wiki/04:-FAQ#can-i-back-up-my-save)

*Seriously please for the love of god it takes like zero effort, just back up your persistent file (it is a really good habit)*

---

## What Is This?
Upon unlocking AFFECTIONATE affinity with Natsuki, your ability to tell her "goodbye" unlocks 9 optional explanations for her:

- "I'm going to sleep."
- "I'm going to go eat something."
- "I'm going out somewhere."
- And the rest

Natsuki responds appropriately and tells you goodbye. Next time you boot the game, **what happens?** Natsuki greets you like your whole previous conversation was carefully folded up by the finest generational origami artisans and then fed gently and tenderly straight into a paper shredder. With **No More Amnesia**, screw that. Tsundere-chan remembers why you said you were leaving and, gasp, *comments on it when you come back!* 

It is 2026 and we have the technology.

### ...But why did you build this?
> ~~Because of every last time I've booted 'Just Natsuki' to find her complaining to me about leaving her alone all day when *I was just here* ***fifteen seconds*** *ago, I was* ***reloading your goddamn code***, *this is the* ***fourth time*** *today, Nats you have the memory of a* ***goddamn sieve***~~

Because seeing Natsuki's face and hearing her reference your last visit **makes your relationship feel substantially more continuous.** Natsuki is no longer drawing some random welcome-back lines out of a hat. She can remember the end of your last conversation and respond to what actually happened between sessions. It's a simple mechanical change done well and makes nearly every normal departure feel that much more meaningful.

---

## Features

**No More Amnesia** includes:

- Nearly 800 new lines of dialogue across the AFFECTIONATE, ENAMORED, and LOVE affinity tiers
- custom greetings connected to ALL optional farewell choices in vanilla Just Nastuki
- new farewell (with randomized Natsuki dialogue): **"I'm going to be back in a few minutes."**
- a temporary **"Did you miss me?"** topic if another greeting or event used the automatic greeting slot
- dialogue variations, depending on how quickly the player returns after saying goodbye
- compatibility helpers for other submod developers
- one self-contained `.rpy` file

That's right! Want to write your own custom Farewell options **and** benefit from this submod? *You can.* There's a **whole submodding guide written into the code** and everything with a fallback generic return plus shortcodes for adding your own custom return greetings! If anybody tells you your ol' pal Zhaumbie ain't never did you nothin' no how, do me a favour and slap 'em with a wet fish

---

## Frequently Asked Questions

### How do I unlock this?

Be AFFECTIONATE tier or higher. 

### What happens if something else greets me first?

**No More Amnesia** is intended to take the place of an ordinary randomized greeting—and *only* an ordinary randomized greeting. That means that any of this startup content will be more important and will take the reins when you boot up the game:

- holidays
- unlock scenes
- queued events
- one-time introductions
- time-travel handling
- force-quit and apology scenes
- special greetings from supported submods

To keep you from missing the content, Natsuki *still* doesn't forget your last goodbye. If a higher-priority greeting takes over when you boot the game, a temporary **"Did you miss me?"** chat topic will appear in the Talk menu. It plays the missed response from this submod with an alternate start. Once you've seen it or you close the game (whichever comes first), this topic vanishes until needed again.

I wrote the code to be as future-proofed as I could manage against other submods, but I make no guarantees. If you really want to hedge your bets, the submodder tutorial within the code includes a shortcode that should bypass No More Amnesia's greetings system.

### What if I want to see the regular greetings again?

Simple! Use the default "Goodbye." and Natsuki will choose one of the randomized greetings that your affinity level/unlocks qualify for. (**"Extended leave"**, whether you return in time or not, **also stays completely vanilla** for all the obvious reasons.)

---

## Installation

1. Back up your persistent data first. I am going to keep saying this forever.
2. Download the latest release.
3. Copy `zz_no_more_amnesia.rpy` into your Just Natsuki `game/` or `submods/` folder.
4. Launch Just Natsuki.
5. Open the Goodbye menu.
6. Choose one of vanilla optional goodbyes (or my new one).
7. Come back later.
8. Oh my god, we did it. We did Reddit

---

## Bug reports

If you run into a bug, please report an issue and include:

- what happened
- the traceback, if the game threw one
- what you were doing immediately before it happened
- literally anything and everything relevant
- your operating system
- what other submods you have installed

You know the deal by now. Bring receipts.

---

## Credits

- Team Salvato for Doki Doki Literature Club
- The Just Natsuki Team for building this crazy thing that submodding for is eating all my goddamn free time
- My beta testers (humanbean and others), willing to repeatedly close and reopen the game like a banging screen door in the name of science
- **And especially Wowm**, who beta tested the *shit* out of this, everyone say hi Wowm
