![Plant Seller Logo](https://res.cloudinary.com/dcd6y2awx/image/upload/v1709673317/PlantSeller/UI%20Images/plant_seller_bg_none.png)

---

**Project Name:** Plant Seller

**Description:** Welcome to Plant Seller: Where Green Dreams Come True!

Explore our lush collection of plants to elevate your living space. From vibrant succulents to elegant ferns, find the perfect green companions to breathe life into your home.

Let's grow together!

---

**Folder Structure:**

```
plant-seller/
├── frontend/
│   ├── (frontend files and directories)
├── backend/
│   ├── (backend files and directories)
```

**Frontend:**
- Framework: React.js
- Port: 3000 (localhost)

**Backend:**
- Framework: Node.js, Express.js
- Database: MongoDB
- Port: 8000 (localhost)

---

**Features:**

1. **User Account:**
   - Login
   - Signup
   - Profile
   - Address
   - Cart
   - Order
   - Buy Plant
   - And more...

2. **Nursery:**
   - All features of a user
   - Nursery Profile
   - Add Plant
   - Edit Plants
   - Customize Nursery Store
   - And more...

3. **Admin:**
   - All access of the website
   - Manage users
   - Manage nurseries
   - Manage plants
   - And more...

---

**Technologies:**

- MERN Stack (MongoDB, Express.js, React.js, Node.js)
- Stripe.js (Payment Integration)
- Chart.js (Data Visualization)
- Bootstrap (Frontend Framework)
- Sass (CSS Preprocessor)

---

**Getting Started:**

1. Clone the repository:



```
git clone https://github.com/MeetGori1/plant-seller-ecommerce-.git
```

2. Install dependencies:

```
cd plant-seller/frontend
npm install

cd ../backend
npm install
```


3. Set up environment variables:

   - Create a `.env` file in the backend directory.
   - Define environment variables such as `PORT`, `MONGODB_URI`, `STRIPE_SECRET_KEY`, etc.

4. Run the frontend development server:



```
cd ../frontend
npm start
```


5. Run the backend development server:

```
cd ../backend
npm start
```
---

6. Open your browser and visit `http://localhost:3000` to view the application.

-------------

Build Docker Images Manually


Navigate to the frontend directory:
```
cd frontend
docker build -t frontend-app .
```

Navigate to the backend directory:
```
cd ../backend
docker build -t backend-app .
```
---
