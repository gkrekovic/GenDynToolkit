GenDynToolkit
=============

Introduction
-------------

This is comprehensive toolkit for controlling the sound synthesis process using the dynamic stochastic technique devised by Iannis Xenakis. The package contains the following abstractions:
+ **gendyn~** - a native and straightforward implementation of the basic dynamic stochastic snyhtesis (DSS),
+ **audio2gendyn~** - an algorithm for controlling the synthesizer using an input audio signal. Relevant audio features of an input signal are mapped to the synthesis parameters making the control immediate and intuitive,
+ **midi2gendyn~** - a polyphonic MIDI synthesizer based on DSS. The patch receives MIDI notes, velocities, and other controls, maps them into synthesis parameters, and employs sound units based on **gendyn~** to generate the sound.

Conceptual and technical details can be found in this publication: <br>
* Gordan Kreković, Davor Petrinović, "A Versatile Toolkit for Controlling Dynamic Stochastic Synthesis", Sound and Music Computing Conference, 2013.

Video Examples
--------------
Demonstration of the toolkit and highlights from the experiments mentioned in the paper are shown in the following
[video](http://www.youtube.com/watch?v=1Uk6KeglvnI).
