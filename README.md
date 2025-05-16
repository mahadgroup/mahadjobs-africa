# MahadJobs Africa

> 🌍 A dedicated job portal connecting African professionals and skilled workers with high-quality international employment opportunities.

---

## 🌐 Overview

MahadJobs Africa is a recruitment platform that bridges the gap between African talent and global job markets. With support for skilled and unskilled labor categories, the platform simplifies everything from job browsing to interview scheduling — all powered by Mahad Manpower’s global recruitment infrastructure.

---

## 💼 Key Features

- 🌍 Country Targeting: Kenya, Uganda, Ghana, Nigeria, South Africa
- 🌐 International Job Listings (UAE, Qatar, Oman, Europe, Asia)
- 📝 Smart Resume Builder + Cover Letter Generator
- 📲 WhatsApp Job Alerts (Twilio)
- 🔍 Filter Jobs by Skill, Language, Experience
- 🎯 Employer Dashboard for Screening & Shortlisting
- 📅 Zoom API for Interview Scheduling
- 🎥 Video Resume Upload Feature
- 📊 Application Tracking (Shortlisted / Interview / Hired)
- 🗺️ Resources on Work Permits, Visa Support, and Travel Prep

---

## 🛠️ Tech Stack

- **Frontend:** Angular / React  
- **Backend:** Node.js / ASP.NET Core  
- **Database:** MongoDB / PostgreSQL  
- **Hosting:** VPS / Plesk / Azure  
- **Integrations:** Zoom, Twilio, Cloudinary

---

## 📁 Folder Structure
mahadjobs-africa/
├── frontend/ # Angular/React frontend with Africa-specific styling
├── backend/ # REST API backend (Node/.NET)
├── database/ # DB schema and seeders
├── public/ # Static resources
├── docs/ # Process flows, UI/UX design, API contracts
└── README.md

---

## 🚀 How to Run Locally

### Prerequisites
- Node.js / Angular CLI / .NET SDK
- MongoDB or PostgreSQL
- Git & VS Code

---

### 🟩 Node.js Setup

```bash
git clone https://github.com/mahadgroup/mahadjobs-africa.git

# Frontend
cd frontend
npm install
ng serve

# Backend
cd backend
npm install
npm run dev
cd backend
dotnet restore
dotnet run
