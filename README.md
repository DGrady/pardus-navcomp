# pardus-navcomp
A Pardus enhancement that highlights low-cost routes

[Pardus](https://www.pardus.at) is a massively multiplayer, browser-based game set in space that focuses on trading and combat. It's the kind of game in which players devote a lot of time to writing hacks and addons to make playing the game less irritating, and since my brief dalliance with Pardus in 2010 coincided with a desire to learn JavaScript, I tried my hand at coming up with a metagame tool as well.

This is the Pardus Navigation Computer, implemented as a Greasemonkey script for Firefox. It highlights a lowest-AP route from the player's current location to a destination that they specify. To find the lowest-cost route, it uses data pulled from the [Pardus community's auto-mapping server](http://pardus.butterfat.net) and Dijkstra's algorithm.

Apparently, Pardus, Greasemonkey, and Butterfat are all going strong six years later, but since userscripts.org has vanished I'm moving this to Github. I haven't played Pardus since I finished this hack in 2010, don't have any screenshots of it in action, and have no idea if it still works. It's here because storage is free.
