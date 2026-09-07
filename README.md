# One Guitar Band

One Guitar Band is a real-time stand alone application that allows the user to produce complete musical arrangements using only a guitar and a computer.
The system incorporates several sound production functionalities, including that of a looper. At each repetition of the loop, the user can interact with either one of the following sound production mechanisms:
- Guitar production: perform a mono or stereo recording of the guitar sound.
- Drum production: stimulate the guitar through percussive gestures to produce drum samples (or cymbals) and arange them in time to compose the rhythmic part.
- Bass production: single notes played on the first three strings of the guitar (covers the range from E1 to A2) are transformed into bass sound.
- Modulation: a prerecorded guitar layer can be modulated in amplitude and/or in frequency, so as to produce rhythmic and melodic patterns of unique sonic chatacter.

## Important attributes
- The program works with any ordinary acoustic or electric guitar.
- Up to 4 different Guitar, Modulation, Drums and Bass layers can be generated.
- The sound of Drums, Cymbals and Bass can be customized to a large degree through wavetable selection and sound synthesis parameter tuning.
- Post processing: optionally the user can correct any temporal inaccuracies by quantizing the produced Drums and Bass sequence.
- Load and save functionalities: the user can save all system settings and recorded/produced instruments. At a later point, he/she can recall that data to continue working on the composition.
- Exporting to DAW: selected layers from selected instruments can be exported as .wav files. The user can then import these files in the DAW of his/her preference to work towards the final production.
- Song Sections: Settings can be instantly modified with the click of a single button on the GUI or from an external MIDI device.
- Drum model customization: through a simple training procedure, the user can specify custom gestures for the drum production model.
- Flexibility: All functionalities can be controlled from the GUI, most important functionalities can be triggered also from an external MIDI controller. 

## Requirements
- Windows 10 or 11
- An ASIO sound card with at least two inputs and two outputs
- 48000 or 44100 Hz sampling rate
- Buffer size of 64 samples or higher  

## One Guitar Band Version 1.0

This repository contains a first release of One Guitar Band as a standalone WINDOWS application.  The application will run with limitations, but we can offer a completely unlocked version to a limited number of users for FREE. This offer is for a limited number of users and a first-come first-served approach will be followed.  

## Trial limitations

- Trial expires on: December 31, 2026
- Short muting occurs every 18 seconds
- Export and Save functionalities are disabled

## Download (no installation required)

- Go to the Releases section and download 'OGB.zip'.
- Unzip the folder and save it somewhere on your hard disk, e.g. in C:/. Avoid saving it in C:/Program Files as this location has restricted writing access!
- Double click OneGuitarBand.exe inside the OGB folder to run the program.

## Access to the unlimited version
- At the lower left corner of the GUI your machine ID will be printed. Copy the machine ID and send it to us at onegtrband@gmail.com.
- Within 24h you will be notified by email to download OneGuitarBand.exe once more and use it to replace the existing one in your hard disk. The application will then run without any limitations. 

## User Guide

[Download the User Guide](docs/OneGuitarBand_userGuide_GR.pdf)

## Third party libraries
One Guitar Band incorporates and relies on several excellent open-source libraries:
- JUCE – Cross-platform C++ framework used for audio processing, user interface development, and audio device management.
- RTNeural – Lightweight neural network inference library used for real-time machine learning processing.
- Signalsmith Stretch – High-quality time-stretching and pitch-shifting library used for audio transformation.
