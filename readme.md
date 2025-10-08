# Mini-Vendor-Catalog-Manager

**Live Demo:** [https://mern-ecommerce-frontend-gamma.vercel.app/](https://mern-ecommerce-frontend-gamma.vercel.app/)

**LinkedIn:** [Manish Mahawar](https://www.linkedin.com/in/manishmahawar20/)

---

## 🛍️ Mini-Vendor-Catalog-Manager

A lightweight, scalable catalog management system for vendors, built with MERN Stack, Prisma, and Shadcn UI.

---

## 🔧 Tech Stack

| Layer      | Technology Used                      |
| ---------- | ------------------------------------ |
| Frontend   | React.js + Shadcn UI + Tailwind CSS  |
| Backend    | Node.js + Express.js                 |
| Database   | PostgreSQL (via Prisma ORM)          |
| Auth       | JWT + OTP (optional)                 |
| Deployment | Vercel (Frontend) + Render (Backend) |
| Optional   | Socket.io (for real-time updates)    |

---

## ✨ Key Features

### 👤 Vendor Dashboard

* Add/edit/delete product listings
* Upload product images and documents
* Set pricing, stock, and availability
* View product performance analytics

### 📦 Product Catalog

* Category-based filtering
* Search by name, tags, or vendor
* Pagination and sorting
* Soft delete with restore option

### 🔐 Authentication & Roles

* Vendor login/signup with OTP verification
* Admin panel for catalog moderation
* Role-based access control (RBAC)

### 📊 Analytics (Optional)

* Product views, clicks, and conversion tracking
* Export reports in CSV format

---

## 📁 Project Structure

```
mini-vendor-catalog-manager/
├── backend/
│   ├── controllers/
│   ├── models/ (Prisma schema)
│   ├── routes/
│   ├── middleware/
│   └── .env
├── frontend/
│   ├── components/
│   ├── pages/
│   ├── hooks/
│   └── .env
```

---

## 🚀 Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/mini-vendor-catalog-manager.git
cd mini-vendor-catalog-manager
```

### 2. Backend Setup

```bash
cd backend
npm install
npx prisma init
# Configure DATABASE_URL in .env
npx prisma db push
npm run dev
```

### 3. Frontend Setup

```bash
cd frontend
npm install
npm run dev
```

---

## 🧪 Demo Credentials (Optional)

```
email: vendor@demo.com
password: vendor123
```

---

## 📣 Bonus Suggestions

* Integrate Stripe for vendor subscription tiers
* Add image compression via Cloudinary
* Enable real-time stock updates with Socket.io

