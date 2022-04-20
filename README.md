# Bloodstained-Arena
A text-based card game made in Python, loosely modelled after the game Super Auto Pets.

The bloodthirsty Titan known to mortals as Cavien can offer great power to those who prove themselves in his arena. Though he calls for blood, none of the aspirants can truly die, as the Titan magically heals all their wounds in the last moment before death takes them, ready to try again, though the process is not without immense agony.

Two aspirants battle against each other to win Cavien's favour, first acquiring means to attack with in the Shop phase with coins granted to them every round, before battling each other in turn-based combat.

Most basic functions of the game work, but the process of fully completing a round to return to the shop phase is incomplete. The game should be run directly from the file, not in the Python shell.

Known Bugs:
* Rounds currently never end
* Duplicate Melee cards in either player's hand share the same use counter
* Some fatal errors can occur which do not yet have a known cause

Planned features:
* Make rounds function as intended and play out until one player loses all lives
* Add basic AI that can fill player 2 slot
