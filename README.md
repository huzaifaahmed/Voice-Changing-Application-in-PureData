# Voice-Changing-Application-in-PureData

A voice changer/sound changer application that can manipulate both live sounds and pre-recorded sounds/songs. Built using the graphical programming interface of PureData.

This voice changer features a number of different sound effects and innovations to produce interesting output sounds.

The sound effects included within this voice change include:

* High Pass Filter
* Low Pass Filter
* Reverberation
* Tremelo
* Vibrato
* Ring Modulation
* Frequency Shifting
* sound Mixer

Each sound effect can either be applied to the input signal individually or multiple sound effects can be applied at the  same time. To activate a sound effect click the "Active" check box of the corresponding sound effect you wish to activate. To de-activate a sound effect click this check box again. The parameters of each sound effect can be changed using the sliders within their graph-on parent selection areas. The default parameter values of a sound effect can be restored by clicking on it's corresponding "reset" bang. To view more information about each individual sound effect you can open it's sub patch. 

The "Display" area of the voice changer allows you to select the type of sound input you would like, with options to open a sound file or to input live using a microphone. This input sound has visual displays which show its rms decibel value and its waveform. Furthermore, there are options to reset, activate or inactivate all of the sound effects in one click.

The pre-set effects area allows recognisable voice features to be applied to an input sound. When one is selected certain sound effects are activated and their parameters are set to achieve the desired voice effect.

The sound visuals area oft he voice changer allows a 3-d visualization of the output sound to be seen that has been implemented using the PD Gem library. There are options here to open/close the visual window and settings to specify the x,y and z rotational co-ordinates of the 3-d object. Alternatively you can select the auto-rotate property by clicking the "auto-rotate" toggle.

The output sound signal can have it's volume level controlled in the bottom right of the voice changer using the "volume" slider.
A detailed look at the output sound's waveform and spectrum can be viewed by opening the "wsprobe" object.