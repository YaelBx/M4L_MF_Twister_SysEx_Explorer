# MaxForLive - MF Twister SysEx Explorer
Format SysEx &amp; configure your MF Twister directly from MaxMSP / MaxForLive.

![MF Twister SysEx Explorer GUI](resources/Device.png)

## Versions
Ableton Live 11

Max 8.1.11

## Changelog
17 Feb 2022 - version 1

## Description
SysEx format/packet were reversed engineered based on MF Utility logs and MF Twister firmware code (which can be found [here](https://github.com/DJ-TechTools/Midi_Fighter_Twister_Open_Source)).

Configure your MF Twister directly from MaxMSP / MaxForLive. Generated packet (in decimal format) are noted on the left of the device.
You can set your device directly by pasting the packets to messages and sending to your midiout object.

This device goal is to show you the SysEx packets needed if you want to create your own Max device in order to configure your MF Twister.

## Setup
Drag your device into a MIDI track, set your MF Twister as MIDI out. If well configured, pressing "Save & reset" should reset your device.

When sending a parameter, the device goes into a configuration mode (no color, no response) until the device is reset or unplugged.