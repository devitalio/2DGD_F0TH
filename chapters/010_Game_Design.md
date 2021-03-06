\null\clearpage

Game Design
=============

\epigraph{There are three responses to a piece of design - yes, no, and WOW! Wow is the one to aim for.}{\textit{Milton Glaser}}

Game design is a huge topic, in this section we will just dip our toes into the argument, with some tips and tricks that can make the difference.

In this section we will also talk about level design tips, tricks and common pitfalls to avoid. We will talk about tutorials, entertaining the player and ways to reward them better.

Tutorials
-----------

### Do not pad tutorials

Tutorials are meant to introduce the player to the game's mechanics, but a bad tutorial can ruin the experience. Tutorials should be comprehensive but also compact, padding tutorials should absolutely not be a thing.

Gloss over the simpler things (usually the ones that are common to the genre) and focus more on the unique mechanics of your game.

Avoid things like:

> Use the "right arrow" button to move right, the "left arrow" button to move left, use "up arrow" to jump, use "down arrow" to crouch

Instead use:

> Use the arrows to move.

And eventually present the more complex mechanics in an "obstacle course" fashion.

### Integrate tutorials in the lore

Tutorials are better when well-integrated in the lore, for instance if your game features a high-tech suit maybe you should make a "training course" inside the structure where such suit was invented.

By integrating the tutorial into the game world, it will feel less of a tutorial for the player, but more like training for the game's protagonist.

### Let the player explore the controls

Sometimes it's better to allow the player to explore the controls, by giving them a safe area to try: this area is usually a tutorial or a specific training area.

It can prove more effective to avoid spoon-feeding your player with all the moves, and just let them explore the core mechanics of the game by themselves, eventually assisted by an in-game manual of some sort.

So instead of doing something like (thinking about a 2D tournament fighter):

> Do $\rightarrow \searrow \downarrow$ + A to do a chop attack
>
> Do $\rightarrow \nearrow \uparrow$ + A to do an uppercut
>
> ...

Try something like:

> Do $\rightarrow \nearrow \uparrow$ + A to do an uppercut
>
> Try more combination with your arrows and the attack buttons for more moves
>
> Check the move list in the pause menu

Consolidating and refreshing the game mechanics
------------------------------------------------

### Remind the player about the mechanics they learned

There's a latin saying that goes "repetita juvant", which means "repeating does good".

A good idea is to sprinkle around different levels concepts that have been learned previously, so to remind and consolidate them. This is more effective when done shortly after learning a new mechanic.

### Introduce new ways to use old mechanics

After a while, old mechanics tend to become stale, to rejuvinate them we can apply such mechanics to new problems. Changing their use slightly can make an old experience new again.

For instance, knowing that shooting our magic beam against something on the ceiling will make it drop (usually killing an enemy), we can make the player use such envinronmental interactivity to drop a suspended weight to open a door, or shoot a bell to "force" a change of guard so to sneak stealthily.

Rewarding the player
---------------------

### Reward the player for their "lateral thinking"

A good idea could be rewarding the player for not throwing themselves "head first" into the fight, but instead thinking out of the box and avoid the fight altogether, or just win it differently.

Putting a very powerful enemy in front of some treasure (for instance currency used in-game) can seem unfair, unless you place an unstable stalactite that can be shot with your magic beam.

Your magic beam won't deal enough damage to the enemy to kill it before such enemy takes your life, but a stalactite on their head will do the trick, and the reward for such lateral thinking will be a heap of coins (or gems, or whatever currency you invented).

![Example of how to induce lateral thinking with environmental damage [^chests] [^icetiles] [^undeadfossil]](./images/game_design/lateral_1.png){width=40%}

Giving tips to the player by breaking the fourth wall can be another idea, a rock or a patch of dead grass conveniently shaped like an arrow could point towards a secret room that has a fake wall.

![Example of how to induce lateral thinking by "breaking the fourth wall" [^jawbreaker]](./images/game_design/lateral_2.png){width=40%}

This last tip should be done very subtly, so not to ruin the immersion. Unless your game takes advantage from these kind of things (for instance games based on comedy).

