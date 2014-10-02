**WARNING**: This is not active yet. When this repo has settled and drone-wars has been update to
accept repo links this warning will be removed.

# Drone Brain

This repo contains the foundation of a [drone-wars][drone-wars] robot brain. To make a
brain, you should clone this repo. You can select one of the [provided brains](brains) to hack on,
or write your own from scratch. Example [bodies](bodies) and [turrets](turrets) are also provided.
Special thanks goes to @DarbyBrown for putting together some nice graphics (we did the original
body and turret which are pretty basic).

## Directory structure

When drone-wars inspects your repo, it will look for three files in the root directory:

 - `brain.js`
 - `body.png`
 - `turret.png`

Anything else will be ignored. The image files should both be `50px x 50px` PNGs.

For information on the data your brain receives, and how to format messages back, consult the
drone-wars README.

## Entering your robot into a battle

The easiest way to enter a robot is to make sure that the code you want to run is in the master
branch of your drone-brain repo on github. Copy the URL of the repo, and paste it into the entry
field.

You can use branches, tags and hashes too. All drone-wars needs to be able to do is resolve the
brain and image files.

[drone-wars]: https://github.com/drone-wars/drone-wars
