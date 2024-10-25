
# Project 4 - DJ Software using OSC and Pure Data

## Members
Kevin Pérez

## Overview

**Project 4** is a DJ software system developed using **Pure Data (PD)** in combination with the **OSC Controller app (Open Sound Control)**. The software allows users to interact with a set of widgets (sliders and buttons) within the OSC app to create electronic music pieces, simulating the experience of a live DJ performance. Each widget interaction results in an auditory response in Pure Data, controlling various aspects of sound synthesis and playback.

## Features

- **Automatic Sound Switching with Grid Buttons**: The patch `pd controller` listens to **grid buttons 1 to 5**, automatically changing the bass sound. The bass can be activated via toggles.
- **Bass Sound Generation**: The patch `pd bass` generates bass sounds, which are controllable via:
  - **Slider 4**: Controls the bass volume.
  - **Slider 1**: Controls the metronome for the bass.
  - **Grid Buttons**: Control parameters such as **decay**, **pitch**, **filter**, and **sine wave** modulation.
  
- **Clap Sound Generation**: The patch `pd clap` functions similarly to `pd bass`, but it is used for controlling the clap sound. 
  - **Toggles**: Keeps the clap sound constantly playing.
  - **Grid Buttons**: Changes the clap sound. They can also trigger a single clap sound on demand.

- **Single-Use Sound Triggers**: The patch `pd sounds` allows single sounds to be triggered using buttons or grid buttons.
  
- **Loop Sound Control**: The patch `pd loop` plays a looping sound that can be toggled on/off using **toggle 1**. 
  - **Slider 3**: Controls the loop volume.
  - **Slider 2**: Controls the loop's metronome.

## Setup Instructions

1. **Download and Install Pure Data**:  
   Ensure that you have Pure Data (PD) installed on your machine. You can download it from the official website:  
   [https://puredata.info/downloads](https://puredata.info/downloads)

2. **Install OSC Controller App**:  
   The system is controlled using the OSC Controller app. Make sure to download it from your app store and configure it according to the settings needed for this project.

3. **Patch Loading**:  
   Open Pure Data and load the following patches into the PD environment:
   - `pd controller`
   - `pd bass`
   - `pd clap`
   - `pd sounds`
   - `pd loop`

4. **OSC Configuration**:  
   Ensure that the OSC Controller app is connected to Pure Data over the same network, and all widgets in the layout (sliders and buttons) are configured to send OSC messages correctly.

## Usage

- **Widgets**:
  - **Sliders**: Control aspects like volume, metronome timing, and sound parameters.
  - **Toggles**: Activate or deactivate continuous sound playback for bass and clap.
  - **Grid Buttons**: Change sound characteristics (decay, pitch, filter) and trigger sounds (single or looped).

- **Sound Modules**:
  - The **bass** and **clap** modules allow detailed sound control for creating electronic music.
  - The **single sound** and **loop** modules offer additional sound triggers and looping capabilities, making it ideal for live DJ performance.

## Dependencies

- Pure Data (PD)
- OSC Controller App

No additional external libraries or dependencies are required.

## License

This project is distributed under the MIT License. See `LICENSE` for more information.

## Credits

Project developed by [Your Name]. Special thanks to the creators of Pure Data and the OSC Controller app for providing the tools that made this project possible.

---

Feel free to adjust any of the sections or include additional details specific to your project!Here is a README draft based on the details you've provided for "Project 4," your DJ software using OSC and Pure Data:

---

# Project 4 - DJ Software using OSC and Pure Data

## Overview

**Project 4** is a DJ software system developed using **Pure Data (PD)** in combination with the **OSC Controller app (Open Sound Control)**. The software allows users to interact with a set of widgets (sliders and buttons) within the OSC app to create electronic music pieces, simulating the experience of a live DJ performance. Each widget interaction results in an auditory response in Pure Data, controlling various aspects of sound synthesis and playback.

## Features

- **Automatic Sound Switching with Grid Buttons**: The patch `pd controller` listens to **grid buttons 1 to 5**, automatically changing the bass sound. The bass can be activated via toggles.
- **Bass Sound Generation**: The patch `pd bass` generates bass sounds, which are controllable via:
  - **Slider 4**: Controls the bass volume.
  - **Slider 1**: Controls the metronome for the bass.
  - **Grid Buttons**: Control parameters such as **decay**, **pitch**, **filter**, and **sine wave** modulation.
  
- **Clap Sound Generation**: The patch `pd clap` functions similarly to `pd bass`, but it is used for controlling the clap sound. 
  - **Toggles**: Keeps the clap sound constantly playing.
  - **Grid Buttons**: Changes the clap sound. They can also trigger a single clap sound on demand.

- **Single-Use Sound Triggers**: The patch `pd sounds` allows single sounds to be triggered using buttons or grid buttons.
  
- **Loop Sound Control**: The patch `pd loop` plays a looping sound that can be toggled on/off using **toggle 1**. 
  - **Slider 3**: Controls the loop volume.
  - **Slider 2**: Controls the loop's metronome.

## Setup Instructions

1. **Download and Install Pure Data**:  
   Ensure that you have Pure Data (PD) installed on your machine. You can download it from the official website:  
   [https://puredata.info/downloads](https://puredata.info/downloads)

2. **Install OSC Controller App**:  
   The system is controlled using the OSC Controller app. Make sure to download it from your app store and configure it according to the settings needed for this project.

3. **Patch Loading**:  
   Open Pure Data and load the following patches into the PD environment:
   - `pd controller`
   - `pd bass`
   - `pd clap`
   - `pd sounds`
   - `pd loop`

4. **OSC Configuration**:  
   Ensure that the OSC Controller app is connected to Pure Data over the same network, and all widgets in the layout (sliders and buttons) are configured to send OSC messages correctly.

## Usage

- **Widgets**:
  - **Sliders**: Control aspects like volume, metronome timing, and sound parameters.
  - **Toggles**: Activate or deactivate continuous sound playback for bass and clap.
  - **Grid Buttons**: Change sound characteristics (decay, pitch, filter) and trigger sounds (single or looped).

- **Sound Modules**:
  - The **bass** and **clap** modules allow detailed sound control for creating electronic music.
  - The **single sound** and **loop** modules offer additional sound triggers and looping capabilities, making it ideal for live DJ performance.

## Dependencies

- Pure Data (PD)
- OSC Controller App

No additional external libraries or dependencies are required.

