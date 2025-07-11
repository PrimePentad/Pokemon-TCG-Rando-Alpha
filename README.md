# Pokemon TCG for GBC Randomizer Alpha - Proof of Concept

## What am I looking at?

  The purpose of this is to provide a proof of concept for the Pokemon TCG randomizer, as well as providing a list of what is needed from the AP world/client. 
  A binary diff patch is provided with a manually injected randomizer to provide a concrete example of my vision for the randomizer.


## So what do you want from me?

  1. I am primarily hoping to find someone to help build the AP side of things as I have neither the knowledge or time to learn and build it. I am more than happy to learn and help maintain it.
  
  2. Secondarily, please feel free to play the seed and start providing feedback in the Pokemon TCG thread in the Future Games channel in the AP discord. I am not planning on any major changes 
  between now and getting a working AP beta going, but I am happy to start gathering feedback.


## How does the randomizer differ from the vanilla game?
  
  1. The most important change is a significant overhaul of the booster packs.
     - The seed provided demonstrates an 'Evolution Line' booster system where boosters are pre-seeded with a playset of a full evolution line. For example, there is a booster pack that contains 4 Spearow and 4 Fearow.
     - The intention is to provide some lesser-known Pokemon lines a chance to shine in the early game, as they may be among your only options.
     - Trainers also come in their own individual booster packs of 4, with notable exceptions that are split into 2 packs of 2 or even 4 packs of 1 copy thrown into the pool. (Bill, Professor Oak, Computer Search, etc...)
     - There are a limited quantity of boosters in the game, with the intent to prevent players from farming boosters instead of doing AP checks.
     - A 'Vanilla-like' alternative will be available, with increased card counts in the boosters to make up for the limited booster quantity. However I'm presenting the 'Evolution Line' option here as I believe it is the stronger option after playtesting.

  2. The second most important change is that there are (optional) doors blocking the club floors.
     - This provides the game with much needed hard progression, as the game is more or less beatable with a lightly modified starter deck. If you disagree with that opinion, the inclusion of the doors will be optional.
     - The clerks standing next to the doors will tell the player what the key is. In addition, the clerks will open the door once the key is presented to them.
     - The door key can be either a specific card or a medal, and the distribution of keys can be any combination of the two, as demonstrated by the example seed.
    
  3. The starter deck has been randomized. The structure is the same as the original 3 starter decks, with a stage 2 evo line, 2 stage 1 evo lines, and 2 basic only pokemon, distributed across 3 colors.
     - In addition, the player is given 80 of each energy, excluding double colorless energies.

  4. The Challenge Hall is excluded from AP items/locations as of now. Instead, it is permanantly on as an activity to do during BK downtime.
     - To prevent players from spamming Challenge Halls instead of doing other checks, the reward is quite meagar: 4 random cards across all possible cards.

  5. Several other miscellaneous changes have been implemented to smooth out the experience.
     - The tutorial is completely skipped.
     - NPCs who trade with the player multiple times will trade back-to-back without resetting the game.
     - Ishihara trades no longer require the legendary cards and so they are in the pool.
     - The fighting club pupils are already visiting other clubs without talking to Mitch first - this is to expand sphere 0 checks when the club floors are locked.
     - Not a change so much as a reminder: several club leaders have various requirements before battling them that are still in place (for example, having 4 medals before challenging Murray).
  

### So how does AP integrate into the game?
  1. The booster packs (and, optionally, medals) are the items added to the AP pool
  2. Locations are:
     - Trainer first fights: 2 rewards for a win, in addition to a third reward for the leader medals should they be randomized.
     - Trainer refights: 2 additional rewards for a second win. The trainer will give you a hint as to what the rewards are before a refight, with the specificity selectable by the player.
     - Ronald and Imakuni follow these same reward structures. Ronald is refightable if the player loses, and Imakuni immediately respawns in another gym for rebattle without requiring a system restart.
     - The boosters sent to the player in the mail are also randomized.
     - The trades as well as the slowpoke behind the poster are also thrown into the pool.
       + However, while the trade requirements are vanilla, you only need to have the required card, you will not actually have to give it up.
       + Furthermore, the reward for these trades is replaced with boosters instead of individual cards.
  3. Once AP integration happens, the player will obtain items send from AP by rereading mail 1, which has been renamed 'AP items'. 
