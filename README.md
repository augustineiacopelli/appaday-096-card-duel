# AppADay 096: Card Duel

**A two-player, pass-and-play creature card battle. Send out a creature, trade blows, and take all six of the other trainer's stars.**

**Live:** https://augustineiacopelli.github.io/appaday-096-card-duel/

**Portfolio:** https://augustineiacopelli.github.io/appaday/

Card Duel is a phone-sized card battler built for two kids sharing one device. Each creature carries an attack number and a health number and nothing else, so a six-year-old can read a card in a second and still make a real decision with it. There are no accounts, no shuffling of physical cards, no rules the players have to hold in their heads between turns, and nothing to install.

## How it plays

Two players enter their names and the first turn begins behind a curtain that hides the hand from anyone else in the room. On a turn you draw one card, send out one creature, and then attack with any creature that is awake. A creature that arrives this turn takes a nap and wakes up on your next turn, which keeps anyone from dropping a fresh creature and swinging with it immediately.

Attacking is two taps. Tap your creature, then tap what it should hit. Both creatures deal their attack number to each other at the same moment, so a big attacker with thin health can win the exchange and still fall over. Any creature at zero health is knocked out, and every knockout takes one star off the trainer who owned it, which means a trade costs both sides a star. If the other side has no creatures out at all, your creature walks past and takes a star straight from the trainer. Six stars ends the duel.

Your side holds up to three creatures, your hand holds up to five cards, and the deck of twelve creatures reshuffles when it runs dry, so a game never stalls out for want of cards. The curtain returns between every turn.

## The creatures

Twelve creatures share one deck list: Pip 3/3, Bramble 2/6, Zappy 4/1, Shellback 1/8, Cinder 5/4, Moonowl 3/4, Nibbles 2/2, Snapper 4/3, Frostwolf 5/2, Bubbles 2/5, Sparkfin 3/2, and Thundercat 4/4. Both players draw from the same list in a different order, so the two sides are even and the shape of the game comes from what shows up when.

## Built with

One file of vanilla HTML, CSS, and JavaScript. No frameworks, no build step, no dependencies beyond Google Fonts. Titan One and Nunito set the type. The attack, knockout, and star sounds are generated with the Web Audio API and can be switched off. Names, running win tally, and the sound setting are kept in `localStorage`, which is wrapped so the file also opens straight off disk.

## Part of AppADay

Day 096 of [AppADay](https://augustineiacopelli.github.io/appaday/), a project by Augustine Iacopelli to design, build, and publish one complete web app every single day.

Category: Games (G)
