# FF-TFAssets
 Assets to use in TF2 when streaming

**REPLACING MEANS DELETING/MOVING THE OLD FOLDER AND MOVING IN THE NEW FOLDER, NOT OVERWRITING.**
Move `custom` to the `tf` folder, overwriting the existing `custom` folder. If you already had mods in there, replace the folder with the new one instead, backup your old `custom` folder if needed.

Replace your `tf/cfg` folder. BACKUP your old cfg folder if you're planning to play TF2 ever again. 
Before launching TF2, disable Steam Cloud Synchronization in the properties of the game in the Steam Library.

Set your launch options for TF2 (same place as Steam Cloud Sync) as these, again, backup your existing launch options if needed:
`-insecure -novid -windowed -noborder -h 1080 -w 1920 -nojoy -nosteamcontroller -precachefontchars -noquicktime -no_texture_stream -console`


Originally provided by J4mes, the configs had received multiple edits for Fortress Faceoffs. The configs were originally created for the Casting Coach Classic organization.
Content from the now deleted INSTRUCTIONS.cfg:
```
This is a collection of cfgs for casting and demo reviewing based off DumTum's demo review cfg file, and edited by Finn and Starach.
We are not experts and there are likely better ways to achieve the stuff in here, but this works for us.

MAKING IT WORK
To make this work, make sure this is your only active cfg folder in the tf folder (rename your current one something else or move it somewhere else).
Back up your main cfg and custom folders somewhere else.
Put '-insecure' into your TF2 launch options. (remove when you want to play the game normally)
Bear in mind some of the features like projectile outlines will only work for STVs and not normal demos.

THE FILES
They are basically the same but tailored to specifically casting or demo reviews.
For example the casting ones will auto switch to the killers pov, whereas the demo ones will not.
The current 'autoexec' is technically '_6v6_casting'. It's the one I use the most so it is the current default.
You can enable the others via console or by changing them to just 'autoexec' (changing the current autoexec to something else of course)
For the max fps value to change you have to do it while in the main menu not in a demo/STV.
The four autoexecs and the 'custom_team_names' files are the only custom things in here, everything else is automatically generated.

NOTES
Familiarise yourself with the keybindings in the cfgs, there's lots of neat things you can do.
'custom_team_names' lets you input the teams names beforehand and then use 'c' it to apply them into the hud.
Many of the key bindings are personal preference, I recommend adapting them to your usage.
BACK UP YOUR NORMAL CFG
You might need to put certain commands into your normal cfg to properly reset stuff after swapping back.
'tf_use_match_hud 1' is a common one, as well as 'cl_crosshair_scale 32' to make your crosshair reappear.
```