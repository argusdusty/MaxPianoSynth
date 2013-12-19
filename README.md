MaxPianoSynth
=============
##A Physical-Model Piano Synthesizer for Max 6.1
This program was built for my UC Berkeley Music 158 final. It simulates all 88 piano strings, using the Karplus-Strong algorithm to simulate the string, with the hammer simulated using staggered low-pass filters over an initial impulse, and the soundboard simulated with a low-frequency low-Q resonator. Most of the tecnhiques [described here](https://ccrma.stanford.edu/~jos/pasp/Piano_Synthesis.html).

This software requires the [CNMAT externals](http://cnmat.berkeley.edu/downloads), and is distributed under the [MIT license](http://opensource.org/licenses/MIT).

Inputs can also be controlled by keyboard (keys) and mouse (pedals). See patch comments for details on the controls.

The m158.o.io patches for keyboard and mouse belong to the instructors of Music 158 - Rama Gottfried and Ilya Rostovtsev.

Thanks to Ilya Rostovtsev for assistance in creating this program.
