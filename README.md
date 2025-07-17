# WeaponSway
A C# script you can use in your Unity FPS game to add position/rotation sway as well as bobbing while walking to your gun. This will make your gun model feel more dynamic and less stuck in place, adding to the game feel. This is intended to be used for FPS weapons but it will work just as well for any type of viewmodel.

## Installation
1. Download the WeaponSway.cs script and drag it into your Assets folder (typically into Assets/Scripts/).
2. Make sure your gun (or whatever viewmodel you are using) is a child of two empty game objects, I recommend naming one of them "Bobbing" and the other one "Sway".
3. Attach the WeaponSway script to your gun.
4. Drag the two empty parent game objects into the corresponding transform slots in the inspector.
5. Adjust any of the other settings in the inspector to fit your game, the default settings you will see are my personal preference.
6. Hit play and enjoy your dynamic and responsive feeling gun.