# Teenage Engineering K.O. II Tips and Tricks

Compiled from various sources, mostly from the Elektronauts thread here:

https://www.elektronauts.com/t/ep-133-tips-and-tricks/204124

[General](#General)
[Sequencing](#Sequencing)
[Timing](#Timing)
[FX](#FX)
[Punch-In FX](#Punch-In FX)
[Looper](#Looper)
[Fader](#Fader)
[Sampling](#Sampling)
[Undo](#Undo)

---
## General

### Lock Mode
When powering on, hold MAIN. The screen will flash "LOK". Now any changes you make will not be automatically saved. Turn off and back on again to turn off lock.
### Playback Speed Nudge
During playback pressing/holding + or - will speed up or slow down the playback temporarily.
### Playback Speed Nudge Lock
If you hold + or - during playback to nudge the playback speed, pressing FX will lock the speed change. Pressing MAIN will return to normal speed.
### Change Projects
Hold MAIN and then press and hold a numbered pad until you see P followed by a number (which is the Project number you selected).
### Changing Base Pitch or Volume of A Pad Sample
Press SOUND and then the X/Y knobs control the Amplitude (volume) and Pitch.
### Remove A Sample From A Pad
Hold SOUND then press 0.

> Note: don't use ERASE + SOUND to remove a sample from a pad. ERASE + SOUND actually deletes the sample from the KO's memory!
### Running Out of Adjustment Travel For X/Y Knob
If you're fine tuning using X or Y knobs and you run out of physical travel to get the value you want, switch to System Settings (hold SHIFT, press ERASE) and you can move the knobs wherever you want to and exit System Settings without affecting the parameter.
### Mute and Solo
There is no dedicated Mute function but holding a Group pad (A/B/C/D) and moving the fader to the bottom will set the group(s) to silent i.e. muted - an icon will appear in the display to show the group is muted.

To solo a Group, hold FX and press the Group pad. This "stacks" so if you solo Group A, you can solo Group B (or whatever) and then both A + B groups will play soloed.

---
## Sequencing
### Empty Pattern Indicator
A little "pin wheel" or asterisk icon will appear below the Bar.Beat when the selected Pattern is empty.
### Find Next Empty Pattern
Hold SHIFT and Press A. The next empty Pattern for the current Bank will be selected.
### Trigger Sequencer Recording By Pressing Pad
If you engage recording mode (when stopped) by pressing RECORD, hitting any of the number pads will start recording playback.
### Changing Patterns for Multiple Tracks Simultaneously
Hold any combination of A, B, C or D and hit + or - to change pattern for all tracks. You can also type in a number on the pads and the pattern for each of the tracks will change to that pattern.
### Pattern Change Timing
SHIFT + ERASE to enter System Settings. Use + to move to SEQ and press ENTER. Use + to move to SCN and press ENTER. Select TICK or BAR.
### Change Time Signature For Current Scene
Hold MAIN and then press TEMPO.
### Tap Tempo
Tap the TEMPO button
### Fine Tempo Adjustment
Hold SHIFT while adjusting the tempo.
### Detect Input Tempo When Sampling
Hold SAMPLE and press TEMPO.
### Polymeter Sequencing
Set Time Signature to 1/4 then set the Pattern Length(s) to 3, 5, 7 etc.
### Keys Mode and Repeats
In Keys Mode, you can hold TIMING and a pad to repeat that pad and then play other notes while that pad is repeating.

In Keys Mode you can engage a Punch-In FX such as Bit Crusher (Pad 9), release the FX button while holding the Punch-In FX pad and then if you play subsequent notes they all run through the effect.
### Changing Repeat Speed While Repeating
If you hold TIMING and press a pad to repeat that pad, you can let go of TIMING while still holding the pad. This then frees up your hand to change the Repeat Speed (X knob) while the note is repeating. This will also be recording to the Sequencer if recording is active.
### Transpose Recorded and Incoming MIDI
Open a Pad in Keys Mode.
Enter Sound Edit (SHIFT + SOUND) and use +/- to select MIDI
Adjusting the Y knob will inversely transpose recorded and incoming MIDI on that pad.
Note: this also works even in the outgoing MIDI channel is set to 'off'.
### Step Sequencing Note Length
When in Step Sequencing mode, with RECORD held and entering notes, the longer you hold the pad to enter the note, the longer the recorded note length.
### Quantizing Single Notes While Live Recording
In live recording mode, if you want to quantize a single note, hold TIMING before recording the note.
### Replace Mode Recording
By default recording new notes into a pattern adds the new notes to the existing ones. If you arm recording by pressing RECORD and then instead of just pressing PLAY to start recording, holding SHIFT then pressing PLAY starts recording in replace mode.

---
## Timing

The timing grid is based on 96 PPQN.

| Division | Ticks | Notes |
| ---- | ---- | ---- |
| Septuplets | 0 14 27 41 55 69 82 |  |
| Quintuplets | 0 19 38 58 77 |  |
| Triplets | 0 32 64 |  |
| 16ths | 0 24 48 72 | Any tic number divisible by 24 is a 16th |
| 32nd | 12 24 36 48 60 72 84 | Any tic divisible by 12 is a 32nd |
| 64th | 0 6 12 18 24 30 etc. | Any tic divisible by 6 is a 64th |
| 128th | 0 3 6 9 12 15 etc. | Any tic divisible by 3 is a 128th |

---
## FX

### Controlling the Timing of Master FX Changes
Hold SHIFT and press +/- to select a Master FX. FX won't change until you let go of SHIFT.

---
## Punch-in FX

| Pad | Punch-In FX | Pressure Modulation | Note |
| --- | --- | --- | --- |
| . | Pitch Mod | Pitch mod more random | |
| 0 | Pad Random | | |
| ENTER | Stutter | | |
| 1 | Beat Repeat | Repeat duration decreases | |
| 2 | Tape Stop | Speed decreases | Affects MIDI clock output |
| 3 | LPF Tremolo | Speed increases| |
| 4 | LPF | Cutoff frequency decreases | |
| 5 | HPF | Cutoff frequency increases | |
| 6 | Master FX Send | Send amount increases | |
| 7 | Mute Slicer | Chop speed increases | |
| 8 | Octave Down | Pitch increases towards original | |
| 9 | Bit Redux | Bit depth reduces | |

### Play Other Pads While Punch-In FX Active
If you hold FX and press a pad to enable a Punch-In FX, you can release the FX button while still holding the pad and then while the FX is active you can play all the other pads.

### Punch-In FX on Pad 6 Is Master Effect
Punch-In FX on Pad 6 is a send to the Master Effect so if you change your Master Effect this will affect the Punch-In FX on that pad.

---
## Looper

### General
All fader functions work while Loop is active.
You can switch between Groups and jam on the pads while the Loop is active.
### Changing Loop Start and Length
As well as the X/Y Knobs you can use + or - while Loop is active to shift the start position.
### Set Initial Loop Length
When triggering Loop Mode with SHIFT+TEMPO, the longer you hold TEMPO the longer the initial loop length will be.
### Standby Mode For Looper
Hold SHIFT + FX then press TEMPO and Loop Mode will be activated but looping won't start until you move the X or Y knob to set the start/length of the loop.
### Use Punch-In FX With Loop Active
Turn on the Loop (SHIFT+LOOP)
Hold FX and hold pad for Punch-In FX.
Release FX while still holding pad then use + or - to move the Loop.
Release Punch-In Pad and try another FX, the Loop stays active.
### Use Punch-In FX While Changing Master FX
You need to keep holding FX to change Master FX otherwise Loop turns off.
#### Exiting Loop Mode
As well as pressing MAIN, TEMPO or SHIFT + LOOP to exit Loop Mode you can also press FX twice. This is handy if you are using Punch-In FX with Loop and want to exit Loop and Punch-In at the same time without having to press MAIN or TEMPO.

---
## Fader

#### Fader "Default" Mode Is Group Volume
Holding any of the group pads A/B/C/D and moving the fader sets the volume for the group(s).
### Reset All Fader Settings
Hold SHIFT and press FADER - does not clear any fader automation just resets current parameter(s).
### Step Recording The Fader
While not quite Elektron-style P-Locks you can use + or - to move to a step, hold down RECORD and move the Fader. Whatever value you record on a step will remain for the rest of the sequencer until another automation parameter value is recorded.
### Show Fader Assignment/Position
Hold FADER and press the A/B/C/D pads. The display will show you the currently assigned Fader function for each bank and also the left of the display will show you the current "virtual" fader level.

---
## Sampling

#### Detect Input Tempo When Sampling
Hold SAMPLE and press TEMPO.

---
## Undo

Undo only available when there is an umbrella symbol displayed.

To use Undo, hold SHIFT and press Pad B.
### Undo During Recording
Undo during recording reverts to the point at which Play was pressed. In other words, to confirm a note entry/sequence change, you need to press Stop at least once.
### Elektron-Style 'Reload'
Record fader automation then press SHIFT+B to Undo which will return the Pattern to the state before you recorded the automation.
