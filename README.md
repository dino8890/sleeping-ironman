![preview](https://media.moddb.com/cache/images/downloads/1/211/210095/thumb_620x2000/cover_blue.png "preview")

Sleeping Ironman - Anomaly 1.5.1
--------------------------------

Modifies ironman mode to include time spent sleeping when determining when to grant a new life. Amount of sleep which counts towards granting a new life is configurable (see configuration section) and is half by default.

### Installation

#### JSGME:

Copy the "Sleeping Ironman" folder to your "MODS" folder and enable it through JSGME.

#### Manual:

Copy the contents of "Sleeping Ironman/gamedata" folder to your gamedata folder.

### Configuration

#### Using Mod Configuration Menu (MCM)
The mod is compatible with MCM, therefore you can simply install the mod and configure it through MCM as usual by selecting "Sleeping Ironman" menu.

#### Without Mod Configuration Menu (MCM)
The mod can be configured by changing default values from included script file:

1. Open `Sleeping Ironman/gamedata/scripts/sleeping_ironman_mcm.script` in code editor.
2. Locate `defaults` table, first line of the file. 
3. Configure the mod by changing the desired values (see details below).
4. Save changes and install the mod.

#### Details

- `sleep_percent` - ˙Percentage of hours asleep which count as being awake. For example, with a value of 0.5, sleeping for 12 hours will count as being 6 hours awake. 
  - `Acceptable values`: between `0.05` and `1.0`.
  - `Default`: `0.5`.
  - The old **Half Sleep** variant used the value `0.5`. 
  - The old **Full Sleep** variant used the value `1.0` making 100% of sleep count towards granting a new life.  
- `limit_lives` - Limits maximum number of lives. Additional lives past `max_lives` value are not granted.
	- `Acceptable values`: `true` or `false`.
	- `Default`: `false`.
- `max_lives` - Additional lives past this value are not granted. Works only when life limit is enabled.
	- `Acceptable values`: between `1` and `1000`.
	- `Default`: `3`.

### Feedback

Would love to hear your feedback on the "feel" of the game. Sleep percentage of `0.5` still keeps the original feel and tension, but offers another chance after a rare slip up or just bad luck.

### Related mods:

*   [Immersive Sleep](https://www.moddb.com/mods/stalker-anomaly/addons/immersive-sleep) by tkcrits

### Screenshot

![pda](https://media.moddb.com/images/members/5/4511/4510828/profile/pda.jpg "PDA")