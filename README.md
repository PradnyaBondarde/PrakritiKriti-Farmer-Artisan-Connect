# PrakritiKriti – Farmer & Artisan Connect 🌾🧵

A digital platform to bridge farmers and artisans, repurposing agricultural waste into handcrafted products. This web application enables farmers to upload by-products, artisans to browse opportunities, and industries to partner for sustainable manufacturing.

---

## 🚀 Objective  
To create a socially impactful, eco-friendly marketplace linking **agricultural waste** with **local artisans**, thereby promoting waste valorisation, rural employment, and circular economy practices.

---

## ✨ Features  
- Farmer registration & listing of agricultural by-products (e.g., husk, straw, shells)  
- Artisan sign-up & project dashboard for receiving and bidding on materials  
- Industry or brand partner module to view artisan-crafted items and place bulk orders  
- Real-time messaging/notifications between stakeholders  
- Admin dashboard for issue tracking, verification, and sustainability metrics  

---

## 🧰 Tech Stack  
- **Frontend:** HTML, CSS, JavaScript, React (Context API)  
- **Backend:** Node.js, Express.js  
- **Database:** MongoDB / MySQL (specify whichever used)  
- **Cloud / Hosting (optional):** Firebase Authentication, AWS S3, Heroku  
- **Version Control:** Git, GitHub  

---  
## 🗂️ Project Structure
PrakritiKriti-Farmer-Artisan-Connect/
├─ client/ # React frontend (if used)
├─ server/ # Backend APIs (Node.js/Express)
├─ models/ # Database schema/models
├─ routes/ # API endpoints
├─ public/ # Static assets (images, CSS)
├─ README.md # Project documentation   


---

## 🧠 Working Flow  
1. Farmers log in and list agricultural residue/ by-products (photos + quantities).  
2. Artisans browse materials, submit interest, and collaborate with farmers to create handcrafted items.  
3. Industries review artisan catalogs and place orders for finished goods.  
4. Admin panel tracks registration verification, transaction history, and sustainability dashboard (waste diverted, jobs created).  
5. The system fosters a connect-loop: **Farmers → Material**, **Artisans → Crafting**, **Industries → Consumption**.

---

## 💻 Setup & Installation  
1. Clone the repo:  
   ```bash
   git clone https://github.com/PradnyaBondarde/PrakritiKriti-Farmer-Artisan-Connect.git
   cd PrakritiKriti-Farmer-Artisan-Connect

2. cd server/
npm install
cd ../client/
npm install

3. PORT=5000
DB_URI=your_database_connection_string
JWT_SECRET=your_jwt_secret
CLOUD_STORAGE_KEY=your_cloud_key

# Terminal 1 (backend)
cd server/
npm start  
# Terminal 2 (frontend)
cd client/
npm start

Access the application at: http://localhost:3000

