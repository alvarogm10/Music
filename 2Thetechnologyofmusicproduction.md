---
title: The Technology of music production
---

# Week 1

## Nature of sound

### Propagation

- Sounds moving through a media
- Different in materials
- Speed of sound 340 m/sec: 1 ft/ms and 1 mile/5 seconds
- Trying to emulate spaces
- Delay and reverb

### Amplitude

- Extent of the wave, how much the air compresses
- Longitudinal and Transverse
- dBSPL: Decibels of Sound Pressure Level, is a relative
- dBFS: Decibels of Full Scale. In the notebook is from 0db Maximum to negative scales.
- Loudness is a human perception, different as amplitude
- Dynamic plugins: Expanders, gate, limiters, compressors
- Dynamic range is the range between the noise floor (hiss), sound and noise distortion.

### Frequency

- Sense of pitch is different than frequency
- How fast is the wave vibrating
- Amplitude and frequency are independent
- Timbre: Frequencies, partials and sine waves
- EQ: Booster, filter to manipulate the timbre
- 20Hz to 20kHz, auditive range.
- Masking, Fletcher munson, psycho acoustics, phantom fundamentals

### Visualizing sound

* Osciloscope: Time scale in X and amplitude in Y
* Spectrum analyzer: Horizontal frequency and vertical amplitude
* Spectogram/Sonogram: Represents the changes in time

### Look for

Timbre,partials
Masking,Fletcher munson curves,psycho acoustics, phantom fundamental.

## Microphones and Cables

### Connections overviews

Sound source -> Input transducer: Mic -> Low level audio signal: Balanced XLR -> Audio interface - MIC preamp - Line level audio signal - A/D converter -> Binary -> USB -> DAW -> USB - > Interface -> D/A -> igh level -> Output transducer -> Speaker

### Microphone as a transducer

* Sound pressure in the air as a voltage variations in a wire.

### Microphone types

* Dynamic: 
	- On stage
	- Doesn not require external power
	- MS 58, to vocals

* Condenser:
	- On studio
	- Sensitive
	- Require external power
	- Recommended for studio
	
### Microphone frequency response

* Dynamic:
	- Gain in vocals
* Condenser:
	- Try to pick every frequency, flat response
	
### Microphone polar patterns

What areas are picked up well.
Cardioid:
Super cardiod:
Hyper cardioid:
Omnidireccional:
Figurate:

Changing the direccion, will change the prequency response.
	
### Microphone placement

Most important thing
Try and find best audio
Hint: Point the logo to the sound source

### Line level and gain staging

Line level: Specific level where all the signal work.

+4: Studio level  
-10: Consumer level

Microphone pre-amp amplifies a low signal up to the standard level

Reccomendation: Raise the signal to line level once. Do not lower te signal and then amplify it again or viceversa.

### Cables

- Whenever is a problem, check the cables.

- 1/4" , also know as TS and Instrument cable. Unbalanced.
	- Susceptible to noise, as short as posible
	
- TRS: Two conductors and a shield. For headphones mainly, "stereo cable". Susceptible to noise. Could be used as a Balanced

- XLR: Designed for microphones, not stereo. Balanced.

Balanced cable: Rejects noise,requires two conductors with a shield

Direct box: Converts an unbalanced cable into a balanced signal.

1/8"

RCA:

## Signals and Additional Information

### Interfaces

* Microphone pre-amp
* PAD: Attenuation

### Microphone connection and Gain

* Be careful
* Avoid the feedback

1. Reduce the input gain all the way down
2. Turn phantom-power off before connecting into the interface
3. Connect female end first into the mic, and then male into the interface 
4. Turn phantom-power on
5. Set the level for the recording
	* Nice level signal
	* Do not get distortion
	* Find the highest volume of the recording
	* Be on the "yellow" range (3/4) never on the top
	* Find the monitor 
	* Set a little bit lower, because in performance could get higher levels
6. Turn off monitors before disconnecting something
7. Turn mic gain all way down
8. Turn off phantom power 
9. Turn off

### Analog to Digital converter

* Computer understand binary
* Instrument signals are analog
* Quantization and Sampling
	-Taking a very small piece of audio

### Pick up connections

* For guitars and basses

#### Option 1

Guitar -> 1/4 Ts" cable -> Audio interface

- Not as the same as line level

It is necessary a special designed input, called as:
	* Instrument input
	* Direct input
	* High Z input
	* High impedance input

Issues: It gets some delay (latency)

#### Option 2

Guitar -> 1/4 Ts cable -> Guitar or bass amp - > Mic -> XLR Cable -> Audio interface in MIC input

- Great option, takes the sound of the amp
- Get some sound of the room, sometimes hard

#### Option 3

Guitar -> 1/4 TS" cable -> Amp -> Line out -> 1/4 Ts cable -> Line in

* Not connect speaker outputs into an interface

#### Option 4

Guitar -> 1/4" TS Cable -> Direct Box -> Amp
				      -> XLR cable -> Audio Interface 	

