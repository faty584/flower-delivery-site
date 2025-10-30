# flower-delivery-site

A full-stack MERN (MongoDB, Express.js, React, Node.js) e-commerce flower delivery platform. This project allows users to browse beautiful flower bouquets, add them to their cart, securely check out using Stripe, and manage user authentication. An admin panel is also provided for managing flower products.

###  Customer Features
- Browse flowers with images, categories, prices, and description
- View flower details and see related flowers
- Add items to cart with quantity selection
- Local storage-based cart
- Stripe Checkout integration
- JWT-based login and signup
- Google OAuth sign-in/sign-up

## Live Demo
[Live Demo](https://flower-delivery-website-frontend.onrender.com)

## Tech Stack

| Frontend | Backend | Database | Tools |
|----------|---------|----------|-------|
| React.js | Express.js | MongoDB Atlas | Render (hosting) |
| React Router | Node.js | Mongoose | Stripe API |
| CSS Modules | Multer + Cloudinary | | JWT & Passport.js |


## Authentication

- **JWT**: Used for protecting routes and identifying users.
- **Google OAuth**: Allows users to sign in/up using their Google account.
- **Passport.js**: Handles Google strategy integration.



## Payments

- **Stripe Checkout**: Redirects users to a hosted checkout page.
- Cart data is passed to the backend and used to generate Stripe line items.


## Image Upload

- Admins can upload flower images.
- **Multer** handles image upload.
- **Cloudinary** stores and serves optimized images.


## Getting Started (Local Setup)

flower-delivery-website/
├── client/ # React frontend
│ ├── src/
│ │ ├── components/ # UI Components
│ │ ├── pages/ # SignIn, SignUp, Home, Cart, Admin, etc.
│ │ ├── assets/ # Images, icons, etc.
│ │ └── App.js
├── backend/ # Node + Express backend
│ ├── models/ # Mongoose models
│ ├── controllers/ # Business logic
│ ├── routes/ # API routes
│ ├── middleware/ # JWT auth, Multer, etc.
│ └── server.js
├── .env # Environment variables
└── README.md # You're here!

### Prerequisites:
- Node.js
- MongoDB Atlas
- Cloudinary account
- Stripe account

### Clone the Repo

```bash
git clone https://github.com/faty685/flower-delivery-site
cd flower-delivery-site


👨‍💻 Author
Developed by Fatima Salisu Alhassan
💌 Contact me at mamannurain20@gmail.com
  
