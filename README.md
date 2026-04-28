# 🚑 Arogya Raksha

## ✨ Project Snapshot
- 🩺 Emergency + hospital app in one flow
- ⚡ Mobile-first UI
- 🔴 Live SOS + helper assignment
- 🏥 Doctor booking + records vault
- 🎁 Community reward points

## 🎬 Prototype Video Space
- ▶️ Main walkthrough: [Add video link here](https://example.com/prototype-video)
- 🪖 Helmet demo: [Add helmet video link here](https://example.com/helmet-demo)

## 📸 Screenshot Space
- `docs/screenshots/01-landing-hero.png` - Landing hero
- `docs/screenshots/02-sos-victim.png` - SOS victim screen
- `docs/screenshots/03-helper-popup.png` - Incoming helper popup
- `docs/screenshots/04-helper-on-the-way.png` - Helper on-the-way
- `docs/screenshots/05-helper-at-hospital.png` - Helper at-hospital
- `docs/screenshots/06-dashboard-home.png` - Home dashboard
- `docs/screenshots/07-care-booking.png` - Care booking page
- `docs/screenshots/08-trips-tabs.png` - Trips tabs
- `docs/screenshots/09-safety-hub.png` - Safety hub
- `docs/screenshots/10-profile-rewards.png` - Profile + rewards

## 🧭 App Navigation
- 🏠 Home
- 🚕 Trips
- 🛡️ Safety
- 👤 Profile
- 🚨 Center SOS action

## 🚨 SOS (Victim) Features
- 10s SOS countdown
- One-tap SOS trigger
- Helmet/crash flow support
- Auto helper search
- Single helper acceptance only
- Helper details shown:
  - Name
  - Age
  - Short address
  - ETA
  - Distance
- Victim details shared to helper:
  - Name
  - Age
  - Short address
  - Contact
- Live map + route
- Alert sent summary
- Safety guide card
- Need-to-talk support card
- Feeling/mood check card

## 🙋 Helper Side Features
- Incoming SOS popup
- Quick accept flow
- Auto route to help screen
- On the way tab
- At hospital tab
- Victim info card
- Live ETA updates
- Distance guard logic
- Arrived-state handling
- Hospital notify panel
- Success state copy:
  - Successfully notified
  - Preparing for treatment
- Rescue completion flow
- Points reward flow

## 🏠 Home Features
- Helmet status card
- Partner hospital block
- Department browse block
- Quick actions block
- Community impact strip

## ⚡ Quick Actions
- Report accident
- Call ambulance
- Share live location
- Safety circle

## 🏥 Care / Booking Features
- Department-wise discovery
- Hospital listing
- Doctor listing
- Doctor profile details
- Slot picker
- Reason-for-visit input
- Payment bar
- Google Pay option
- Demo pay option
- Pay-at-hospital option
- Booking confirmation flow
- Appointments listing

## 🧾 Trips Features
- Rides tab
- Helped history tab
- Earned tab
- Day-wise movement grouping
- Help rescue history cards
- Points/earnings view

## 🛡️ Safety Features
- Safety hub screen
- Medical ID screen
- Safety Circle screen
- Emergency support shortcuts

## 🗂️ Health Data Features
- Health Vault storage
- Prescription upload
- Report upload
- Record access anytime

## 👤 Profile Features
- Personal profile
- Medical fields
- Saved addresses
- Emergency contacts
- Points and reward summary

## 🧑‍⚕️ Special Portals
- Doctor portal route (`/doctor`)
- Hospital portal route (`/hospital`)
- Admin route (`/admin`)

## 🔌 Integrations
- Firebase Auth
- Firestore
- Firebase Storage
- Cloud Functions
- Google Maps
- Google Places
- Google Directions/ETA logic
- Google Pay (test/prod mode)

## 🧱 Data + Logic Highlights
- SOS request model
- Assignment model
- Participant brief model
- One-helper transaction lock
- Realtime assignment updates
- Helper location streaming

## 🖥️ Tech Stack
- React
- TypeScript
- Vite
- Tailwind CSS
- Framer Motion
- Firebase

## 📁 Important Project Paths
- `src/screens/public/LandingPage.tsx`
- `src/screens/app/DashboardPage.tsx`
- `src/screens/app/SosPage.tsx`
- `src/screens/app/HelpPage.tsx`
- `src/screens/app/TripsPage.tsx`
- `src/screens/app/care/CareBookPage.tsx`
- `src/components/IncomingSosOverlay.tsx`
- `src/components/HospitalAlertPanel.tsx`
- `src/data/sos.ts`
- `src/data/helmet.ts`
- `src/data/user.ts`
- `functions/`

## ⚙️ Run Locally
- `npm install`
- `npm run dev`

## 🔐 Env Setup
- Copy `.env.example` -> `.env.local`
- Fill required Firebase keys
- Fill Maps keys
- Keep sensitive server keys in `functions` env only

## 🧪 Build Commands
- `npm run build`
- `npm run build:functions`
- `npm run serve:functions`

## ✅ Status
- Mobile-first layout active
- SOS + helper flow active
- Care booking active
- Trips tabs active
- Safety module active
