# SENSEX

**Physical diagnostics, on-device.**

SENSEX turns a smartphone into a diagnostic tool for machines and household equipment. It fuses the camera, microphone, and motion sensors to detect abnormal vibration, sound, or visual wear — then returns an evidence-backed likely cause with a confidence score and a guided next inspection step. All analysis is designed to run locally on-device: no raw audio, video, or motion data ever needs to leave the phone.

Built for students, technicians, small businesses, and households who don't have access to expensive diagnostic equipment or expert help on hand.

---

## The problem

Machines and appliances signal trouble long before they fail — a rattle, a whine, a wobble. Most people can't read those signs, and expert help or diagnostic equipment isn't always nearby. Existing tools read one signal at a time (sound-only or vibration-only apps), often upload raw data to the cloud, and rarely tell you what to do next.

## What SENSEX does

1. **Multi-sensor capture** — camera, mic, and motion sensors record the equipment simultaneously
2. **On-device fusion** — a local model aligns visual, acoustic, and motion signals in real time
3. **Evidence-backed diagnosis** — a likely cause is produced with a confidence score
4. **Guided next step** — the app walks the user through the next inspection action

## This repo

This repo hosts the installable web app (PWA) prototype — a simulated walkthrough of the SENSEX flow (splash → sensor capture → diagnosis → history → settings) so anyone can install it on a phone and feel the product experience ahead of the on-device model being wired up.

**Live app:** [https://sensex-xi.vercel.app/](https://sensex-xi.vercel.app/)
**Repository:** [github.com/balapraharsha/sensex](https://github.com/balapraharsha/sensex)

### Try it

1. Open the live link above on your phone
2. Tap **Install app** (Android/Chrome) or **Share → Add to Home Screen** (iPhone/Safari)
3. Open it from your home screen — it launches full-screen, like a native app
4. Tap **Start Diagnosis** to run a simulated scan

> This prototype simulates sensor capture and diagnosis so it works on any device instantly. It does not access your real camera, mic, or motion sensors, and does not run a real ML model yet. The production version fuses real sensor data through an on-device model.

### Tech

Single-page installable PWA — plain HTML/CSS/JS, a Web App Manifest, and a service worker for offline caching. No build step, no dependencies beyond a Google Fonts import.

---

## Team

**Team SENSEX**

**Bala** and **Yasasswini** have built together across nearly every major hackathon on their track record:

- **Grand Finalists** (Top 800 of 31,000+ teams) — Meta PyTorch OpenEnv Hackathon × Scaler, presenting two reinforcement-learning projects, **ContractArena** and **CrisisCity**, live to Meta engineers in Bangalore
- **Grand Finale Qualifiers** — iDEA 2.0 Hackathon (Union Bank of India × K.J. Somaiya College), as Team DesiLogic
- **Shortlisted** — AWS AI for Bharat Hackathon 2026
- **3rd Prize** — Paradox 2026, IIT Madras

---
