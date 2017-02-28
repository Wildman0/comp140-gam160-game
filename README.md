# comp140-gam160-game
###Kyle Wildman
Repository for Assignment 1 of COMP140-GAM160

# Game Concept

The game will be 3D and consist of a top down view on 2 trash compactors with a conveyor belt moving a number of different items 
towards the compactor. Some of these will be items which the player wants to compact, such as an aluminium can or other various sorts 
of trash. Other items will be ones they want to avoid crushing such as a bomb or a baby. Crushing the trash will increase the player's 
score by 500 for a direct hit, 300 for a slightly off time hit and 100 for a way off time hit, as well as increasing their score 
multiplier by 1x (Look at a game called Osu! for the same scoring system, albeit in a very different game). Trying to crush something 
the player shouldn't or not crushing something they should will make them lose lives and reset their score modifier. 
As the game goes on, the conveyor belts will speed up, increasing the challenge for the player. If done correctly, this should make the 
game frantic and challenging at points which, in my opinion at least, makes it fun, This can either go on until the player 
can't keep up anymore or it can be a timed game. In both cases, score and time survived will be the measure for how well the player has 
done.

# Mechanics

- Compacting -

The central part of the game is the mechanics of crushing trash pieces that come towards the compactors at the right time, avoiding 
compacting any objects that aren't meant to be compacting. The player will have to compact the right objects at the right time in order 
to increase their mutliplier, build their score up and stop the game from ending due to a lack of trash compacting. Over time, the trash 
will come quicker and move frequently in order to challenge the player further. The compacting action will happen when the player pushes the corresponding finger cymbals together.

- High Scores -

Part of the motivation for the player will be the inclusion of high scores. This will jsut derive from the score they are able to get 
while playing, by the inclusion of high score adds a competitive element, making it more like that the player will come back to try 
beating other scores/


# Custom Controller Concept

For this game, I will be attaching pressure sensors to 2 pairs of mini cymbals that are attached to the players' thumb and index finger 
on each hand. I plan on making the first prototype using an Arduino Uno and [2 pairs of finger cymbals](https://www.amazon.co.uk/Percussion-Plus-PP210-Finger-Cymbals/dp/B002R0IL1Q/ref=sr_1_1?ie=UTF8&qid=1488294011&sr=8-1&keywords=finger+cymbals) with 
attached pressure sensors or easily pressable buttons attached to detect when the cymbals touch together. This will send a signal to the 
Arduino, which the game will then be able to interpret as the player pushing down the left or right compactor.

# Other Alt Controllers

One alt-controller I can take inspiration from is [this one used to play Winston in Overwatch](https://www.youtube.com/watch?v=_GJ55UIyGvw). I can use the 
way that he completes circuits with the cymbals too, by having wires attached to each with a conductive plate that signals a button
press whenever they touch. This might prove to be more complex than necessary though

Alternatively, I considered a [High Striker](https://en.wikipedia.org/wiki/High_striker) style alt-controller. Although not specifically 
an alternative controller for videogames, it uses a pressure sensor in order to sense how much pressure is being applied to it. I could
attach a component that measures specific pressure to the cymbals, meaning that the player would have to actually clap them together
with some force in order to get the compactor to compact. This could be to comedic effect, as the cymbals would make a noise when 
clapped together but it could also become uncomfortable to play for a long time, discouraging players from doing so.
