# 🚑 Arogya Raksha

> **Emergency response + hospital care platform**  
> One mobile-first app for SOS rescue, helper coordination, doctor booking, safety tools, and health records.

---

## 📑 Table of Contents
- [Project Overview](#-project-overview)
- [Prototype Videos](#-prototype-videos)
- [Screenshots](#-screenshots)
- [Core Feature Set](#-core-feature-set)
- [Tech Stack](#-tech-stack)
- [Project Structure](#-project-structure)
- [Getting Started](#-getting-started)
- [Environment Setup](#-environment-setup)
- [Available Scripts](#-available-scripts)

---

## ✨ Project Overview

- 🆘 Instant SOS and helper dispatch model
- 🗺️ Live map tracking with ETA and distance updates
- 🏥 Department-based hospital and doctor booking
- 🗂️ Health Vault for prescriptions and reports
- 🛡️ Safety suite (Medical ID + Safety Circle)
- 🧾 Trips history (rides/helped/earned)
- 🎁 Points and community contribution flows
- 📱 Mobile-style experience across all screen sizes

---

## 🎬 Prototype Videos

| Type | Link |
| --- | --- |
| Full product walkthrough | [Add video link](https://example.com/prototype-video) |
| Helmet + SOS hardware simulation | [Add video link](https://example.com/helmet-demo) |

---

## 📸 Screenshots

| Screen | Preview Path |
| --- | --- |
| Landing page | `docs/screenshots/01-landing-hero.png` |
| SOS victim flow | `docs/screenshots/02-sos-victim.png` |
| Incoming helper popup | `docs/screenshots/03-helper-popup.png` |
| Helper - On the way | `docs/screenshots/04-helper-on-the-way.png` |
| Helper - At hospital | `docs/screenshots/05-helper-at-hospital.png` |
| Home dashboard | `docs/screenshots/06-dashboard-home.png` |
| Care booking | `docs/screenshots/07-care-booking.png` |
| Trips tabs | `docs/screenshots/08-trips-tabs.png` |
| Safety hub | `docs/screenshots/09-safety-hub.png` |
| Profile and rewards | `docs/screenshots/10-profile-rewards.png` |

---

## 🧩 Core Feature Set

### 🚨 SOS & Emergency Flow
- 10-second SOS countdown
- Crash/helmet-triggered emergency path
- One-helper acceptance lock (single responder model)
- Mutual profile sharing: name, age, short address, ETA, distance
- Live victim-helper map tracking
- SOS progress states with actionable cards
- Emergency contact and support-oriented UX blocks

### 🙋 Helper Experience
- Nearby SOS popup intake
- Fast accept and redirect to response interface
- On-the-way + at-hospital dual workflow
- Victim details and route intelligence
- Hospital notification panel
- Success state: "Successfully notified, preparing for treatment"
- Rescue completion and points reward flow

### 🏠 Home Dashboard
- Helmet status card
- Partner hospital discovery
- Department browsing
- Quick actions section
- Community impact highlights

### 🩺 Care & Booking
- Department -> hospital -> doctor navigation
- Detailed doctor cards and profiles
- Slot selection
- Reason-for-visit input
- Payment experience (including Google Pay flow options)
- Appointment lifecycle UI

### 🧾 Trips & Rewards
- Rides tab (movement history grouping)
- Helped tab (rescue history)
- Earned tab (points summary)

### 🛡️ Safety & Health Records
- Safety hub access
- Medical ID module
- Safety Circle contacts module
- Health Vault uploads and retrieval

### 👤 Account & Portals
- Profile details and medical fields
- Emergency contacts and address data
- Role-based portals: doctor, hospital, admin

---

## 🛠️ Tech Stack

| Layer | Technology |
| --- | --- |
| Frontend | React, TypeScript, Vite |
| UI | Tailwind CSS, Framer Motion, Lucide Icons |
| Auth | Firebase Authentication |
| Database | Cloud Firestore |
| Storage | Firebase Storage |
| Backend | Firebase Cloud Functions |
| Maps & Location | Google Maps APIs (Places, directions/ETA logic) |
| Payments | Google Pay (test + production-ready modes) |
| Workspace | npm workspaces |

---

## 🏗️ Project Structure

```text
Uber Hospital and Emergency/
├── src/
│   ├── components/        # Reusable UI and flow components
│   ├── data/              # Firestore/data-layer logic
│   ├── screens/
│   │   ├── public/        # Landing and public-facing pages
│   │   └── app/           # Authenticated application screens
│   ├── shell/             # App layouts and wrappers
│   └── lib/               # Shared client utilities
├── functions/             # Firebase Cloud Functions workspace
├── docs/                  # Documentation and screenshot assets
├── .env.example           # Client environment variable template
└── package.json           # Root workspace scripts
```

---

## 🚀 Getting Started

```bash
npm install
npm run dev
```

---

## 🔐 Environment Setup

```bash
cp .env.example .env.local
```

- Fill Firebase client configuration
- Fill Maps configuration
- Keep server-only secrets in Cloud Functions environment
- Do not commit private keys

---

## 📜 Available Scripts

```bash
# Start development server
npm run dev

# Build frontend
npm run build

# Preview production build
npm run preview

# Build cloud functions workspace
npm run build:functions

# Serve cloud functions locally
npm run serve:functions
```
