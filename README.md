# 🌍 Wanderlust

**Wanderlust** is a web application inspired by **Airbnb**, designed to help users discover, list, and book unique travel accommodations. It is built using JavaScript, Node.js, Express.js, EJS, and other modern web technologies. The application follows the **MVC (Model-View-Controller)** architecture for maintainability and scalability.

---

## 🚀 Key Features

- **🌐 Explore Listings**  
  Users can browse a wide range of listings using filters such as location, price range, and amenities.

- **🏡 Add Your Own Listings**  
  Registered users can create their own listings with images, descriptions, and pricing details.

- **📅 Booking Management**  
  Users can book available listings and manage their bookings through a simple and intuitive interface.

- **👥 User Management**  
  Secure registration and login system using **Passport.js**. Listing owners can edit or delete their own listings, while guests can only book them.

---

## 🧰 Technology Stack

### 🌐 Frontend:
- **HTML** – Page structure  
- **CSS** – Styling and layout  
- **JavaScript** – Dynamic interactivity  
- **Bootstrap** – Responsive design

### 🛠️ Backend:
- **Node.js** – Server-side runtime  
- **Express.js** – RESTful routing and middleware  
- **EJS** – Templating engine for dynamic views  
- **Passport.js** – Authentication and session management  
- **NPM Packages** – Additional functionality like flash messages, form validation, etc.

### ☁️ Cloud & APIs:
- **Cloudinary** – For image upload and management  
- **Mapbox** – For location-based maps integrated in listing views

---

## 🔒 Prerequisites & Setup

- **Node.js** and **npm** installed
- **MongoDB** setup (local or cloud)
- Create a `.env` file and include the following:
  ```env
  MAPBOX_TOKEN=your_mapbox_token
  CLOUDINARY_CLOUD_NAME=your_cloud_name
  CLOUDINARY_KEY=your_key
  CLOUDINARY_SECRET=your_secret
