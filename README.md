# Castle Battle Operations Plan

Single-page operations plan for the King's Castle battle during **Kingdom of Power** (KvK) in
[Kingshot](https://kingshot.game). Built for the WPK and KVK alliances.

Written for an **all-out castle battle**: no diplomatic agreements with the opposing kingdom beyond
what the game itself enforces, and open attacks on player cities during the castle window.

## What it is

A reference card meant to be read on a phone, in a hurry, during a five hour fight. Not a guide.
Every member should be able to find their own job and the current phase in a few seconds.

- Live phase tracker. Enter the castle open time once and every phase converts to your local time.
- Turret ring diagram, because turrets fire *at* whoever holds the castle.
- Joiner preset groups, so the alliance stops stacking four of the same hero.
- Honest list of the mechanics this plan assumes but nobody has confirmed in game.

## Build

Single self-contained `index.html`. No build step, no dependencies, no framework. Inline CSS and JS.
Google Translate flag switcher covering 18 languages, since the alliance is not all English speaking.

Local preview:

```sh
python3 -m http.server 8791
# http://localhost:8791/
```

## Access

Open, no login. The page carries `noindex, nofollow, noarchive` so it stays out of search results, but
anyone with the link can read it. Nothing here is treated as secret.

## Sources and accuracy

Mechanics come from the official Century Games Kingshot help pages plus community testing, and the
page marks the difference. Several widely circulated guide sites state the KvK castle rule as three
consecutive hours out of six, which contradicts the official help page. The official rule is a **five
hour window with a 2.5 consecutive hour instant win**, otherwise longest cumulative occupation time.

Where sources disagree, the page says so rather than picking one and sounding confident. If the game
contradicts this page, the game is right.

## Series

Part of a set of Kingshot pages:

- [How to Gear](https://texnottexas.github.io/kingshot-gear-guide/)
- [How 2 Garrison](https://texnottexas.github.io/kingshot-garrison/)
- [How 2 Bear Hunt](https://texnottexas.github.io/kingshot-bear-hunt/)
- [Bear Hunt Rally Capacity](https://texnottexas.github.io/kingshot-rally-capacity/)

Put together by Tex.
