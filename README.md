Prototype of Enemy AI checking for locked and unlocked doors

This demo has a AI check three doors to see if they are locked or unlocked
The player can lock and unlock the doors by walking up to one and pressing "R"

The player starts on a floating block so they can observe the enemy AI movement

Issue right now is the navlink for the doors is not working correctly. So the AI has a hardtime actually walking through the unlocked doors 


1/9/23
The Navigation issues have been fixed. The AI will open the door if it detects as unlocked and then move towards the player
Players can also place a static mesh actor in front of a door to lock the door instead of pressing "R" on it
The setup now is one door will have a cube placed, and two other doors can be manually locked by the player
The AI will attempt to find a open door and move through it
