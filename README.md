#Pokemon TCG for GBC Randomizer Alpha - Proof of Concept

##What am I looking at?

  The purpose of this is to provide a proof of concept for the Pokemon TCG randomizer, as well as providing a list of what is needed from the AP world/client. 
  A binary diff patch is provided with a manually injected randomizer to provide a concrete example of my vision for the randomizer.


##So what do you want from me?

  I am primarily hoping to find someone to help build the AP side of things as I have neither the knowledge or time to learn and build it. I am more than happy to learn and help maintain it.
  Secondarily, please feel free to play the seed and start providing feedback in the Pokemon TCG thread in the Future Games channel in the AP discord. I am not planning on any major changes 
  between now and getting a working AP beta going, but I am happy to start gathering feedback.


##How does the randomizer differ from the vanilla game?
  
  1. The most important change is in booster back distribution.
      -The seed provided demonstrates an 'Evolution Line' booster system where boosters are pre-seeded with a playset of a full evolution line. For example, there is a booster pack that contains 4 Spearow and 4 Fearow.
      -The intention is to provide some lesser-known Pokemon lines a chance to shine in the early game, as they may be among your only options.
      -There are a limited quantity of boosters in the game, with the intent to prevent players from farming boosters instead of doing AP checks.
      -A 'Vanilla-like' alternative will be available, with increased card counts in the boosters to make up for the limited booster quantity. However I'm presenting the 'Evolution Line' option here as I believe it is the stronger option after playtesting.

  2. The second most important change is 
