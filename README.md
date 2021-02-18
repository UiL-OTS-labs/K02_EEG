# K02_EEG
Docs for EEG setup in K02

# EEG setup K02

## Todo

- Overview documentation
- Test plans/reports pre-pilot
- Technical drawing (digital)
- Pictures of components
- Specs and connections/parts.


# Overview of setup
![image info](https://github.com/UiL-OTS-labs/K02_EEG/blob/main/baby-eeg/baby-eeg.001.png)
![captions](https://github.com/UiL-OTS-labs/K02_EEG/blob/main/baby-eeg/baby-eeg.002.png)
![infographic](https://github.com/UiL-OTS-labs/K02_EEG/blob/main/baby-eeg/baby-eeg.003.png)


## General

- Built as an infant EEG lab, but can be used for all ages (default description will be for caregiver + child participant) scenario.
- Participants are capped and connected with EEG equipment.
- Participant and caregiver will be inside the sound-proof cabin for an experiment. 
- Seating options (todo)
- Caregiver can wear a headphone with masking sounds, played on mp3-player and the Crimson 3 monitoring interface.
- Through the same Crimson 3 route, the parent can communicate with each other using the talkback option. Only if the experimenter presses the button, like an intercom. The microphone inside the cabin can be used by the caregiver. The Crimson is not connected to any PC, it works in standalone mode.
- In case of visual stimuli, the parent may use a pair of special polarised glasses, visually masking the display contents.
- There is a portable secondary screen available for inside (or outside) the cabin. A Display port to HDMI (and mini) HDMI connector cable must be used. After capping and/or signal checking inside the cabin, the display may be taken back to its charging place at the experimenter desk, or otherwise moved/closed.  


## System components

## Humans
- Participant
- Caregiver/parent
- Experimenter (and/or assistant)

## EEG system
- EEG Amplifier (EEG-a)
- EEG Trigger Box (EEG-t)
- EEG Charger (EEG-c)
- EEG battery (EEG-bat)
- EEG Cap (EEG-c)
- EEG bundles (EEG-bun)
- EEG Optical cable (EEG-opt)

### PC's
- Presentation PC (stimuli)
- Recording PC (bio-signals, triggers from Presentation PC, other recordings)
- Naming convention in tables for connections: PRES_USB_1/REC_USB_1, etc)

### Displays
- Presentation screen A (observer)
- Presentation screen B (booth)
- Recording screen (observer)
- Recording screen

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
- M mini jack (TRS) to dual mono M XLR Y-splitter cable
- M mini jack to M RCA L/R cable 

### Data cables/connectors
- Ethernet
- USB 2.0 extension
- USB 3.0 extension
- Display Port cables
- Display port to mini HDMI connector (portable screen)
- Mini jack to left/right XLR splitter
	

PRES-USB1 | REC-USB-1 | EEG Amp | EEG trigger box | EEG Optical Cable | EEG bundle(s) | 
----------|-----------|---------|-----------------|-------------------|---------------| 
0         | 0         | 0       |                 |                   |               |
