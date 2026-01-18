# JanMitra

JanMitra is a voice-first companion that helps rural Indians access government schemes, financial information, and local support in their own language, through a web browser or a simple phone call.

Users can either open a web page and speak, or call a phone number. In both cases, JanMitra provides real-time spoken responses with a strong focus on accessibility, accuracy and simplicity.

---

## Overview

Millions of rural citizens struggle to access government services not because support doesn’t exist, but because information is difficult to find, understand, or navigate. JanMitra bridges this gap by turning complex public systems into simple voice conversations.

---

## How It Works (Actual Implementation)

Web Browser / Mobile Phone  
→ WebSocket  
→ Gemini Live  
→ WebSocket  
→ Voice Response  

- Browser users interact via a voice-enabled web client  
- Phone users interact via calls powered by Exotel  
- Both interfaces use the same WebSocket backend  
- Gemini Live handles speech-to-text, reasoning, and text-to-speech  

---

## Core Features

- Web browser access with no app installation
- Phone call access via Exotel for basic mobile phones
- Real-time speech-to-speech interaction
- Multiple language support
- Factual responses focused on public information
- Low-friction design with no login or setup

---

## Target Users

- Rural citizens in India with internet or basic phone access
- Users facing language barriers, complex portals and middlemen dependency

---

## Tech Stack

- Frontend: NextJs
- Calling: Exotel
- Transport: WebSocket
- Voice + LLM: Google Gemini Live
- Backend: Lightweight WebSocket server
- Deployment: Vercel

---

## Current MVP Scope

- Interfaces: Web browser and phone calls
- Interaction: Voice-only
- Data: Prompt guided factual responses
- Tools: None (planned for future)

---

## Guardrails

- No medical, legal, or political advice
- No personal data storage
- Public-information-only responses
- Off-topic queries are filtered

---
