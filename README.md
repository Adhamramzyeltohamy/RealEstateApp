# 🏢 Cloud Real Estate Rental & Tenant Management System

A mobile-friendly, multi-role cloud-based SaaS platform built with **Python (Flask)** and **Supabase (PostgreSQL)** for real estate management, automated rental bookings, tenant operations, and maintenance workflows.

🌐 **Live Demo:** [dhueru5u.pythonanywhere.com](https://dhueru5u.pythonanywhere.com/)

---

## 📸 Screenshots & Platform Overview

### 1. 🌐 Public Customer Portal
Search available properties, filter by type/budget, and view real-time unit status.
![Public Customer Portal](RealEstateApp/static/images/WhatsApp%20Image%202026-10-19%20at%203.45.00%20AM.jpeg)

---

### 2. 🔐 Authentication & Portal Selection
Role-based portal access for Tenants and System Managers.
![Login Portal](RealEstateApp/static/images/WhatsApp%20Image%202026-10-19%20at%203.45.24%20AM.jpeg)

---

### 3. 📊 Manager Analytics Dashboard
Real-time management metrics covering revenue collection, occupancy rates, and active bookings.
![Manager Dashboard](RealEstateApp/static/images/WhatsApp%20Image%202026-10-19%20at%203.46.07%20AM.jpeg)

---

### 4. 🏢 Property Portfolio Management
Full CRUD controls for property listings, photos, and tenancy status.
![Property Management](RealEstateApp/static/images/WhatsApp%20Image%202026-10-19%20at%203.46.15%20AM.jpeg)

---

## 🌟 Key Features

* **Public Customer Portal:** Search rooms/apartments, view property details/photos, apply online, and receive automated IBAN payment references.
* **Tenant Dashboard:** View active contracts, track monthly rent invoices, upload bank transfer receipts, and report maintenance issues with photos.
* **Manager Console:** Manage buildings and units, verify/reject bank payments, oversee occupancy rates, and handle maintenance tickets.

---

## 🛠️ Tech Stack & Architecture

* **Backend:** Python / Flask
* **Database & BaaS:** Supabase (PostgreSQL)
* **Storage:** Supabase Object Storage
* **Frontend:** Responsive HTML5, CSS3, JavaScript
* **Hosting:** PythonAnywhere

---

## 🚀 Getting Started

### Prerequisites
* Python 3.10+
* Supabase Account & Project

### Installation & Local Setup

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/Adhamramzyeltohamy/RealEstateApp.git](https://github.com/Adhamramzyeltohamy/RealEstateApp.git)
   cd RealEstateApp
   ```

2. **Create and activate virtual environment:**
   ```bash
   python -m venv .venv
   source .venv/bin/activate  # On Windows: .venv\Scripts\activate
   ```

3. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Environment Variables:**
   Create a `.env` file in the root directory (refer to `.env.example`):
   ```env
   SUPABASE_URL=your_supabase_url
   SUPABASE_PUBLISHABLE_KEY=your_supabase_key
   FLASK_SECRET_KEY=your_secret_key
   ```

5. **Run the Application:**
   ```bash
   python app.py
   ```
   Open `http://127.0.0.1:5000` in your browser.
