# 🎉 Festive Finesse Events

**Festive Finesse Events** is a professional event management platform built with **React**, **TypeScript**, and **Node.js**. This full-stack application is designed to help event planners manage bookings, showcase their portfolios, and interact with clients effortlessly.

![Festive Finesse Events](https://images.unsplash.com/photo-1511795409834-ef04bbd61622?auto=format&fit=crop&q=80)

---

## ✨ Features

- 🎨 **Modern, responsive UI** with dark theme
- 🔐 **Secure admin dashboard** with authentication
- 📸 **Dynamic event gallery** with filtering options
- 💼 **Service packages** showcase
- 📝 **Event booking system** with email notifications
- 💬 **Contact form** with email integration
- ⭐ **Client testimonials** section
- 📱 **Mobile-first design**
- 🔄 **Real-time updates** across the platform
- 🗄️ **SQLite database** for data persistence

---

## 🚀 Tech Stack

### Frontend
- **React 18**
- **TypeScript**
- **Tailwind CSS** for styling
- **Framer Motion** for animations
- **Lucide Icons** for icons
- **React Router DOM** for routing
- **React Hot Toast** for notifications

### Backend
- **Node.js** and **Express** for server
- **Better SQLite3** for database
- **TypeScript** for type safety

---

## 📦 Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/festive-finesse-events.git
   cd festive-finesse-events
2. **Install dependencies:**:
   ```bash
   npm install
3. **Start the development server**:
   ```bash
   npm run dev

---

## 🏗️ Project Structure
   src/
├── components/        # React components
├── lib/               # Utility libraries
├── server/            # Backend API
├── types/             # TypeScript types
└── utils/             # Helper functions

## 🔑 Admin Access
Default admin credentials for demo purposes:

Email: admin@festive.finesse.events
Password: FFE@admin2024
Note: Make sure to change these credentials in a production environment.

## **💡 Key Components**
Frontend
Hero Section: Dynamic landing page with event booking modal.
Services: Displays event planning services offered.
Gallery: Filterable portfolio showcasing previous events.
Products: Displays available event packages and pricing.
Testimonials: Client reviews and feedback.
Contact: Integrated form to contact event planners.
Backend
API Endpoints: RESTful API for managing data (events, messages, gallery).
Database: SQLite for storing event data, messages, and gallery images.
Email Service: Notification system for bookings.
Authentication: Secure admin access for managing bookings and gallery.
📱 Responsive Design
The application is optimized for different screen sizes:
Desktop (1200px+)
Laptop (1024px)
Tablet (768px)
Mobile (320px)
🔒 Security Features
Password hashing for secure storage.
Protected admin routes to restrict access.
Input validation to ensure data integrity.
XSS and CSRF protection to prevent attacks.
Rate limiting to prevent abuse.

📝 License
This project is licensed under the MIT License - see the LICENSE file for details.


