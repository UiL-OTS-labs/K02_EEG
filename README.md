# K02_EEG
Docs for EEG setup in K02

# EEG setup K02

## Todo

- Test plans/reports pre-pilot (latency, sound card, etc)
- Technical drawing (digital version, Keynote master slide added here, should also be Powerpoint/LibreOffice editable versions?)
- Pictures & info of comopnenent (links of all components in keynote file --> export MD?) 
- Manual for Presentation experiment + triggers
- ~~Manual for ZEP?~~


# Overview of setup (update export after new edits)
![image info](https://github.com/UiL-OTS-labs/K02_EEG/blob/main/baby-eeg/baby-eeg.001.png)
![captions](https://github.com/UiL-OTS-labs/K02_EEG/blob/main/baby-eeg/baby-eeg.002.png)
![infographic](https://github.com/UiL-OTS-labs/K02_EEG/blob/main/baby-eeg/baby-eeg.003.png)


## General

### Caregiver + infant setup
- This lab was built as an _infant_ EEG lab, but the lab could be used for all ages (default documentation is for for caregiver + child (participant) scenario.
- Participants are _capped_ and connected with EEG equipment.
- Participant and caregiver will be inside the sound-proof cabin during an experiment. 

### EEG system details
- [BioSemi Active Two system](https://www.biosemi.com/products.htm)
- The amplifier can handle _two_ 32-channel electrode sets (matches the EEG lab in K13).
- [Manual for handling electrode sets](https://resources.lab.hum.uu.nl/resources/Electrodes_handling.pdf
- For more technical details about ther BioSemi Equipment: see the sections about EEG equipment [here](https://uilots-labs.wp.hum.uu.nl/facilities/eeg-lab/). 
- Better info will follow (TODO)

### Masking sounds & talkback (Crimson 3 monitoring interface + HP4 headphone amplifier)
- Caregiver can wear a headphone with masking sounds, played on mp3-player and the Crimson 3 monitoring interface.
- Using the Crimson 3, experimenter and caregiver can communicate using the 'talkback' button on the Crimson. 
	- Only if the experimenter presses the button, there is two-way communication. 
	- The microphone _inside_ the cabin is for the caregiver. 
	- Inside the Crimson is a microphone for the experimenter. 
	- The Crimson is --in this setup-- _not_ connected with USB to any PC, it works in _standalone_ mode.
	- The headphone loudness for the caretaker can best be tested before the experiment and can be adjusted using the headphone amplifier knobs.

### Visually masking the caregiver (polarised glasses)
- In case of visual stimuli, the caregiver may wear a pair of special polarised glasses that will mask the display contents (made by Chris van Run).

### Screens and their functionality
- Each PC (presentation PC and Recording PC) has connections for a _Screen A_ (experimenter section, outside the cabin) and a _Screen B_ (inside the cabin).
- The screen B for the Recording PC is _portable_. After capping and/or signal checking inside the cabin, the display may be taken back to its charging place at the experimenter desk, or otherwise moved/closed. Connect the portable screen to the DisplayPort to HDMI + mini HDMI adapter to use it.  

## System components

## Humans
- Participant
- Caregiver/parent
- Experimenter (and/or assistant)

## EEG system
- EEG Amplifier (EEG-a): where the bubndles are connected.
- EEG Trigger Box (EEG-t): where triggers of presentation program and recording are integrated.
- EEG Charger (EEG-c): charges the EEG battery pack(s)
- EEG battery (EEG-bat): there are two batteries: always keep the other battery charged.
- EEG Cap (EEG-c): caps are in the drawers (todo).
- EEG bundles (EEG-bun): electrode bundles: handle with care!
- EEG Optical cable (EEG-opt): thin orange cable that connects EEG-a to EEG-t).

### PC's
- [Presentation PC](todo:Specs) (stimuli)
- [Recording PC](todo:specs) (bio-signals, triggers from Presentation PC, other recordings)

### Displays (screens)
- Presentation screen A (experimenter)
- Presentation screen B (cabin)
- Recording screen A (experimenter) 
- Recording screen B (for the experimenter, inside or outide the cabin, portable screen).

### Audio components
- Speakers A (left channel), B(center, summed mono channel) and C (right channel)
- Crimson 3 monitoring/talkback interface (standalone mode)
- HP4 Headphone amplifier
- MP3 player (for masking sounds)
- Direct Input (DI) + channel switch box (don't touch)
- Mono summing box (DI)
- Stimulus PC sound card
	
#### Audio cables
- F/M XLR, balanced mono audio signals (speakers A, B, C and up to 2 microphones)
- M/F jack (stereo headphone amplifier extension)
- M mini jack to M RCA L/R cable (connect MP3 player to RCA input of Crimson) 
- Mini jack to left/right XLR splitter (connect Presentation mini jack audio out to DI's ad speakers inside cabin
- Small XLR connectors (DI connections)
- Dual L/R M-M jack connector (connect the Headphone Amplifier to Crimson)

### Data cables/connectors
- Ethernet
- USB 2.0 extension
- USB 3.0 extension
- Display Port cables
- Display port to mini HDMI connector (portable screen)

	


PRES-USB1 | REC-USB-1 | EEG Amp | EEG trigger box | EEG Optical Cable | EEG bundle(s) | 
----------|-----------|---------|-----------------|-------------------|---------------| 
0         | 0         | 0       |                 |                   |               |
