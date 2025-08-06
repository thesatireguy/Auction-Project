🗂️ Project Structure
AuctionWebsite/
├── Backend/
│   ├── server.js              # Node.js server entry point
│   ├── config/
│   │   └── db.js              # MongoDB connection setup
│   ├── models/
│   │   ├── Product.js         # Product schema (Mongoose)
│   │   └── User.js            # User schema (Mongoose)
│   ├── routes/                # (Reserved for future route separation)
│   └── .env                   # Environment variables
├── Frontend/
│   ├── index.html             # Home page
│   ├── sell.html              # Product upload form
│   ├── listed.html            # "My Listings" page
│   ├── checkout.html          # Checkout page
│   ├── product.html           # Product detail page
│   ├── CSS/                   # Stylesheets
│   └── JS/                    # Client-side scripts (e.g., sell.js, listed.js)
├── start-server.bat          # Script to start server (Windows)
└── launch.vbs                # Optional script to launch site

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

