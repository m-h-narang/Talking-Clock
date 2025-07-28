# Talking Clock — Voice Output Application

This project implements a talking clock in Python that announces the current time in English using pre-recorded audio segments. The application allows the user to hear the current time, read any arbitrary input time, and select between multiple voices recorded by different team members. The code runs locally without relying on external APIs or pre-trained Text-to-Speech models.

This work was developed as part of the Voice Technology MSc. 2024–2025 Programming assignment.

---

## Project Description

The project fulfills the requirements of the Talking Clock assignment, including:

- Recording and using audio segments to announce the current system time in natural-sounding speech.
- Concatenating audio segments to generate time phrases dynamically, avoiding the need to record every possible time.
- Allowing users to choose between different recorded voices.

Implementing additional features:

- Ability to read arbitrary user-input time.
- Extra functionality to demonstrate voice output variations.

---

## How to Run

1. Clone or download the repository folder containing TalkingClockGroup3.ipynb and the audio recordings.

2. Place all required audio recordings in a directory named audio/ (or update the code paths if different).

3. Install dependencies:

``` bash
pip install pydub simpleaudio
```

4. Open and run the notebook:

``` bash
jupyter notebook TalkingClockGroup3.ipynb
```

5. In the interface:

- Select the desired voice set.

- Choose current time announcement or read an input time.

- Play the generated audio output.

