# 🩸 Digital Blood Donation Hub

**A public-domain web application bridging the gap between blood donors, seekers, and hospitals in real time.**

This platform streamlines life-saving blood donation workflows by enabling geo-located donor searches, instant emergency broadcasts, and secure eligibility tracking to minimize critical response times.

## 🚀 Core Features

* **Smart Donor Profiles:** Automated donation interval tracking and privacy-focused contact controls.
* **Geo-Location Matchmaking:** Distance-based filtering to locate available, matching donors nearest to the hospital.
* **Emergency Broadcasts:** Live distress signals that instantly notify compatible regional donors.
* **Live Inventory Hub:** Real-time stock tracking tailored for partnered blood banks.

## 🛠️ Technology Stack

* **Frontend:** Next.js (TypeScript) & Tailwind CSS
* **Backend:** Node.js (Express)
* **Database:** PostgreSQL (User data) & Redis (Geo-queries)
* **Auth & Security:** NextAuth.js (Role-based access controls)

## ⚙️ Quick Start

### 1. Installation
```bash
git clone https://github.com
cd digital-blood-donation-hub
npm install
```

### 2. Environment Setup
Create a `.env` file in the root folder:
```env
DATABASE_URL=postgresql://user:password@localhost:5432/blood_db
JWT_SECRET=your_secret_key
MAPS_API_KEY=your_location_api_key
```

### 3. Run the App
```bash
npm run db:migrate
npm run dev
```
The app will run locally at `http://localhost:3000`.

## 🤝 Contributing & License
We welcome all open-source contributors. Distributed under the **MIT License**. Deployed fully in the public domain to maximize global health access.
