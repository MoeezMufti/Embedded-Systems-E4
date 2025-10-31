# Embedded-Systems-E4

## Overview
This project extends a basic traffic light system to include **pedestrian lights and a button**. Pressing the button requests a crossing, switching traffic and pedestrian lights safely.

## Features
- Traffic light: **Red, Yellow, Green**  
- Pedestrian light: **Red and Green**, synchronized with traffic lights  
- Button-triggered pedestrian crossing: activates **3s after press** or at normal Green duration  
- Timing: Green = 10 units, Yellow = 5 units  

## Structure
/docs -> UML diagrams (class, state machine, sequence)
/arduino -> Arduino code (.ino)
/simulation -> Tinkercad/Wokwi simulation files

## Usage
1. Open `.brd` file in Arduino IDE or Tinkercad/Wokwi.  
2. Connect LEDs and button to specified pins.  
3. Upload or start simulation.  
4. Press button to test pedestrian crossing behavior.  

## Authors
- `Moeez Mufti`  
- `Muhammad Ali`
- `Talha Khan`
