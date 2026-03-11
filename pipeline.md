# AI News Production Pipeline

This file describes the complete workflow used in the project.

---

## 1 Download News Broadcast

The original news program is downloaded from YouTube.

---

## 2 Extract Script

The presenter speech is transcribed into text.

This script will be used for narration.

---

## 3 Extract Presenter Voice

Presenter voice samples are extracted using UVR.

Purpose:

Separate voice from music and noise.

---

## 4 Clean Audio Dataset

Audio is cleaned using Audacity.

Operations:

- Noise reduction
- Silence trimming
- Volume normalization

---

## 5 Clone Voice

Clean audio is uploaded to ElevenLabs.

A voice model is created.

---

## 6 Generate Narration

The script is converted into narration using the cloned voice.

---

## 7 Prepare Presenter Image

The presenter photo is enhanced using Leonardo AI.

---

## 8 Animate Presenter

The presenter image and narration audio are uploaded to HeyGen.

The system generates an animated presenter with lip synchronization.

---

## 9 Video Editing

All materials are imported into Lightworks.

The AI presenter replaces the original presenter.

---

## 10 Final Export

The final AI news broadcast is exported as MP4 video.
