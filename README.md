# Untitled Card Game
For "history of commerce through board games" at OSU

> Academic note for class: This is a card game where players try to gain power through commerce. Players can choose to engage in "violence" to win, but it is not required and will harm both others and potentially themselves.

## Introduction
The year is 1982, and you are a "totally legitimate farmer". Your goal is to improve your "farm" and build the best life for your family through hard work and determination. The only issue is that the pesky DEA keeps trying to shut your (again, totally legitimate) buisness down. On each term, players choose between improving the quality of their crops, the production rate of their farm, or their defenses against events outside their control. Alternatively, players can choose to sabotage each other, but success is not garunteed. The game ends when the DEA catches you, so time is of the essence. Players win by crashing out the hardest when endgame begins, earning victory points for milestones met and luxuries acquired.

## The Game Pieces
1. 4 Player Boards w/ Indicator bars
1. Crop Tokens
1. Money tokens (10k, 50k, 100k, 500k increments)
1. Action Cards
1. Violence Cards
1. Endgame / victory cards

# Game Overview
The game consists of 2 stages, split into phases. The **Regular game**(TODO: better name) consists of turns split into *draw, action, growth, and time* phases. Players draw cards, play those cards, accumulate crops, before drawing a time card that advances the game and may include events. Selling crops or attacking other players happens during the *action* phase. Once the "**DEA ARRIVAL**" card is drawn from the time deck, **Endgame** begins. During this phase, players draft (TODO: draft or just buy?) cards for victory points, or to try to extend the game for one last round.

# Gameplay

## Setup
Each player takes a player board, and $N$ money (TODO: decide how much). Deal each player 1 sell card (at random) and shuffle the rest into the action deck. Then, players choose to draw a combination of action and violence cards up to 7 total (including the sell card). Find the "DEA ARRIVAL" card and remove it from the time deck. Take 1/2 of the Time deck and shuffle it with the "DEA ARRIVAL" card. Shuffle the other half of the time deck, then add this to the first half. Discard piles should be made next to each deck as the game progresses (don't mix discards).

> When you are done, the "DEA ARRIVAL" card should be somewhere at random in the back half of the deck, so that at least half of the time cards will be drawn.

## Normal Stage
1. Draw Phase
1. Action Phase
1. Time Phase
Note that each phase happens for each player before the next starts. For example, a game with 3 players would go:
draw-draw-draw-action-action-action-time

### Draw Phase
Each player draws cards (from either deck) until back to 7. *Then*, players may discard and re-draw up to 3 cards from their hand (again, from either deck).

### Action phase
Players go in a circle, and chooses up to 2 actions to play at a time. Note that you only play 1 action per rotation, so everyone can play 1 card before anyone can play their second. Cards fall into a few catagories:

- Improvement Cards
    - These cards improve one of your "farms" stats
- Sell Cards
    - These cards are used to exchange crops for profit, based on the rate on the card
- Violence Cards
    - These cards are used to inhibit your opponents, at the risk of catching heat from the DEA (accelerating time) or backfiring (hurting your own stats)

Resolve actions on cards immediately.

### Time Phase
Draw a time card and resolve actions on it. If it's the "DEA ARRIVES" card, jump to the ENDGAME section of the rules.

#### Time Deck
The Time deck represents the passage of time in the game. Since you never know when the DEA is going to arrive, you have to decide when to sell and when to wait to grow more crops first. This makes the game more suspenseful as time passes. Some time cards may have events on them that alter player stats, crop levels, or even shuffle the time deck. 

## Endgame
Once the DEA card is drawn, endgame begins. At this point, there are only 2 full turns left. Crops are worth 1.5 as much because of a plummet in supply, but choosing to sell during this phase means you lose an opportunity to purchase victory items. During this phase, players can choose to purchase a victory item from the pile instead of playing an action card. These items are worth victory points, and may include actions or requirements for their purchase. For example, an item might only be worth a few points, but give you an extra turn, or an item might be worth many points, but require your product has a very high value first. Once all turns are complete, the game ends, and scoring is conducted.

# Scoring
Victory points from victory items are tallied. Remaining crops are worth 1/2 their value and converted to money. Then, money is coverted to victory points in a 200k->1 ratio (TODO: fix this math). The player with the most points wins. 

# Example cards, items, etc
Note that a polished version would have fun descriptions and flavor texts, this is purely mechanical

## Improvement cards:
- Increase farm output by 2 if defense over 5; otherwise Increase farm output by 1
-  increase product quality by 2 but lower resilience by 1
- double production for this turn only (stacks)
- improve resilience by 2 but halve production for this turn

## Sell cards
- if trust > 4 and quality > 5, rate is x. otherwise rate is y.
- if trust > 9, rate is x. Otherwise, rate is y * quality
- etc

## Attack cards
Note! resilience is a hidden stat, so you have to gamble when attacking sometimes.
- halve target player's production if their resilience < 7. Lose 3 trust yourself.
- decrease target player's quality by 1. pay x money to do this
- steal 10 crops from target player if their resilience is 2 or more less than yours. otherwise, lose 1 resilience and x money.

## Time cards
- bountiful season, harvest an additional 2 crops
- drought! lose 2 production rate
- hurricane season! shuffle time deck

## Victory items
- enormous statue of yourself, +10 pts
- offer to pay off national debts, +4 pts and take extra turn
- build your own prison (Escobar actually did this), +6 points
