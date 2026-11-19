# Yatai-1 (屋台)
YES IK WE ARE SUPPOSED TO PUSH TEH CODE NOT THE BUILD 
SHUT UPPASFADFADF
This was my attempt at cloning Sylenth1. It's not very good, but it's a humble attempt.

Yatai-1 is a subtractive synth with a cream-and-purple, screen-printed guitar-pedal look. It comes as a VST3 instrument for your DAW and as a standalone Windows app.

## What's in it
- 2 parts (A and B), each with 2 oscillators: Saw, Pulse, Triangle, Sine, HPulse, QPulse, TriSaw and Noise, with up to 8 unison voices each
- A filter per part (lowpass, highpass, bandpass, notch; 12 or 24 dB) with drive, warm drive and keytracking
- An amp envelope per part, 2 mod envelopes, 2 LFOs and 2 misc mod sources (velocity, mod wheel, keytrack and more), all routable to cutoff, resonance, pitch, volume, pan and more
- Poly or mono mode, legato, portamento and pitch bend
- An arpeggiator, plus distortion, phaser, chorus, EQ, delay, reverb and compressor
- 12 presets

## VST3 plugin
1. Download `Yatai-1-VST3-win64.zip` from the Releases page and unzip it.
2. Copy the `Yatai-1.vst3` folder into `C:\Program Files\Common Files\VST3`.
3. Rescan plugins in your DAW. Yatai-1 appears as an instrument from "Yatai Audio".

Every control can be automated, your settings are saved with your project, and the arpeggiator, tempo-synced LFOs and delays follow your DAW's tempo.

## Standalone app
1. Download `Yatai-1-standalone-win64.zip` from the Releases page and unzip it.
2. Run `Yatai-1.exe`. Use **Options** in the top-left corner to choose your audio output and MIDI keyboard.
3. Play with the mouse, a MIDI keyboard, or your computer keys: A W S E D F T G Y H U J K, with Z and X to change octave.

You need Windows 10 or 11 with the Microsoft Edge WebView2 runtime, which comes with Windows 11. Both are 64-bit only. The standalone app isn't code-signed, so Windows SmartScreen may warn you the first time you run it. Click **More info**, then **Run anyway**.

Built with JUCE 8. Sylenth1 is a product of LennarDigital. This project isn't affiliated with or endorsed by them.