Direct box: Get the correct impedance

Helps from the noise

#### Option 5

Add to Option 4 a second signal of the amp into the interface

### DAW

* Get a speakers for studio situations
* Powered speakers

# Week 2

Pre production: Composing and getting ideas, planning the performance
Production: Recording of the performance
Post pruduction: DAW, editing, mixing and mastering

## DAW

### Analog to digital conversion

* Binary -> bit "0" and "1"
* CD Standard 16-bit
* Studio 24-bit
* More bits -> more dynamic range
* Good for recording because at lowlevel is going to be a good recording
* Reccomended at 24 bit

* Sampling rate: Higher rate -> higher the frequency that one could record.
* Nyquist -> Half of the sample rate
* Audio CD 16-bit. 44100 samples/sec
* Videos -> 48000 
* Suggestion using 48000. in order to work with another people

### Buffer size

* How large the chunk of audio measurement is stored previously in the computer, number of audio samples waiting to get to the D/A converter in order for player to hear themselves while recording.

* Lowering buffer size -> reduces latency -> but also reduces the number of plugins that can be used.
* Raising buffer size, increase latency and increase the number of plugins that can use.

* While recording use a low buffer size, try 128 samples.
* During post production, raise buffer size to 1024, when necessary.
* Freezing a track 
* Plugins affect CPU 

* Delay = Buffer size / Sample rate
* < 20 ms , delay

### File types

Data compression -> loss less
Audio compression -> 

* Using highest possible quality when recording
* WAV. AIFF file. Better quality as uncompressed
* Broadcast wave files -> stores more metadata if crashes - BWF

* Interleaved files: Contains both left and right audio channels in a single file.

### Project folder

* Folder 

### Project checklist

* Proper Project name and Location
* Digital Audio Preferences
* Recording File Type
* Hardware settings

## Tracks, files and editing

Audio tracks:
MIDI tracks:
Auxiliary tracks:
Instrument track: listen to midi -> output something
Global track: Tempo, meter, markers

### Recording audio

* Create track: mono or stereo. Mono is most of the times
* Name track immediately after creating a track.
* Levels
* Click track
* Count off

- Check your settings
- Create a track (remember mono or stereo)
- Name the track
- Record enable the track
- Set levels using the microphone preamp
- Enable the click and countoff
- Record

### Zooming

### Trimming

* Best to rehearse more and then record -> Save a lot of time on editing.
* Clip audio
* Audio file and a region or a clip.
*Changing regions -> non-destructive

### Separating and cutting

Split and cut a region

### Nudging

* Moving a region back and forth

### Grid

* Snap
* Resolution of the grid

### Fades

* When cutting is generating Hi-Frequency pop
* Cut when point is zero is better -> Check DAW
* Fades helps to avoid the pops

* Crossfades when overlapping 
* First region comes down when second goes up 

### Cycling

* Setting the loops

### Merging

* Type to destructive editing, as is writing a new audio file.
* Known as merging or consolidating.
*If the track is ready, is good to do it.

### Naming and coloring

* Handy to name and colouring the regions

### Markers

Markers are for specific location of the songs.
*Generally in global tracks.

### Comping

* Creating a perfect performance form a series of imperfect takes.
* Also applies crossfades
* A shorter crossfade is always better
* Use merge at the end


### Destructive editing

* Normalizing: 
* Reverse:

Careful because could change the sounds of another poroject, if the file is linked.

### Notes

Non-destructive editing: The clip or region is changed but the referenced audio files is unchanged

## MIDI

- Score of a the computer
- Musicial Instrument Digital Interface
- Midi channels, 1 to .16
- Common midi messages 
	* Note on/off
	* Control change
	* Pitch bend
- Velocity: How "hard" the key is hit

- Two data words of a note-on message indicate: Velocity and note number. 7 bit numbers each.
- "Panic", send all notes off
- "Sustain", is conreol channel 64
- "Channel pressure", after touch.
- Sampler: Plays back pre-recorded audio.
- Sinthetizer: Creates sound from geometric waveform or formula.

### MIDI Controllers

- Some of them use drivers
- 5 pin MIDI Midi cable
- Cable USB - Bidireccional capability
- Pitch
- Modulation - Control change 1
- Change functionality from 1 to 127
- 

### Software Instruments

- Plugin / insert
- Virtual instrument

### MIDI Editing: Velocity

- Adjusting relative volume
- Most synths will change volume with velocity

### MIDI Quantization

- Natural performance is sometimes "sloppy"
- Quantization, repairs it depending on the groove.
- Set grid, usually 16. Best to check out how is the shorter note.
-Reccomend, go to the MIDI track, repair notes, and then quantization.
-Quantization strenght:  by default 100% goes to the grid perfectly. 
- Reccomended using 20% QS, then do it repeatedly until is a tight sound and not too "robotic". 

### Common MIDI recording and editing functions:

Overdub

### Wrap-up





