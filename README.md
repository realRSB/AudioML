# Audio Data Analysis and Machine Learning Project

## Overview

This project explores audio data analysis techniques and prepares audio data for use in machine learning models. The code processes audio files, visualizes their characteristics, and transforms them into spectrograms (both regular and Mel spectrograms) which can be used as input for machine learning models.

## Project Goal

The ultimate goal of this project is to transform raw audio data into a suitable format (Mel spectrograms) that can be fed into a machine learning model for further analysis or classification.

## Key Concepts

*   **Frequency:** The rate at which a sound wave repeats, perceived as pitch.
*   **Intensity:** The amplitude of a sound wave, perceived as loudness.
*   **Sample Rate:** The number of samples taken per second to represent an audio signal, affecting sound quality.
* **Spectrogram:** visual representation of audio frequencies.
* **Mel Spectogram:** Another visual representation of audio frequencies, with certain optimizations.

## Dependencies

The following libraries are required to run the code in this project:

*   **pandas** (version 2.1.3): For data manipulation and analysis. `pip install pandas==2.1.3`
*   **numpy** (version 1.26.3): For numerical operations. `pip install numpy==1.26.3`
*   **matplotlib** (version 3.8.2): For creating static, interactive, and animated visualizations. `pip install matplotlib==3.8.2`
*   **seaborn** (version 0.13.1): For statistical data visualization. `pip install seaborn==0.13.1`
*   **glob** (part of the Python standard library): For finding pathnames matching a specified pattern.
