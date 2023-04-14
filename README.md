# Serato DJ Pro Cue Point Script

This is a script for Serato DJ Pro that allows you to set cue points on multiple tracks quickly and easily. The script loads a track into the left deck and sets five cue points at different parts of the track: bar 1 (typ. intro), bar 9 (typ. verse), bar 25 (typ. pre/chorus), bar 41 (typ. into song), and bar 65 (winding down).

## Prerequisites

To use this script, you will need:

- A Mac computer
- Serato DJ Pro installed
- [cliclick](https://github.com/BlueM/cliclick) installed.

Note: If you have installed Homebrew, you can install `cliclick` by running the following command in your terminal:

```sh
brew install cliclick
```

## Usage

1. Open Serato DJ Pro and select the tracks you want to set cue points on.
2. Open the Script Editor application on your Mac.
3. Paste the script into a new script window.
4. Update the trackCountsToCue variable in the script to the number of tracks you want to set cue points on.
5. Save the script with a descriptive name (e.g. "Serato Cue Points").
6. In the Script Editor application, select Run to execute the script.

When the script runs, it will prompt you to enter the number of tracks you want to set cue points on. After you enter the number, the script will load the first track into the left deck and set the cue points. It will then load the next track and repeat the process until all tracks have been cued.

## Notes

- This script assumes that you are using the default keyboard shortcuts in Serato DJ Pro.
- The delay wait variable is used to give Serato DJ Pro time to process the keyboard shortcuts before the script continues. If you find that the script is not working as expected, you may need to increase this value.
- The cliclick commands are used to click the beat jump button in Serato DJ Pro. These commands may not work if you have changed the default layout of the Serato DJ Pro interface.
- Use this script at your own risk. Make sure to backup your tracks before running this script.

## make script into keyboard shortcut

see [guide here](https://apple.stackexchange.com/a/276839)
