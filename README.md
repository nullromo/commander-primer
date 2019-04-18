# Commander Primer

An introduction to deckbuilding for the Magic: The Gathering (MTG) Commander format by Kyle Kovacs

### How to use this guide

This guide is meant for people who already know how to play Magic, but don't know anything about Commander. Throughout the guide, concepts will be introduced and explained, and any cards that are referenced will show up as images. There is a glossary of terms at the bottom. By the end of the guide, you should have a pretty clear idea of what Commander is all about and how to build a deck. My recommendation is to read the entire guide before starting to build your deck, but if you can't wait, then following along will work as well.

## What is commander?

There are many different ways to play MTG, called **formats**. A format is defined by a specific set of deckbuilding rules. Each official format contains rules about how many cards are allowed to be in a deck, which cards are allowed to be played, how many players are in a game, how mulligans work, and sometimes a few other rules.

The main official formats are Vintage, Legacy, Modern, Pauper, Standard, Commander, Booster Draft, Sealed, and Brawl. Each of these formats has its own set of legal cards and its own restrictions on deck size. This article will not cover the details of the differences between the formats, but this highlights the fact that there are many ways to play MTG, each with its own set of specific rules and metagames.

So what is the Commander format? Let's take a look at the rules in detail.

### Commander deckbuilding rules

The deckbuilding rules are the following:

- Decks contain exactly 100 cards
- Decks are singleton (each deck can only contain one copy of a given card)
- One card in the deck is designated as the "commander" of the deck
  - The commander must be a legendary creature
- All the non-commander cards in the deck must fall under the "color identity" of the commander.
  - Color identity is determined by the mana symbols on the card in either the card's cost or its rules text. For example, the card Ancient Grudge is red, but its color identity is red and green. Hybrid mana symbols, like those seen in Dovescape count as both colors when determining the card's color and when determining its color identity. Hence, Dovescape is blue and white, and its color identity is blue and white.

    > Note that mana symbols in reminder text do not count as mana symbols in a card's rules text. Example: the _Extort_ mechanic, as seen in Blind Obedience does not change a card's color identity. Blind Obedience is white, and its color identity is white.

  - Of course, the cards in the deck do not have to exactly match the color identity of the commander. So if a deck's commander were blue, red, and black, then the deck could have cards that are just blue, cards that are red and black, cards that are just black, etc.
  
![Ancient Grudge][Ancient Grudge] | ![Dovescape][Dovescape] | ![Blind Obedience][Blind Obedience] |
|-|-|-|

Your commander is usually what gives your deck its flavor. Most decks are structured such that the cards all interact well with the abilities of the deck's commander. Later on in the guide, we will explore what this means and how it works.

In addition to the deckbuilding rules, there are some in-game rules specific to Commander.

### Commaner game rules

The relevant game rules are the following:

- You may not have known it, but in every game of MTG there is a zone called the _command zone_. This is where commanders live at the start of the game, and it's where they normally return to when they die.

  > Note, the command zone is also used for other things with which you may be familiar, such as planeswalker emblems and conspiracies.

- You may cast your commander from the command zone as if it were in your hand.
- Any time a commander you own would change zones, you may have it go to the command zone instead of whatever zone it would have gone to. This means, for example, that if your commander is on the battlefield and it is destroyed, you may put it in the command zone instead of in your graveyard. Likewise, if your commander is in your graveyard (perhaps because you chose not to return it to the command zone after it died) and it would be exiled, you may choose to return it to the command zone instead.
  - Keep in mind that a commander that returns to the command zone when it is destroyed doesn't actually die. Since moving to the command zone is a replacement effect, the commander never enters the graveyard, and so never actually triggers any "whenever a creature dies..."-type abilities.
- Every time you cast your commander from the command zone, it costs 2 more generic mana to cast for each time you have cast it from the command zone that game.
- If a player is dealt 21 damage (over half their starting life total) by a single commander, that player loses the game as a state-based action.
  - This so-called "commander damage" is tracked across the whole game, even if the damage-dealing commander leaves and re-enters the battlefield many times.
  - Noncombat damage also counts as commander damage.
- Players start at 40 life
- Each player gets 1 free mulligan (you can draw back up to 7 after your first mulligan, then 6 after your second, etc.)
- The player who goes first does not skip their first draw step

