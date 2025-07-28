# AI Voice Sync with Cloudflare Proxy

## Overview

A browser-based voice assistant that connects to Gemini AI through a Cloudflare Worker proxy, featuring real-time voice visualization and natural conversation flow.

## ✨ Key Features

- **Cloudflare Proxy Architecture**
  - Secure API routing through Cloudflare Workers
  - Protection of sensitive API credentials
  - Edge network caching for faster responses

- **Voice Interaction**
  - Continuous speech recognition
  - Natural language processing
  - Text-to-speech with voice modulation

- **Visual Feedback**
  - Dynamic audio waveform visualization
  - Reactive lighting effects
  - Real-time response tracking

## 🛠️ Technical Implementation

| Component               | Technology Used           |
|-------------------------|---------------------------|
| Voice Recognition       | Web Speech API            |
| AI Processing           | Gemini AI via Cloudflare  |
| Audio Visualization     | Web Audio API             |
| Frontend                | Vanilla JS + CSS          |

## Architecture
```mermaid
graph TD
    A[User Voice] --> B[Browser]
    B --> C[Cloudflare Worker]
    C --> D[Gemini AI]
    D --> C --> B --> E[Voice Response]
