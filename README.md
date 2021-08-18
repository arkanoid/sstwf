# Slow Story Telling Web Framework

This is a framework for a **web game** based on node.js and MySQL. The game is of the **story telling** type; similar but not the same as Interactive Fiction (IF).

In [Interactive Fiction](https://en.wikipedia.org/wiki/Interactive_fiction) games you can have quick responses for your actions. If that's what you're interested on, check frameworks like [Twinery](https://twinery.org/) and several others.

It is **slow** because the story isn't really interactive. The story is told in parts, slowly. Then you perform actions that will, later, advance the story. You need to check on the game state once a while to see results, read, then take actions that will be processed (minutes, hours) and when done you will advance the story. Hence, **slow**. Of course the framework can be configured so the actions are instant or very quick; so it will be more like IF. You can do so if you want but the real purpose here is advancing the story slowly.

## Why slow?

Let's say some decisions made by the player involve battle between characters and enemies; or travel to other places; or researching new technologies, studying new information, searching for clues. Anything that would take some time in a story. After deciding what to do the player receives information about what's being done and how much time it will take. So the player can check back later and advance the story.

What the actions will process are up to you, that part can be programmed as you like. Use the node.js framework and the MySQL database as support to what you plan to do.

# Features

- Story is told in chapters/parts. You advance to different parts of the story depending on your actions.
- Different characters. You can have only one character, or several ones. More can be created later in the story, and some can die or leave the story, but several different characters may appear in it.

