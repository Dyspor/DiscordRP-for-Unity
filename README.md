# DiscordRP-for-Unity
This is a Script for Unity, to Handle the Rich Presence

## How to use the Script
In the Script are some parts that you have to edit so it fits to your game:

### Application ID
On the Discord Developer Portal you create a Application. There is a "Application ID".

You Copy this ID and paste it in:


Line 29
> ADD_APPLICATION_ID_HERE

This "Connects" your Game with Discord (kinda)


### State
The "State" just describes the state the player is:

Playing, Main Menu, Idle

You can Change it within the ("")





### Details
The Same as State here are just some Details, that may describe the player state





### Large Image
In discord when a User is playing very often the Game Icon is shown there.

In the Discord Dev Portal, you add a Icon for your Application. This Icon got of course a Name.

In Line 66 you write the name where:
> "PLACE_IMAGE_HERE"
Between the ("")


## Applying it to the Game
This script just has to be in the game and loaded when in playmode.
The can be done by making it a component of the Player or the game manager
