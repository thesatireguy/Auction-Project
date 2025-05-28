🗂️ Project Structure
bash
Copy
Edit
AuctionWebsite/
├── Backend/
│   ├── server.js              # Entry point for the Node.js server
│   ├── config/
│   │   └── db.js              # MongoDB connection
│   ├── models/
│   │   ├── Product.js         # Mongoose schema for products
│   │   └── User.js            # Mongoose schema for users
│   ├── routes/                # (Optional future separation)
│   └── .env                   # Environment variables
├── Frontend/
│   ├── index.html             # Home page
│   ├── sell.html              # Product upload form
│   ├── listed.html            # "My Listings" page
│   ├── checkout.html          # Checkout page
│   ├── product.html           # Product detail page
│   ├── CSS/                   # Inline or embedded CSS
│   └── JS/                    # Frontend logic (e.g., sell.js, listed.js)
├── start-server.bat          # Launch script for local development (Windows)
└── launch.vbs                # Optional helper for launching site
🛠️ Installation
Clone the Repository:
git clone https://github.com/yourusername/AuctionWebsite.git
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

