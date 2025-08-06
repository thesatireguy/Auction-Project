### 📁 Project Structure

#### AuctionWebsite/
- **Backend/**
  - `server.js`  
    → Entry point for the Node.js backend server

  - `config/db.js`  
    → MongoDB connection setup

  - `models/Product.js`  
    → Mongoose schema for products

  - `models/User.js`  
    → Mongoose schema for users

  - `routes/`  
    → (Reserved for future API route separation)

  - `.env`  
    → Environment variables (e.g., DB URI, Port)

- **Frontend/**
  - `index.html`  
    → Homepage

  - `sell.html`  
    → Product upload form

  - `listed.html`  
    → User's listed products page

  - `checkout.html`  
    → Checkout/purchase flow

  - `product.html`  
    → Product details view

  - `CSS/`  
    → Styling files

  - `JS/`  
    → Frontend logic (e.g., `sell.js`, `listed.js`)

- `start-server.bat`  
  → Script to start the server on Windows

- `launch.vbs`  
  → Optional script to auto-launch the site


Clone the Repository:
git clone https://github.com/thesatireguy/Auction-Project.git
cd AuctionWebsite/Backend

Install Backend Dependencies:
npm install
Setup Environment Variables

Create a .env file inside Backend/ with the following contents:
MONGO_URI=mongodb://localhost:27017/auctiondb
PORT=5000

Start the Backend Server:
node server.js
Open index.html in your browser to use the frontend.

