## STR-500: The Manual

- To-do: make a video version of this manual, add pictures to this

### Powering on
Plug in the power socket. The STR-500 is usually supplied with a 5v power supply, though you can use anything between 5-12v so long as it is center positive (don't use a guitar pedal power supply!). 

Flip the power switch to turn on. It takes about 3 seconds for the instrument to boot, and the LED should turn on when it's ready to go.

### Audio input and output
Audio input and output is **line level only**. I would suggest using the instrument in conjunction with a mixer. It works well to send audio via an aux send from the mixer into the STR-500 and then out from the instrument into a channel on the mixer. In any case any audio input will need to be at line level to work properly, and the outputs will not work correctly with headphones. The inputs and outputs are unbalanced (but balanced cables work fine).

Both input and output use dual mono 1/4" jack sockets. The left sockets are normalled to the right, so if nothing is plugged into the right socket then the signal is flattened to mono. That way you can have stereo input or output or both. 

Even if you record a mono signal, the audio processing includes a small amount of stereo width. So it can sound nice to use both output jacks into a stereo channel even if you are only sampling a mono signal. 

### Calibrating the string
The basic premise of the STR-500 is that the string is mapped directly to the time domain of a sample. Pulling the string scrubs through a recorded sound from beginning to end. The range of pulling the string can be calibrated. This is achieved by setting a minimum and maximum. These correlate to the beginning and end of the recorded sample.

On startup, the current location of the string is set to the beginning of the sample. This means that if you pull out the string a bit, or tie it to something, and turn on the instrument, the current location of the string will be mapped to the beginning of the sound. 

By default the maximum is set to the end of the string, so the end of the sound is played when the string is fully pulled out, around 3m. This is very long! 

You will likely want to calibrate the string each time you start it up. You do this by pulling the string to the desired minimum or maximum location and then pressing the corresponding calibration button. The LED should flash when you press the button. You can press these buttons in any order, and you can change them anytime you like (a new range will be applied instantly to the same recorded sample). 

Once you have calibrated the maximum, pulling the string beyond this maximum will result in the sound fading away. 

At the minimum setting, the playback will be just at the beginning of the sample - this can sound a bit jittery or robotic until you pull the string, depending on the characteristic of the recorded sound. 

### Recording a sample
Press and hold the "record" button to record a sample. The LED should flash when you start and stop recording. You can a record a maximum of 10 seconds. At the end of the 10 seconds the recording just stops (it does not loop record). 

*note: this button does not work if anything is plugged into the recording footswitch input*

### Playing the sample
Press and hold the "play" button to trigger playback. Press and hold the button and then pull the string to scrub through the sound.

*note: this button does not work if anything is plugged into the playback footswitch input*

### Footswitch inputs
Recording and playback can also be triggered via the footswitch inputs. These are 1/4" jack sockets above the audio inputs on the back of the device. The jack socket above the input sockets is the footswitch input for recording, and the socket above the output sockets is the footswitch input for playback.

Plugging anything into the footswitch recording socket will bypass the record button, and plugging anything into the footswitch playback socket will bypass the playback button. 

The footswitch inputs are just designed for simple switches. This means that most standard footswitches should work, though you may need to set them to "normally off". Also, any passive switch connected to a 1/4" cable will work, so you can make your own toggle switches or tilt switches or anything else you can imagine. 

Generally speaking there are two types of footswitches, momentary and latching. Momentary switches complete a circuit only whilst they are held down, while latching switches stay on with one press and are turned off with a second press. Both recording and playback work well on the STR-500 with momentary switches (these replicate the button pressing on the lid exactly). A latching switch can be fun to use on playback, as it means sound is constantly playing and you can just record new samples on the fly without worrying about playing back. 

However, I would advise against using latching switches on recording, because there is no loop recording on the STR-500. Therefore you would need to press the button once to record and a second time to stop. If you leave it on for ten seconds you will fill up the recording buffer and then have to press the button *twice* to stop recording and then start recording again. It will work, technically, but I'm pretty sure it's not a good idea in virtually every case.

### Filter and pitch switches
Two toggle switches on the lid control the filter and pitch controls. When these are switched on the X and Y position of the string are mapped to filter (X) and pitch (Y). 

The filter is a standard low-pass filter with a bit of resonance. When activated, moving the string left and right should give you a full frequency sweep from around 70 to about 14k hertz.

The pitch range is quite broad, moving the string backwards brings the pitch below the original recording and pushing it forwards brings it up higher than the original.  