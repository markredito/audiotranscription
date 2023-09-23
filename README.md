
# README for "Audio Transcription using Whisper"

---

## Overview

This project provides a Jupyter notebook to transcribe audio using OpenAI's Whisper Model. Authored by Mark Redito, it is inspired by a tutorial from Weights and Biases. The specific model used for transcription is `medium.en`, a medium-sized model tailored for the English language.

---

## Prerequisites

- Google Drive: For storing and accessing audio files.
- OpenAI's Whisper library: Used for transcription. Install via `pip install -q git+https://github.com/openai/whisper.git`.
- CUDA (Optional): If available, it can be used for faster inference.

---

## Steps

1. **Connect to Google Drive**:
   - Mount your Google Drive to access audio files.

2. **Specify Audio File Details**:
   - Choose the source of the audio file (`gdrive` or `local`).
   - Provide the path to the audio file.
   - Decide on the output format:
     - Save as a plain text file.
     - Save as an SRT file.

3. **Install Dependencies & Configure**:
   - Install the necessary libraries.
   - Load the Whisper model (`medium.en`).

4. **Transcription**:
   - Transcribe the provided audio file.
   - Save the transcription in the chosen format(s) (`.txt` or `.srt`).

---

## Notes

- For faster inference, it is recommended to use a GPU.
- Ensure the path to the audio file is accurate when specifying it.
- The notebook provides an easy interface for users to specify their choices and get transcriptions seamlessly.

---

## Links & References

- [Author: Mark Redito](https://markredito.com)
- [Inspiration: Weights and Biases Tutorial](https://https://wandb.ai/wandb_fc/gentle-intros/reports/OpenAI-Whisper-How-to-Transcribe-Your-Audio-to-Text-for-Free-with-SRTs-VTTs---VmlldzozNDczNTI0)
- [Whisper on GitHub](https://https://github.com/openai/whisper)

---

This README provides a concise overview and instructions to utilize the notebook for audio transcription. Users can follow the specified steps to obtain transcriptions of their audio files.

---

Feel free to modify or expand this README as per your requirements.
