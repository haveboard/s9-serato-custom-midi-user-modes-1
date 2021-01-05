# Serato Custom MIDI User Modes for the Pioneer DJM-S9
### created by [DJ haveboard](http://djhaveboard.com/)

updated April 10th, 2018 current version 1.0.1

4 separate User Modes for the Pioneer S9 to work with Serato DJ to provide additional functionality.

I still haven't figure out how to get the XML to inherit Serato color values for cues so the colors are set as is. These can be changed with some basic XML editing.

~~Cues stay lit (IT'S LIT, YO) whether there is a cue set for that pad or not. If you know how to light up the pads _only_ when there is an active cue please contact me and let me know.~~
Output lighting for pressed cues removed in favor of active/inactive cue lighting. If there is no cue in a slot, the cue no longer lights up.

## Installation

1. Clone or Download the files to your computer from the green button on the upper right side of [this GitHub Repo](https://github.com/haveboard/s9-serato-custom-midi-user-modes-1).
2. Place `s9_custom_user_modes_by_haveboard.xml` file into your Serato MIDI XML Directory
   - Mac: `~/Users/\_YOUR_USER_NAME_/Music/_Serato_/MIDI/Xml`
   - Windows: `C:\Users\_YOUR_USER_NAME_\Music\_Serato_\MIDI\Xml`
3. Go into Serato DJ Settings under the MIDI tab, select the `s9_custom_user_modes_by_haveboard` option from the MIDI PRESET list and then select "load" to load the custom MIDI XML file.
4. To enable one of the Custom User Modes, press `SHIFT` + one of the PAD MODE buttons _twice_ to enter the respective User Mode:
   - [User Mode 1](https://github.com/haveboard/s9-serato-custom-midi-user-modes-1#user-mode-1---cues--samples) - `SHIFT + HOT CUE x2` Cues & Samples
   - [User Mode 2](https://github.com/haveboard/s9-serato-custom-midi-user-modes-1#user-mode-2---cues--rolls) - `SHIFT + ROLL x2` Cues & Rolls
   - [User Mode 3](https://github.com/haveboard/s9-serato-custom-midi-user-modes-1#user-mode-3-left-cues-left--right-pads-sample-deck) - `SHIFT + SLICER x2` Left Cues Left & Right Pads Sample Deck
   - [User Mode 4](https://github.com/haveboard/s9-serato-custom-midi-user-modes-1#user-mode-4---left-pads-sample-deck--right-cues-right) - `SHIFT + SAMPLER x2` Left Pads Sample Deck & Right Cues Right
   
## User Modes Explained
Pads are numbered starting top left, left to right, separated by left pads and right pads.

| ___ | ___ | ___ | ___ | middle btns | middle btns | ___ | ___ | ___ | ___ |
| --- | --- | --- | --- | :---: | :---: | --- | --- | --- | --- |
| L01 | L02 | L03 | L04 | HOT CUE | ROLL | R01 | R02 | R03 | R04 |
| L05 | L06 | L07 | L08 | SLICER | SAMPLER | R05 | R06 | R07 | R08 |

## User Mode Shortcuts

If you go into your 'DJM-S9 Settings Utility' under 'Preference' you can check 'PAD MODE options' so you can press the pad mode button 3 times instead of holding `SHIFT + PAD MODE BUTTON` to get into the user modes.

## User Mode 1 - Cues & Samples 
- press `SHIFT + HOT CUE x2`

### Left Pads
1. **Cue 1** (Shift + Pad Deletes Cue)
   - Red Shade - White Press
2. **Cue 2** (Shift + Pad Deletes Cue)
   - Orange Shade - White Press
3. **Cue 3** (Shift + Pad Deletes Cue)
   - Dark Purple Shade - White Press
4. **Cue 4** (Shift + Pad Deletes Cue)
   - Yellow Shade - White Press
5. **Sample 1** (Blue Shades)
6. **Sample 2** (Blue Shades)
7. **Sample 3** (Blue Shades)
8. **Sample 4** (Blue Shades)

### Right Pads
1. **Cue 1** (Shift + Pad Deletes Cue)
   - Red Shade - White Press
2. **Cue 2** (Shift + Pad Deletes Cue)
   - Orange Shade - White Press
3. **Cue 3** (Shift + Pad Deletes Cue)
   - Dark Purple Shade - White Press
4. **Cue 4** (Shift + Pad Deletes Cue)
   - Yellow Shade - White Press
5. **Sample 5** (Blue Shades)
6. **Sample 6** (Blue Shades)
7. **Sample 7** (Blue Shades)
8. **Sample 8** (Blue Shades)

For the rolls, I like the shorter rolls closer to the decks so the Rolls are mirrored from 1/8 on the outside to 1 on the inside for each deck

## User Mode 2 - Cues & Rolls
- press `SHIFT + ROLL x2`

### Left Pads
1. **Cue 1** (Red Shade - White Press)
   - Shift + Pad Deletes Cue
2. **Cue 2** (Orange Shade - White Press)
   - Shift + Pad Deletes Cue
3. **Cue 3** (Dark Purple Shade - White Press)
   - Shift + Pad Deletes Cue
4. **Cue 4** (Yellow Shade - White Press)
   - Shift + Pad Deletes Cue
5. **1/8 note Loop Roll** (Green Shades)
6. **1/4 note Loop Roll** (Green Shades)
7. **1/2 note Loop Roll** (Green Shades)
8. **1 note Loop Roll** (Green Shades)

### Right Pads
1. **Cue 1** (Red Shade - White Press)
   - Shift + Pad Deletes Cue
2. **Cue 2** (Orange Shade - White Press)
   - Shift + Pad Deletes Cue
3. **Cue 3** (Dark Purple Shade - White Press)
   - Shift + Pad Deletes Cue
4. **Cue 4** (Yellow Shade - White Press)
   - Shift + Pad Deletes Cue
5. **1 note Loop Roll** (Green Shades)
6. **1/2 note Loop Roll** (Green Shades)
7. **1/4 note Loop Roll** (Green Shades)
8. **1/8 note Loop Roll** (Green Shades)

## User Mode 3 - Left Cues Left & Right Pads Sample Deck
- press `SHIFT + SLICER x2`

### Left Pads
1. **Cue 1** (Red Shade - White Press)
   - Shift + Pad Deletes Cue
2. **Cue 2** (Orange Shade - White Press)
   - Shift + Pad Deletes Cue
3. **Cue 3** (Dark Purple Shade - White Press)
   - Shift + Pad Deletes Cue
4. **Cue 4** (Yellow Shade - White Press)
   - Shift + Pad Deletes Cue
5. **Cue 5** (Dark Green Shade - White Press)
   - Shift + Pad Deletes Cue
6. **Cue 6** (Pink Shade - White Press)
   - Shift + Pad Deletes Cue
7. **Cue 7** (Light Green Shade - White Press)
   - Shift + Pad Deletes Cue
8. **Cue 8** (Light Purple Shade - White Press)
   - Shift + Pad Deletes Cue

### Right Pads
1. **Sample 1** (Blue Shades)
2. **Sample 2** (Blue Shades)
3. **Sample 3** (Blue Shades)
4. **Sample 4** (Blue Shades)
5. **Sample 5** (Blue Shades)
6. **Sample 6** (Blue Shades)
7. **Sample 7** (Blue Shades)
8. **Sample 8** (Blue Shades)

## User Mode 4 - Left Pads Sample Deck & Right Cues Right
- press `SHIFT + SAMPLER x2`

### Left Pads
1. **Sample 1** (Blue Shades)
2. **Sample 2** (Blue Shades)
3. **Sample 3** (Blue Shades)
4. **Sample 4** (Blue Shades)
5. **Sample 5** (Blue Shades)
6. **Sample 6** (Blue Shades)
7. **Sample 7** (Blue Shades)
8. **Sample 8** (Blue Shades)

### Right Pads
1. **Cue 1** (Shift + Pad Deletes Cue)
   - Red Shade - White Press
2. **Cue 2** (Shift + Pad Deletes Cue)
   - Orange Shade - White Press
3. **Cue 3** (Shift + Pad Deletes Cue)
   - Dark Purple Shade - White Press
4. **Cue 4** (Shift + Pad Deletes Cue)
   - Yellow Shade - White Press
5. **Cue 5** (Dark Green Shade - White Press)
   - Shift + Pad Deletes Cue
6. **Cue 6** (Pink Shade - White Press)
   - Shift + Pad Deletes Cue
7. **Cue 7** (Light Green Shade - White Press)
   - Shift + Pad Deletes Cue
8. **Cue 8** (Light Purple Shade - White Press)
   - Shift + Pad Deletes Cue

## Parameter Buttons

~~The parameter buttons for all user modes select Sample Bank's A, B, C, and D, left to right respectively.~~
Parameter buttons for banks have been removed as it caused the parameters to not work properly for other modes. Hat tip to DJ Harley Beretta for making me aware.

Credits:
@Themitchell for his `serato_dj_launchpad_midi_mapping.xml` [gist](https://gist.github.com/Themitchell/2fbeea02d3937cbb631a) which showed me `auto_loop_roll_specific_length`


For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/haveboard/s9-serato-custom-midi-user-modes-1/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
