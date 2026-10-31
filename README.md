# Modal Melody Generator – Max/MSP

An algorithmic melody generation system developed in Max/MSP, exploring the relationship between musical modes, randomness, and interactive music programming.

## Overview

This project generates randomized melodic sequences based on four musical modes: Dorian, Phrygian, Lydian, and Mixolydian.

Users can select a mode and adjust the tonic, tempo, and note duration. Generated melodies can be played within Max or output as MIDI messages.

The project explores how musical rules can be combined with algorithmic processes to produce varied melodic results.

## Features

- Four selectable musical modes
- Randomized melody generation within modal scale constraints
- Adjustable tonic, tempo, and note duration
- MIDI note output
- Internal audio playback using basic synthesis

## Technologies

- Max/MSP
- Algorithmic composition
- MIDI sequencing
- Basic audio synthesis
- Music theory and modal scales

## Implementation

The patch uses `umenu` and `coll` to manage modal scale selections, `random` and `counter` for sequence generation, and `metro` for timing.

MIDI-related objects such as `makenote` and `noteout` handle note events, while `mtof`, `cycle~`, and `ezdac~` support internal audio playback.

## Project Files

- [Max Patch](Modal_Melody_Generator.maxpat)
- [Project Documentation (Japanese)](Project_Description.pdf)

## Future Improvements

Potential improvements include weighted note selection, more structured rhythmic patterns, phrase generation, and expanded sound synthesis controls.

## About

Developed as a coursework project at Tokyo College of Music, Music Business and Technology (MBT).

This project represents my exploration of generative music, music programming, and algorithmic composition.
