# MIDI File Creation Project

## Overview
This project focuses on creating a MIDI file, specifically tailored for generating a drum and bass type beat. It utilizes the Python library `mido` for MIDI file manipulation and creation.

## Prerequisites
To run the scripts included in this project, you need to have Python installed on your system along with the `mido` library. You can install `mido` using pip:

```bash
pip install mido
```

## MIDI File Structure
The script creates a MIDI file with the following structure:

- **Time Signature:** Sets the rhythmic structure (e.g., 4/4 time).
- **Set Tempo:** Defines the tempo of the beat in beats per minute (BPM).
- **Drum Notes:** MIDI note events for various drum sounds (based on General MIDI standard).

Note: SMPTE Offset, Instrument Name, and Key Signature meta messages are not included as they are not essential for a basic drum track.

## Customization
You can customize the drum patterns by editing the note events in the `DnBMidi.ipynb` script. Refer to the General MIDI Level 1 Percussion Key Map for MIDI note numbers corresponding to different drum sounds.