[^chests]: 32x32 Chests attribution: Bonsaiheldin ([http://nora.la](http://nora.la)), hosted at [opengameart](https://opengameart.org/content/treasure-chests-32x32)

[^icetiles]: Simple SVG ice platformer tiles, listed as "Public Domain (CC0)" at [OpenGameArt.org](https://opengameart.org/content/simple-svg-ice-platformer-tiles-16x16-16x96-96x16)

[^undeadfossil]: Fossil (Undead) RPG Enemy Sprites attribution: Stephen Challener (Redshrike), hosted by [OpenGameArt.org](https://opengameart.org/content/fossil-undead-rpg-enemy-sprites)

<!--[^jawbreaker]: Jawbreaker tileset, listed as public domain at [https://adamatomic.itch.io/jawbreaker](https://adamatomic.itch.io/jawbreaker)-->

### Reward the player for their tenacity

After suggesting to reward players for not butting head-first into fights, now I'm going to suggest the exact opposite (in a way): reward your players for their tenacity.

Beating a tough boss with a certain (weak) weapon, or just the plain tenacity and skill that is needed to undertake a hard task, such feats should be rewarded: for instance with a powerful weapon that can be used after some level-ups.

### Reward the player for exploring

Exploration can lead the player to discover secrets, which can range from simple gear, to pieces of unexplored environment, or even pieces of the game's lore.

World exploration should not be limited to simple secrets, a nice idea could be finding a path towards something that is usually considered "environmental damage" (like a catapult in the background) so that the player can deactivate it.

Thinking out of the box can lead to some really interesting results when it comes to this tip.

### Reward the player for not immediately following the given direction

This is an extension of the previous point, the player should be rewarded for their exploratory efforts, even more when those efforts mean not immediately following the direction given by the designer.

"Thinking differently" should be rewarded with challenge and rewards up to said challenge. If the mission tells a player to climb up a tower, the more curious players could be led to hit the tower's underground dungeon before going on with the mission. A nice challenge in such dungeon with a fittin reward could expand on the game experience.

### Reward the player for not trusting you entirely

Sometimes it can be fun, for both the game designer and the player, to play a bit of a trick to the player themselves.

Some famous games, like DOOM and Dark Souls, use secrets-in-secrets to trick players into thinking they found something valuable, while hiding something way more important. Let's see the example below.

![Example of secret-in-secret](./images/game_design/secret_in_secret.png){width=50%}

We can see how we hid a secret inside of another secret and used a piece of valuable (but not *too valuable*) treasure to make the player think they found the secret, while the real secret is hiding behind another fake wall.

\placeholder

<!-- TODO: Talk about other level design tips -->

Tips and Tricks
----------------

### General Purpose

#### Make that last Health Point count

Players love that rush of adrenaline they get when they escape a difficult situation with just one health point. That "just barely survived" situation can be "helped" by the game itself: some programmers decide to program the last HP in a special way.

Some prefer giving the last health point a value that is higher than the other health points (kind of like a "hidden health reserve"), others instead prefer giving a brief period of invincibility when that last "1HP" threshold is hit.

These small devices allow you to give players more of those "near death" experiences that can give players that confidence boost to keep them playing through a hard stage, while at the same time, reducing the chance that they will rage-quit.

#### Avoiding a decision can be a decision itself

An interesting way to make the characters from a game seem more real, is registering the "lack of response" or "lack of action" in the game's AI or dialogue tree.

This means that "ignoring" has consequences, and inaction is in and itself an action of "doing nothing" which should be accounted for, just like ignoring someone in real life can have serious consequence or where someone may prefer to do nothing instead of taking one of many bad decisions.

This trick is used in the game "Firewatch", where not responding to a dialogue prompt is a noted decision.

#### Telegraphing

Players hate the feeling of injustice that pops out when a boss pulls out a surprise attack, that's why in many games where precise defense movement is required bosses give out signals on the nature of their attack.

This "telegraphing" technique, allows for that "impending danger" feel, while still giving the player the opportunity to take action to counteract such attack.

Telegraphing is a nice way to suggest the player how to avoid screen-filling attacks (which would give the highest amount of "impending danger").

![Example of a telegraphed screen-filling attack in a shooter](./images/game_design/telegraphing.png){width=60%}

Another example of telegraphing was used in the Bioshock series: the first shots of an enemy against you always miss, that is used to avoid "out of the blue" situation, which can be seen as a form of "telegraphing" both the presence and position of enemies.

### Shooters

#### Make the bullets stand out

One of the most annoying things that can happen when you're running-and-gunning your way through a level is being hit by a not-so-visible bullet.

Your own bullets, as well as (and most importantly!) the enemies' should stand out from the background and the other sprites, so that the player can see and avoid them.

Some people may want to ask why your own bullets should stand out too, the answer is: so you can easily aim for your targets.
