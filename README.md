# js-game
Title: Initial game functionality - MVP

**Description**

_Must Have_

- Build a game where a player's robot can fight another robot until one of them loses.

- If the enemy-robot loses first, the player's robot will move on to fight another enemy-robot.

_Features_

- The player's robot's name can be dynamically created by the player through the browser.

- The player is given the option to skip the fight by paying a penalty fee, or continue with the fight.

Title: Add shop functionality

**Description**

- After defeating an enemy, ask the player if they would like to purchase an item from a store.

- The player can purchase health or attack points if they can afford it.

Title: Add randomness to health and damage values

**Description**

- Start enemies at a random health value between 40 and 60.

- Start enemies with a random attack value between 10 and 14.

- Attack damage is random, using the robot's attack value as an upper limit (for example, if the player's attack is 10, their damage range is 7-10).

Title: Restructure data with JS objects

**Description**

- Create and use JavaScript objects to organize data related to the player and data related to the enemies.

- Create object methods to perform player actions.
