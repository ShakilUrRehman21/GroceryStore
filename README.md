#  Milk-Marts Platform

Milk-Marts is a full-stack web platform built to digitize local dairy businesses by connecting neighborhood stores with online customers.

The platform enables seamless product browsing, secure payments, order management, and delivery tracking.

---

##  Features

*  Online grocery & dairy product ordering
*  Secure user authentication & authorization
*  Razorpay payment integration
*  Order management system
*  Real-time delivery tracking
*  Admin dashboard for store management
*  PostgreSQL database integration

---

##  Tech Stack

* **Backend:** Django
* **Frontend:** Bootstrap, HTML, CSS
* **Database:** PostgreSQL
* **Payments:** Razorpay
* **Language:** Python

---

##  Key Implementations

* Implemented secure Razorpay payment gateway with 100% transaction success handling
* Built order lifecycle system (Placed → Confirmed → Shipped → Delivered)
* Integrated real-time delivery status updates
* Designed role-based authentication (Customer / Admin)
* Structured relational database using PostgreSQL

---

##  Run Locally

###  Clone the repository

```bash
git clone https://github.com/ShakilUrRehman21/GroceryStore.git
cd GroceryStore
```

###  Create virtual environment

```bash
python -m venv venv
source venv/bin/activate   # Windows: venv\Scripts\activate
```

###  Install dependencies

```bash
pip install -r requirements.txt
```

###  Setup environment variables

Create `.env` file:

```env
SECRET_KEY=
DEBUG=True
DATABASE_URL=
RAZORPAY_KEY_ID=
RAZORPAY_KEY_SECRET=
```

###  Run migrations

```bash
python manage.py migrate
```

###  Start server

```bash
python manage.py runserver
```

Visit:

```
http://127.0.0.1:8000
```

---

##  Core Modules

* User Authentication
* Product Management
* Cart & Checkout
* Payment Gateway Integration
* Order Tracking
* Admin Panel
