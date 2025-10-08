# DC_micro-project

# Digital Modulation (ASK, FSK, PSK) Simulation in MATLAB

## Project Description

This project provides a comprehensive simulation and visualization of three fundamental digital modulation techniques: **Amplitude Shift Keying (ASK)**, **Frequency Shift Keying (FSK)**, and **Phase Shift Keying (PSK)** (specifically Binary PSK or BPSK). Developed in MATLAB, this simulation serves as a practical educational tool to understand how binary digital data (`0`s and `1`s) are encoded onto analog carrier waves for transmission over communication channels.

The script generates and plots the time-domain waveforms for the original binary message signal and each of the three modulated signals. This visual representation helps in grasping the core principles of how variations in a carrier's amplitude, frequency, or phase are used to convey digital information.

## Features

  * **ASK Simulation:** Demonstrates On-Off Keying (OOK) where the carrier is present for a binary '1' and absent for a binary '0'.
  * **FSK Simulation:** Illustrates how different carrier frequencies are used to represent binary '0' and '1', maintaining a constant amplitude.
  * **PSK Simulation (BPSK):** Shows how the phase of the carrier is inverted (180-degree shift) to distinguish between binary '0' and '1', keeping amplitude and frequency constant.
  * **Clear Waveform Visualization:** Generates a MATLAB figure with three subplots, each displaying the input binary data alongside the corresponding modulated waveform.
  * **Configurable Parameters:** Easily adjust carrier frequency, sampling rate, bit duration, and the input binary data directly within the script.
  * **Educational Value:** Provides a hands-on approach to understanding digital modulation theory and its practical application in telecommunications.

## Applications Illustrated

The report accompanying this project discusses typical real-world applications for each modulation type:

  * **ASK:** Optical Fiber Communication (OOK), Infrared Remote Controls.
  * **FSK:** Caller ID in telephony, low-speed modems, amateur radio.
  * **PSK (BPSK):** Wireless communication (Wi-Fi, Bluetooth, Cellular networks), satellite communication.

## Getting Started

### Prerequisites

  * MATLAB R2017a or newer (recommended).

### How to Run the Simulation

1.  **Clone or Download:**
     * Alternatively, you can simply download the `modulation_simulation.m` file directly.
2.  **Open MATLAB:** Launch the MATLAB application.
3.  **Navigate to Project Folder:** In MATLAB's "Current Folder" browser, navigate to the directory where you saved `modulation_simulation.m`.
4.  **Run the Script:**
      * Type `modulation_simulation` in the MATLAB Command Window and press Enter.
      * Alternatively, open the `modulation_simulation.m` file in the MATLAB Editor and click the "Run" button.

A figure window titled "Digital Modulation Waveforms" will appear, displaying the simulated waveforms.

## Code Structure

The `modulation_simulation.m` script is logically divided into the following sections:

1.  **Simulation Parameters:** Defines global variables for carrier properties, data properties, and time vectors.
2.  **Message Signal Preparation:** Prepares the binary input data for clear plotting alongside analog waveforms (e.g., NRZ format for PSK).
3.  **ASK Simulation:** Generates the Amplitude Shift Keyed signal.
4.  **FSK Simulation:** Generates the Frequency Shift Keyed signal.
5.  **PSK Simulation (BPSK):** Generates the Binary Phase Shift Keyed signal.
6.  **Plotting All Waveforms:** Uses MATLAB's `figure` and `subplot` functions to display all generated signals in a single, organized plot.

## Author
  Aditi Vishwakarma,
  Ved Yadav,
  Shraddha Yedave
