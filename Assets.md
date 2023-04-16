The cursor Sprite is named `UI_Common_Cursor01` and is stored in this container
`Assets/GameAssets/Common/UI/Common/Sprites/UI_Common_Cursor01.png`

I bet something related to what triggers the sound will make mention of this
in the code.

...

I figure it would be the same sound across all 6 pixel remasters, so `ff0` files seem like the first ones to check. 

`ff0_system_assets_all_da92c74dfabef525966960a00c084b8e.bundle`
In this file, there is `SWAV_ff0_se001_choice.sab` which is the exact sound
asset I want to change! And the neighboring files would probably be good 
to change along side this mod with the name `SWAV_ff0_se[num]`

...Now how do I change this to the sound I want?