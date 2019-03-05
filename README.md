# Setting Up [Orca](https://github.com/hundredrabbits/Orca) on Mac OS

This very simple set of steps will help you get Orca set up and making sounds with a simple software synthesizer. This is intended for Mac users who have little knowledge of making music on computers and just need to get the very basics set up. When you complete these steps you will have everythng you need to follow Allieway Audio's [ORCA Sequencer Intro Youtube Video](https://www.youtube.com/watch?v=RaI_TuISSJE&t=116s).

1. Download Orca
2. Download a Software Synth
3. Setup MIDI Bus
4. Connect Orca and a Software Synth

# Download Orca

Head to the Orca Itch.io page and download the app. Consider making a donation because the program is neat.
https://hundredrabbits.itch.io/orca

# Download a Software Synth

Orca does not make any sounds itself. It controls other programs or physical instrument through [Midi](https://en.wikipedia.org/wiki/MIDI). To make sounds and music we need an instrument for Orca to control.

To quickly get up and running lets use Dexed - a plugin synth that is closely modeled on the Yamaha DX7
[Dexed](https://asb2m10.github.io/dexed/)

# Set Up Midi

Now we have Orca and we have an Software synthesizers, how do we connect them?

Open the "Audio MIDI Setup" Utilities. You can find this in Applications > Utilities or search for it using Spotlight

[image]

In the toolbar of Audio Midi Setup select "window" and then "Show MIDI Studio"

[image]

You will now see a window like this:

[image]

Double click on "IAC Driver" and you will see a window like this:

[image]

You only need to do a single thing - check the "Device is Online" checkbox.

[image]

You can now close the window and Audio MIDI Setup.

# Connect Orca and a Software Synth

Start by opening Dexed. In the top left hand corner there is an "options" button. Click it and choose "Audio/MIDI Settings...". At the bottom of the window is "Active MIDI Inputs" and the MIDI Bus we put online should be seen.

[image]

You can close the window and feel free to hit the virtual keyboard keys with your mouse to make sure sound is working before going into Orca.

Now open Orca. If you had it open already close and reopen it. In the toolbar you should see "Midi" as an option. By default the Midi bus we put online should be selected - you can tell because the name will be in the bottom right hand side of the Orca window. You can also manually select Midi if you have multiple connected sources by clicking on the toolbar.

You are now ready to make a sounds! Check out Allieway Audio's [ORCA Sequencer Intro Youtube Video](https://www.youtube.com/watch?v=RaI_TuISSJE&t=116s) or the [Orca documentation](https://github.com/hundredrabbits/Orca).

Good luck!













