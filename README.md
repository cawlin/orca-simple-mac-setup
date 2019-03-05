# Setting Up Orca Live Programming Enviroment on Mac OS for Beginners

This very simple set of steps will help you get Orca set up and making sounds with a simple software synthesizer. This is intended for Mac users who have little knowledge of making music on computers. When you complete these steps you will have everythng you need to follow Allieway Audio's [ORCA Sequencer Intro Youtube Video](https://www.youtube.com/watch?v=RaI_TuISSJE&t=116s).

Here's what we'll cover:

1. Download Orca
2. Download a Software Synth
3. Setup MIDI Bus
4. Connect Orca and a Software Synth

# Download Orca

Head to the Orca Itch.io page and download the app. Consider making a donation because the program is neat. Install the app like any other mac app.
https://hundredrabbits.itch.io/orca

You can open Orca and it should look like this. Notice how the "No Midi" text at the bottom of the screen? If this is what you see you won't be able to make any sounds with Orca.

![Orca no Midi](https://github.com/cawlin/orca-simple-mac-setup/blob/master/images/1.png)

# Download a Software Synth

Orca does not make any sounds itself. It controls other programs or physical instrument through [Midi](https://en.wikipedia.org/wiki/MIDI). To make sounds and music we need an instrument for Orca to control.

To quickly get up and running lets use Dexed - a plugin synth that is closely modeled on the Yamaha DX7. Download and install.
[Dexed](https://asb2m10.github.io/dexed/)

# Set Up Midi

Now we have Orca and we have an Software synthesizers, how do we connect them?

Open the "Audio MIDI Setup" Utilities. You can find this in Applications > Utilities or search for it using Spotlight

![Midi Setup](https://github.com/cawlin/orca-simple-mac-setup/blob/master/images/2.png)

In the toolbar of Audio Midi Setup select "window" and then "Show MIDI Studio"

![Midi Setup](https://github.com/cawlin/orca-simple-mac-setup/blob/master/images/3.png)

You will now see a window like this:

![Midi Setup](https://github.com/cawlin/orca-simple-mac-setup/blob/master/images/4.png)

Double click on "IAC Driver" and you will see a window like this:

![Midi Setup](https://github.com/cawlin/orca-simple-mac-setup/blob/master/images/6.png)

You only need to do a single thing - check the "Device is Online" checkbox.

![Midi Setup](https://github.com/cawlin/orca-simple-mac-setup/blob/master/images/5.png)

You can now close the window and Audio MIDI Setup.

# Connect Orca and a Software Synth

Start by opening Dexed. In the top left hand corner there is an "options" button. Click it and choose "Audio/MIDI Settings...". 

![Midi Setup](https://github.com/cawlin/orca-simple-mac-setup/blob/master/images/7a.png)


At the bottom of the window is "Active MIDI Inputs" and the MIDI Bus we put online should be seen.

![Midi Setup](https://github.com/cawlin/orca-simple-mac-setup/blob/master/images/7.png)

You can close the window and feel free to hit the virtual keyboard keys with your mouse to make sure sound is working before going into Orca.

Now open Orca. If you had it open already close and reopen it. In the toolbar you should see "Midi" as an option. By default the Midi bus we put online should be selected - you can tell because the name will be in the bottom right hand side of the Orca window. You can also manually select Midi if you have multiple connected sources by clicking on the toolbar.

![Midi Setup](https://github.com/cawlin/orca-simple-mac-setup/blob/master/images/8.png)

You are now ready to make a sounds! Check out Allieway Audio's [ORCA Sequencer Intro Youtube Video](https://www.youtube.com/watch?v=RaI_TuISSJE&t=116s) or the [Orca documentation](https://github.com/hundredrabbits/Orca).

Have fun! You can use this same technique for setting up more complex Virtual Synthesizer enviroments or DAWs like Ableton. Each tool may have require slightly different steps but the princples are the same.

![Midi Setup](https://github.com/cawlin/orca-simple-mac-setup/blob/master/images/orca-dex-gif)















