# Offworld teleporters for Quake 2
An implementation of offworld or inter-server teleport pads for Quake 2

Extendable "offworld" or inter-server teleportation. The teleporter entity can be added to maps directly or via entity override files.
The teleports spin in game to distinguish them from ordinary intra-map teleports. When player approaches the pad it announces with a center-print message and sound to indicate the target server to the user. Upon touch, the player is teleported via a connect command stuffed to the client. The departure of the player is announced to the other players in the game.

Plans were to extend it to launch other game clients and quit the Quake2 client but this was never implemented.

