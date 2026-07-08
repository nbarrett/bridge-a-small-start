# Bridge: A Small Start

An interactive, single-page introduction to bridge, made for a friend who kept losing the little table maxims ("second hand plays low", "third hand plays high") the moment the next hand started. At the table there's no time to write them down; here they are pinned down for good, each with the reason it works.

**Live site: https://nbarrett.github.io/bridge-a-small-start/**

## What's on the page

- **The quotes wall** - the classic maxims as flip cards: the saying on the front, the *why* on the back, plus an honest "unless..." where each rule bends
- **One trick, played both ways** - a playable proof of "third hand plays high": choose the brave Queen or the careful ten and watch the defenders' trick count change
- **Bidding, decoded** - a tap-the-honours point counter, the 12 / 6 / 25 / 33 ladder, and the one-liner for suit length (bid once: four, again: five, again: six)
- **The plan** - a 3NT deal with a four-step walk-through of counting winners before playing to trick one
- **Entries** - dummy as an island, with the ace drawn as the bridge you must not spend too early
- **The memory chapter** - why nobody remembers 52 cards: count one suit to thirteen
- **Scoring, made small** - why the whole room gallops towards 3NT

## How it's built

One self-contained `index.html`. No build step, no dependencies, no fonts fetched, no tracking. All imagery is inline SVG. Scroll animation is transform/opacity only and switches off for `prefers-reduced-motion`.

The teaching approach borrows from a companion page, [Git is a Media Player](https://nbarrett.github.io/git-is-a-media-player/): start from a mental model the learner already holds (here, the card game Machiavelli - runs and sets) and extend it, rather than starting from jargon.

Bidding numbers follow common UK (Acol) teaching. Where your club or teacher differs, their version wins.
