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

##3 Look for

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

## Recording audio

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

## Zooming






