GenDynToolkit
=============

Introduction
-------------

This is comprehensive toolkit for controlling the sound synthesis process using the dynamic stochastic technique devised by Iannis Xenakis. The aims of the toolkit are:
+ To provide a native implementation of the synthesizer in Pure Data that can be easily modified or extended,
+ To demostrate how to control synthesis parameters,
+ To implement and demonstrate an innovative approach to controlling synthesis parameters using an input audio signal and its relevant features,
+ To implement and demonstrate a polyphonic MIDI synthesizer based on this non-standard synthesis technique.

Conceptual and technical details can be found in this publication: <br>
* Gordan Kreković, Davor Petrinović, "A Versatile Toolkit for Controlling Dynamic Stochastic Synthesis", Sound and Music Computing Conference, 2013. ([download] (https://github.com/gkrekovic/GenDynToolkit/raw/master/A%20Versatile%20Toolkit%20for%20Controlling%20Dynamic%20Stochastic%20Synthesis.pdf))

What's in the package?
-------------

The package contains the following abstractions:
+ **gendyn~** - a straightforward implementation of the synthesizer,
+ **audio2gendyn~** - an algorithm for controlling the synthesizer using an input audio signal,
+ **midi2gendyn~** - a polyphonic MIDI synthesizer based on DSS.
 
Additionally, there are several examples that represent typical use cases:
+ **gendyn_gui** - direct parameter control using sliders,
+ **gendyn_automation** - parameter automation using tables,
+ **gendyn_midi_control** - MIDI-cotrolled polyphonic synthesizer with a reverb,
+ **gendyn_audio_control_adc** - implicit parameter controll from input audio,
+ **gendyn_audio_control_adc** - implicit parameter controll from input audio

Prerequisites
--------------

+ Pd extended
+ [timbre ID] (http://williambrent.conflations.com/pages/research.html) library developed by Wiliam Brent (only for patches containing the objects for audio extraction)


Video Examples
--------------
Demonstration of the toolkit and highlights from the experiments mentioned in the paper are shown in the following [video] (https://www.youtube.com/watch?v=1Uk6KeglvnI).
