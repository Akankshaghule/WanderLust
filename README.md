🏡 WanderLust – Travel Accommodation Booking Platform

WanderLust is a full-stack web application inspired by Airbnb that allows users to explore, create, and review travel listings across the world.
It includes user authentication, image uploads via Cloudinary, and secure data storage using MongoDB Atlas.

🚀 Live Demo

🔗 https://wanderlust-v24i.onrender.com/listings

🧠 Features

✅ User Authentication

Sign up, login, and session-based authentication using Passport.js.

Authorization ensures users can edit/delete only their own listings.

✅ Listings Management

Users can create, edit, delete, and view listings.

Each listing includes title, description, price, location, and images.

✅ Reviews & Ratings

Add, edit, or delete reviews on listings.

Average rating displayed for each property.

✅ Image Uploads

Integrated with Cloudinary and Multer for cloud-based image storage.

✅ Map Integration

(If you added it) Interactive map to display property locations.

✅ Responsive Design

Built using Bootstrap 5, ensuring mobile-friendly UI.

| Layer              | Technologies Used                     |
| ------------------ | ------------------------------------- |
| **Frontend**       | HTML, CSS, Bootstrap, EJS             |
| **Backend**        | Node.js, Express.js                   |
| **Database**       | MongoDB Atlas                         |
| **Authentication** | Passport.js, Express-Session          |
| **Image Storage**  | Cloudinary, Multer-Storage-Cloudinary |
| **Validation**     | Joi for schema validation             |
| **Hosting**        | Render (Server), Cloudinary (Images)  |


WanderLust/
│
├── models/
│   ├── listing.js
│   ├── review.js
│   └── user.js
│
├── routes/
│   ├── listings.js
│   ├── reviews.js
│   └── users.js
│
├── views/
│   ├── listings/
│   ├── partials/
│   └── users/
│
├── public/
│   ├── css/
│   ├── js/
│   └── images/
│
├── app.js
├── package.json
├── .env (not uploaded)
└── README.md

💡 Future Improvements

Add filtering and sorting features.

Implement advanced search (by location, price, type).

Integrate payment gateway for bookings.

Enable multi-image uploads with previews.
