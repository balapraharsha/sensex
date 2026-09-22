# SENSEX

**Physical diagnostics, on-device.**

SENSEX turns a smartphone into a diagnostic tool for machines and household equipment. It fuses the camera, microphone, and motion sensors to detect abnormal vibration, sound, or visual wear — then returns an evidence-backed likely cause with a confidence score and a guided next inspection step. All analysis is designed to run locally on-device: no raw audio, video, or motion data ever needs to leave the phone.

Built for students, technicians, small businesses, and households who don't have access to expensive diagnostic equipment or expert help on hand.

## This repo

This repo hosts the installable web app (PWA) prototype via GitHub Pages — a simulated walkthrough of the SENSEX flow (splash → sensor capture → diagnosis → history → settings) so anyone can install it on a phone and feel the product experience without needing real hardware or an on-device model wired up yet.

**Live app:** `https://<your-username>.github.io/sensex/` (once Pages is enabled — see below)

## Try it

1. Open the live link above on your phone
2. Tap **Install app** (Android/Chrome) or **Share → Add to Home Screen** (iPhone/Safari)
3. Open it from your home screen — it launches full-screen, like a native app
4. Tap **Start Diagnosis** to run a simulated scan

> Note: this prototype simulates sensor capture and diagnosis so it works on any device instantly. It does not access your real camera, mic, or motion sensors, and does not run a real ML model. The production version fuses real sensor data through an on-device model.

## Tech

Single-page installable PWA — plain HTML/CSS/JS, a Web App Manifest, and a service worker for offline caching. No build step, no dependencies beyond a Google Fonts import.

## Team

Team SENSEX — [add your names here]