Commander is best played with 4 players at a time. If a player loses the game, all cards owned by that player cease to exist (from the game's perspective) and the game continues on with the remaining players. If a player wins the game, the game ends and all other players lose.

### Why Commander?

A big part of what makes the format fun is the in-game politics. Some games play out relatively evenly, while other games see one player gain an early advantage and get teamed up on. The fun of commander is that even though your deck has the same cards in it, no two games play out the same way. Often in formats like Standard, which has a very narrow metagame, matchups can be deterministic and the same matchup will often play out the same way. This does not mean that Standard is boring, but it's definitely a different feeling and Commander has such a wide variety of things going on that it never seems to get boring.


> **History Note**: Commander is often called Elder Dragon Highlander (EDH). This is a reference to 2 things. First, when Commander was invented, the only legal commanders were the five Elder Dragons, pictured below. Second, the movie _Highlander_ popularaized the phrase "there can only be one," which refers here to the singleton nature of Commander.
>
> | ![Arcades Sabboth][Arcades Sabboth] | ![Chromium][Chromium] | ![Nicol Bolas][Nicol Bolas] | ![Vaevictis Asmadi][Vaevictis Asmadi] | ![Palladia-Mors][Palladia-Mors] |
> |-|-|-|-|-|

### So, what is Commander?

Commander is **_THE_** casual format. Commander is where you can experiment. Your deck can be whatever you want it to be. You can play weird, random cards printed in 1998 that aren't good enough for Modern. Also, the decks are a lot less consistent in general, because your deck is 100 cards instead of 60, and you only have 1 copy of each. This means that it's a lot less about curving out in the first few turns. It's a lot harder to deprive 3 opponents of resources. It's much more difficult to kill people on turn 3 with simple combat damage. The tight, competative style of other constructed formats is broken down and replaced with a relaxed attitude of fun for the sake of fun.

Now that we've covered what Commander is and how it works, it's time (finally!) to talk about building a deck.

## How to build your deck

This section will talk about how to build your commander deck, from how to start, to where to look for inspiration, to what things to do or avoid.

### Starting out

[Gatherer] is the first website that we will introduce. Gatherer is the official MTG card database, and it has some powerful search tools built into it. Let's take a look at what you can do with it.

> **Note**: Gatherer has all the up-to-date official errata information for every card ever printed. The _official_ rules text of cards is not what is printed on the card, but what it says in Gatherer. This is the official policy, because sometimes the rules of the game change. For some examples, take a look at the cards in the table below. Ancestral Recall used to say "Draw 3 cards or force opponent to draw 3 cards," but it has been changed to say "Target player draws 3 cards" in accordance with the new templating standards. According to some old version of the rules, these things called "mono artifacts" had to be tapped to be used. They later realized that just templating the mono artifacts as regular artifacts with activated abilities made more sense. Glasses of Urza is a great example (see below).
>
> | Old Ancestral Recall | New Ancestral Recall | Old Glasses of Urza | New Glasses of Urza |
> |:-:|:-:|:-:|:-:|
> | ![Ancestral Recall Beta][Ancestral Recall Beta] | ![Ancestral Recall][Ancestral Recall] | ![Glasses of Urza Beta][Glasses of Urza Beta] | ![Glasses of Urza][Glasses of Urza] |
>
> Often times the rules change and cards are not re-printed. Things like "when this creature comes into play" have been changed to "when this creature enters the battlefield." So if you're ever confused about a wording, go to Gatherer to see the official wording updated in accordance with the current rules. Many cards also have rules clarifications detailed in their Gatherer page. Look towards the bottom of [this page][Liliana Gatherer] under "Rulings" for an example.

So what do we do with Gatherer? First of all, we can search for a given type of spell. Let's say we are interested in seeing if there's a way to couter spells outside of blue. In the Gatherer search page, enter `AND "counter target" spell` into the Rules Text filter, and `NOT blue` in the Colors filter. Use the Add buttons to add the search criteria. [This link][non-blue counters] is what you should see. I recommend switching the view to "Visual Spoiler" instead of "Standard." There are some screenshots below to help out.

| Search term entry. Quotes tell the database to use the exact order of words; unquoted terms can show up anywhere on the card | Search criteria are shown to the right. Press the Search button to search |
|-|-|
| ![non-blue counters search][non-blue counters search] | ![non-blue counters terms][non-blue counters terms] |

Notice that a lot of the cards in these results actually do contain blue mana symbols becuase of activated abilities and thanks to the _Devoid_ mechanic. In the next example we will look at one way to mitigate these false positives.

You can ask Gatherer for all kinds of things. Let's say we are building a deck with a green and white commander and we want to find some lands that tap for both green and white mana. We can use the following search criteria:

| {W} is the white mana symbol and {G} is the green mana symbol | We also need to exclude the other mana symbols in order to find legal cards | We want a land that contains these symbols in its rules text |
|-|-|-|
| ![green white lands search][green white lands search] | ![green white lands exclude][green white lands exclude] | ![green white lands terms][green white lands terms] |

Make sure to exclude lands that contain the blue, red, and black mana symbols, becuase those would be illegal in a deck with a commander whose color identity is only green and white. You should end up at [this page][green white lands], which has 30 results. Wow, that's a lot of green-white dual lands!

> **NOTE**: keep in mind that there may be other non-obvious factors. In the example above, we do not see lands like Command Tower, Cascading Cataracts, Painted Bluffs, or Gemstone Mine.
>
> | Command Tower | Gemstone Mine | Cascading Cataracts | Painted Bluffs |
> |-|-|-|-|
> | ![Command Tower][Command Tower] | ![Gemstone Mine][Gemstone Mine] | ![Cascading Cataracts][Cascading Cataracts] | ![Painted Bluffs][Painted Bluffs] |


Now that we know how to find cards meeting specific needs, let's talk about starting a deck. There are a few approaches to start building a commander deck, and the next few sections will talk about each method.

#### Find a commander that you like

Look at some legendary creatures. If you search Gatherer for all legendary creatures, you will find that there are many hundreds of options to choose from. You may not have time to read all of them, but maybe scroll through and browse around. Ask your friends. Look online. The point is to try and find a commander that grabs your attention. A good commander is one that you see potential in. There are some legendary creatures (see below) that just don't really do anything; these do not make good commanders.

| Barktooth Warbeard | Gabriel Angelfire | Gallowbraid | Sir Shandlar of Eberyn |
|-|-|-|-|
| ![Barktooth Warbeard][Barktooth Warbeard] | ![Gabriel Angelfire][Gabriel Angelfire] | ![Gallowbraid][Gallowbraid] | ![Sir Shandlar of Eberyn][Sir Shandlar of Eberyn] | |

If you want to build a deck around a particular commander that has no abilities other than being a 6/5 for 7 mana, then nobody is going to stop you... but it probably won't feel like a commander deck. You want your deck to focus around the commander's abilities (you usually don't want your deck to rely entirely on your commander, but we'll get into that more later on), so it is important to have a playstyle in mind when you think about the commander. For example, look at the table below. Each other these commanders has a pretty obvious playstyle that works well.

| Uril, the Miststalker | Sliver Legion | Sram, Senior Edificer |
|-|-|-|
| ![Uril, the Miststalker][Uril, the Miststalker] | ![Sliver Legion][Sliver Legion] | ![Sram, Senior Edificer][Sram, Senior Edificer] |
| Uril wants a deck that focuses on creature auras | Sliver Legion wants a deck that focuses on playing lots of slivers | Sram wants a deck centered around auras, equipments, and vehicles |

So go exploring and see what catches your fancy. Sometimes it can be interesting to play a commander the non-obvious way. For example, you could play Sliver Legion as your commander, have no slivers in the deck, but play cards that turn your creatures into slivers. Every commander brings something to the table &mdash; you just have to decide what to eat.

#### Pick a style that you like

Another good way to find a direction for your deck is to take the opposite approach. Start with your favorite thing to do in Magic. Maybe you really like creatures with flying and you want to make a fliers deck. Maybe you like playing artifacts. Maybe your favorite thing is reanimating creatures from the graveyard. Whatever it is that you like, you probably already know some cards that could potentially fit in your deck. All you need to do is find a commander to facilitate things.

At this stage, it might be best to just go to Google and look for "popular reanimator commanders" or "spellslinger commanders." You can also search on Gatherer for legendary creatures that have certain keywords in them, like "instant or sorcery," "double strike," "return to owner's hand," or "discard." Finding a commander that facilitates your style of play can be tricky, but whatever you want to do, there is probably a commander out there that can support it.

#### Work with what you've got

One final way to come up with a commander and a direction for your deck is to just look through the collection of cards that you probably have lying around. Collect up all your legendary creatures and take a look at what they do. Find some cards you already own that you think are cool and start grouping them up together. Inspiration comes from getting your hands dirty, so to speak, so just get in there and ideas will come to you. Using cards you already own can save you money and it can be satisfying to know that you built your deck up from what you had.

### Remember your goal: to have fun

Now that you have a starting point, it's important to remember a few things. When you play Commander, your goal is to have fun. Different people think of this in different ways, but let's talk about how to maximize fun from a couple different angles.

#### Build a fun deck

- don't play combo
- don't troll (warp world)
- nonlinear is better

#### Play a fun game

And when you play
- threat assessment
- no spite
- don't be afraid to kill people if it advances you
- politics


### Deckbuilding steps

Now that you have a starting point, it's time to start building the deck! Commander is sometimes called "battle-cruiser Magic" because of the fact that it is slower than 1-on-1, and therefore allows for more big, flashy plays. In Legacy, for example, casting a big 7-mana creature for its full cost is almost always impossible &mdash; you may not even survive long enough to play 7 lands. In Commander, it's much more likely that you'll survive that long because there's a bunch of other things going on. So the pace of the game is a bit slower, allowing you to play some more expensive cards. That being said, you can't just shove 99 huge cards into a deck and hope to have any fun. We're going to talk about how to balance the deck properly.

Keep in mind, your first deck may not be that good. After all, if you haven't played Commander a lot, you probably won't know exactly how it goes. This is okay, because your deck can evolve over time and as you play more and see more decks, you will discover more and more about what makes a good deck.

The following steps will guide you through the deckbuilding process. Keep in mind that they don't necessarily apply in order, but that it's all a creative process and you can always change things around.

Let's get started.

#### Step 1: Think about it

- think about it. If you picked a commander, what cards go with it? If you picked a style, what are the best cards? Use gatherer

#### Step 2: Start a decklist

- make decklist on MTGGoldfish
- add cards you already have/like

#### Step 3: Get some inspiration

- go on edhrec for inspiration
- add cards you like from there

#### Step 4: Nitty-gritty searches

- as you go, you find things and use gatherer

> **Remember the banlist!** There are certain

#### Step 5: Staples

What to include?
- necessary parts of a deck
- staples

#### Step 6: Control yourself

- some meme cards okay, but not too many

#### Step 7: Organization

Collection phase over
- now go on deckstats
- make categories
- think about ratios
- make sure you have the right amount of stuff

#### Step 8: Trim, trim, trim

You will probably have a lot more than 100 cards picked out by now. That's okay, but you're going to have to trim it down. Think hard about 

### Other things to keep in mind

Other things to keep in mind
- budget
- theme/challenge

## Time to buy the cards

Buy the cards
- copy decklist
- select versions in cart optimizer
- optimize 3 times
- select cart
- order
- make sure to write reviews as they come in
- if an order is wrong, give 1 star and they will accommodate, then change after
- anecdote

## Time to play the game!

Time to play
- good table
- playmat
- sleeves
- players

## Glossary of terms

MTG
format
commander




[//]: # (card images)
[Ancient Grudge]: https://img.scryfall.com/cards/large/en/mm3/88.jpg?1517813031 "Ancient Grudge is red, but its color identity is red and green"
[Dovescape]: https://img.scryfall.com/cards/large/en/dis/143.jpg?1517813031 "Dovescape is blue and white, and its color identity is blue and white"
[Blind Obedience]: https://img.scryfall.com/cards/large/en/c17/57.jpg?1517813031 "Blind Obedience is white, and its color identity is white"
[Arcades Sabboth]: https://img.scryfall.com/cards/large/en/me3/142.jpg?1517813031 "The five Elder Dragons"
[Chromium]: https://img.scryfall.com/cards/large/en/me3/147.jpg?1517813031 "The five Elder Dragons"
[Nicol Bolas]: https://img.scryfall.com/cards/large/en/me3/163.jpg?1517813031 "The five Elder Dragons"
[Vaevictis Asmadi]: https://img.scryfall.com/cards/large/en/me3/185.jpg?1517813031 "The five Elder Dragons"
[Palladia-Mors]: https://img.scryfall.com/cards/large/en/me3/164.jpg?1517813031 "The five Elder Dragons"
[Ancestral Recall Beta]: https://img.scryfall.com/cards/large/en/leb/48.jpg?1525122970 "Old wording of Ancestral Recall"
[Ancestral Recall]: https://img.scryfall.com/cards/large/en/ovnt/2005.jpg?1523193155 "New wording of Ancestral Recall"
[Glasses of Urza Beta]: https://img.scryfall.com/cards/large/en/leb/246.jpg?1525123591 "Old printing of Glasses of Urza"
[Glasses of Urza]: https://img.scryfall.com/cards/large/en/me4/203.jpg?1517813031 "New printing of Glasses of Urza"
[Command Tower]: https://img.scryfall.com/cards/large/en/c18/240.jpg?1535505276 "Command Tower"
[Gemstone Mine]: https://img.scryfall.com/cards/large/en/tsb/119.jpg?1517813031 "Gemstone Mine"
[Cascading Cataracts]: https://img.scryfall.com/cards/large/front/7/7/778739db-4431-4e58-91de-d2619aeef3ce.jpg?1543676358 "Cascading Cataracts"
[Painted Bluffs]: https://img.scryfall.com/cards/large/front/8/b/8b373131-2a1d-4710-8a11-c1b366a174d4.jpg?1543676399 "Painted Bluffs"
[Barktooth Warbeard]: https://img.scryfall.com/cards/large/en/me3/144.jpg?1517813031 "Barktooth Warbeard"
[Gabriel Angelfire]: https://img.scryfall.com/cards/large/en/me3/148.jpg?1517813031 "Gabriel Angelfire"
[Gallowbraid]: https://img.scryfall.com/cards/large/en/wth/70.jpg?1517813031 "Gallowbraid"
[Sir Shandlar of Eberyn]: https://img.scryfall.com/cards/large/en/me3/174.jpg?1517813031 "Sir Shandlar of Eberyn"
[Uril, the Miststalker]: https://img.scryfall.com/cards/large/en/arb/124.jpg?1517813031 "Uril, the Miststalker"
[Sliver Legion]: https://img.scryfall.com/cards/large/en/fut/158.jpg?1517813031 "Sliver Legion"
[Sram, Senior Edificer]: https://img.scryfall.com/cards/large/front/1/b/1b323e2c-59dd-4d70-9a48-b10f807bb818.jpg?1543698649 "Sram, Senior Edificer"

[//]: # (website links)
[Gatherer]: https://gatherer.wizards.com/Pages/Advanced.aspx "Gatherer"

[//]: # (examples and screenshots)
[Liliana Gatherer]: https://gatherer.wizards.com/Pages/Card/Details.aspx?multiverseid=398441 "Liliana, Heretical Healer Gatherer page"
[non-blue counters]: https://gatherer.wizards.com/Pages/Search/Default.aspx?output=spoiler&method=visual&action=advanced&text=+%5b%22counter+target%22%5d+%5bspell%5d&color=+!%5bU%5d "non-blue counterspells"
[non-blue counters search]: /images/non-blue-counters-search.png "Search terms for non-blue counterspells"
[non-blue counters terms]: /images/non-blue-counters-terms.png "Search terms for non-blue counterspells"
[green white lands search]: /images/green-white-lands-search.png "Search terms for green and white lands"
[green white lands terms]: /images/green-white-lands-terms.png "Search terms for green and white lands"
[green white lands exclude]: /images/green-white-lands-exclude.png "Search terms for green and white lands"
[green white lands]: https://gatherer.wizards.com/Pages/Search/Default.aspx?output=spoiler&method=visual&action=advanced&text=+%5b%7bG%7d%5d+%5b%7bW%7d%5d+!%5b%7bB%7d%5d+!%5b%7bR%7d%5d+!%5b%7bU%7d%5d&type=+%5bland%5d "Search for green and white lands"
