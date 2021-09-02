MaxPianoSynth
=============
### A Physical-Model Piano Synthesizer for Max 8
This program was built for my UC Berkeley Music 158 final. It simulates all 88 piano strings, using the Karplus-Strong algorithm to simulate the string, with the hammer simulated using staggered low-pass filters over an initial impulse, and the soundboard simulated with a low-frequency low-Q resonator. Most of the tecnhiques are described [here](https://ccrma.stanford.edu/~jos/pasp/Piano_Synthesis.html).

This software requires the [CNMAT externals](http://cnmat.berkeley.edu/downloads), [Odot](https://github.com/CNMAT/CNMAT-odot), and [Music-and-Computing](https://github.com/CNMAT/Music-and-Computing), and is distributed under the [MIT license](http://opensource.org/licenses/MIT).

Inputs can also be controlled by keyboard (keys) and mouse (pedals). See patch comments for details on the controls.

Thanks to Ilya Rostovtsev for assistance in creating this program.
