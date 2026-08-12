# 🌱 Farm2City – Direct Farmer Marketplace

Farm2City is a full-stack **farmer-to-buyer marketplace** that enables farmers to sell their produce directly to buyers, reducing dependence on traditional intermediaries.

The platform allows farmers to list and manage their products while buyers can discover produce based on location, negotiate prices, place orders, and track deliveries through a simple marketplace interface.

## ✨ Features

### 👨‍🌾 For Farmers

* Create and manage product listings
* Specify product price, quantity, and location
* Manage incoming orders
* Track product availability
* Access a dedicated farmer dashboard

### 🛒 For Buyers

* Browse available farm products
* Discover products based on location
* Negotiate product prices
* Place and manage orders
* Track deliveries through the platform
* Access a dedicated buyer dashboard

### ⚙️ Platform Features

* Role-based farmer and buyer workflows
* Location-based product discovery
* Price negotiation
* Product and order management
* Mock delivery tracking
* Responsive marketplace interface
* RESTful API architecture
* PostgreSQL-backed persistent data management

## 🛠️ Tech Stack

**Frontend**

* React.js
* Vite
* JavaScript

**Backend**

* FastAPI
* Python
* REST APIs

**Database**

* PostgreSQL

**Architecture**

* Full-stack client-server architecture
* RESTful API communication
* Role-based workflows

## 🏗️ Project Structure

```text
Farm2City/
├── frontend/          # React.js frontend
│   ├── src/
│   ├── public/
│   └── package.json
│
├── backend/           # FastAPI backend
│   ├── app/
│   ├── requirements.txt
│   └── ...
│
└── README.md
```

## 🚀 Getting Started

### Prerequisites

Make sure you have the following installed:

* Node.js and npm
* Python 3.10+
* PostgreSQL
* Git

### 1. Clone the Repository

```bash
git clone https://github.com/<your-username>/Farm2City.git
cd Farm2City
```

### 2. Setup the Frontend

```bash
cd frontend
npm install
npm run dev
```

The frontend will be available at the local URL shown by Vite.

### 3. Setup the Backend

Open another terminal:

```bash
cd backend

python -m venv venv
source venv/bin/activate
```

On Windows:

```bash
venv\Scripts\activate
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Start the FastAPI server:

```bash
uvicorn main:app --reload
```

### 4. Database Configuration

Create a PostgreSQL database and configure the required database credentials in the backend environment variables.

Example:

```env
DATABASE_URL=postgresql://username:password@localhost:5432/farm2city
```

> Do not commit your `.env` file or database credentials to the repository.

## 🔄 Application Flow

```text
Farmer
   │
   ├── Add / Manage Products
   │
   ▼
Farm2City Marketplace
   │
   ├── Location-based Discovery
   ├── Price Negotiation
   └── Product Information
   │
   ▼
Buyer
   │
   ├── Place Order
   └── Track Delivery
   │
   ▼
Order Management
```

## 🎯 Purpose

Farm2City aims to create a more transparent connection between **farmers and buyers** by providing a digital marketplace where agricultural products can be discovered, negotiated, and purchased directly.

The project also serves as an exploration of **full-stack application development**, including frontend–backend integration, REST API design, database management, role-based workflows, and responsive UI development.

## 📌 Project Status

🚧 **Active Development**

More features and improvements may be added as the project evolves.

## 👨‍💻 Contributors

Developed as a full-stack web development project using **React.js, FastAPI, and PostgreSQL**.
