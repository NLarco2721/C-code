Thesea re three basic C# movement files usable in the Unity engine.

The first file is the InputManager file, which essentially manages 
general key inputs for character movement. It also makes sure that the 
other two files work well with each other, and with the game environment.

The second file is the PlayerLook file, which codes for the player character
following the movement of the mouse. Essentially, makes sure that the player
character can turn its head correctly.

The third file is the PlayerMotor file, which makes sure that the player character 
moves as intended by the user. Codes for the character gravity, walk/run speed,
crawling, going up or down ladders and jumping. The code makes sure that the key binding that was created in the
CharacterController section of unity get tied to the movements themselves.

Note: make sure to edit the code appropriately depending on how you want the game to be played.
This means editing gravity, sprint speed, or having the ability to crawl or jump.
