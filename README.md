# One Guitar Band

One Guitar Band is a real-time stand alone application that allows a guitarist to produce a full orchestration using only a standard electroacoustic or electric guitar.
The system incorporates several sound production functionalities, including that of a looper. At each repetition of the loop, the user can interact with either one of the following sound production mechanisms:
- Drum production: by tapping the guitar in a certain manner, the user can trigger drum samples (or cymbals) and arange them in time to compose the rhythmic part.
- Bass production: by playing a melodic line on the first three strings of the guitar (from E1 to A2), the user can produce a bass line.
- Modulation: the user can modulate the amplitude and frequency of a prerecorded guitar layer, so as to produce rhythmic and melodic patterns of unique sonic chatacter.

## Important attributes
- Up to 4 different Guitar, Modulation, Drums and Bass layers can be generated.
- The sound of Drums, Cymbals and Bass can be customized to a large degree through wavetable selection and sound synthesis parameter tuning.
- Once recorded, Drums and Bass elements are represented by a symbolic sequence (something like MIDI) with notes, onsets and velocities. 
- Post processing: optionally the user can correct any temporal inaccuracies by quantizing the Drums and Bass sequence.
- Load and save functionalities: the user can save all system settings and recorded/produced instruments. At a later point, he/she can recall that data to continue working on the composition.
- Exporting to DAW: selected layers from selected instruments can be exported as .wav files. The user can then import these files in the DAW of his/her preference to work towards the final production.
- Transitions: Settings can be instantly modified with the click of a single button on the GUI or from an external MIDI device.
- Flexibility: All functionalities can be controlled from the GUI, most important functionalities can be triggered also from an external MIDI controller. 

## Requirements
- Windows 10 or 11
- An ASIO sound card with at least two inputs and two outputs
- 48kHz sampling rate
- Buffer size of 64 samples or higher  

## One Guitar Band Version 1.0

This repository contains a first release of One Guitar Band as a standalone WINDOWS application.  The application will run with limitations, but we can offer a completely unlocked version to a limited number of users for FREE. This offer is for a limited number of users and a first-come first-served approach will be followed.  

## Trial limitations

- Trial expires on: December 31, 2026
- Short muting occurs every 18 seconds
- No exporting to DAW functionality

## Download (no installation required)

- Go to the Releases section and download 'OGB.zip'.
- Unzip the folder and save it somewhere on your hard disk, e.g. in C:\. Avoid saving it in C:/Program Files as this location has restricted writing access!
- Double click AppPublic.exe inside the OGB folder to run the program.

## Access to the unlimited version
- At the lower left corner of the GUI your machine ID will be printed. Send us an email with this number (including the "-" sign, if there is one) at onegtrband@gmail.com.
- When notified so by email, download AppPublic.exe once more and use it to replace the existing one in your hard disk. The application will then run without any limitations. 

## User Guide

[Download the Greek version of the User Guide](docs/OneGuitarBand_userGuide_GR.pdf)

## Third party libraries
One Guitar Band incorporates and relies on several excellent open-source libraries:
- JUCE – Cross-platform C++ framework used for audio processing, user interface development, and audio device management.
- RTNeural – Lightweight neural network inference library used for real-time machine learning processing.
- Signalsmith Stretch – High-quality time-stretching and pitch-shifting library used for audio transformation.
