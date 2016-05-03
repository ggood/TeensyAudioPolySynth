# TeensyAudioPolySynth
A very simple polyphonic MIDI synthesizer based on the Teensy  microcontroller with the Teensy Audio Board.

You'll need a Teensy 3.0/3.1/3.2 microcontroller, with a
Teensy Audio Board. See http://pjrc.com/.

Connect the Teensy (with the Audio Board attached) to your computer
with a USB cable.

Add teensyduino support to your Arduino IDE. Instructions on doing
that are here: https://www.pjrc.com/teensy/teensyduino.html

Make sure the Tools->Board setting in your Arduino IDE is correct
for the type of Teensy you have, and that Tools->USB Type is
set to "MIDI". Load, compile, and upload this sketch.

Connect a MIDI keyboard to your computer with a USB cable.

Start up your digital audio workstation, e.g. Ableton Live, Cubase,
etc., and make sure that the MIDI device "Teensy MIDI" is set up
so that MIDI messages from the MIDI keyboard are routed to it.

Plug headphones into the Teensy Audio board and play on the keyboard.
You should hear sawtooth waveforms.
