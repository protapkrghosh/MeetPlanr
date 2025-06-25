# ✨ MeetPlanr

![https://i.ibb.co/YF01QhM7/meetplanr.png](https://i.ibb.co/YF01QhM7/meetplanr.png)

## 📝 Overview

**MeetPlanr** is an open-source web application designed to simplify scheduling meetings across multiple users and time zones.  
It integrates with external calendar services (like Google Calendar) and uses smart algorithms for suggesting the best meeting times.  
Ideal for teams, freelancers, and project managers who want a faster, smarter way to organize meetings.


#### 🌐 Live Demo

🔗 [https://meetplanr.vercel.app](https://meetplanr.vercel.app)


## Features

- 📅 Google Calendar Integration
- 🧠 Smart Meeting Time Suggestions
- 📝 Create & Manage Scheduled Events
- ➕ Create New Event (Custom Event Creation Form)
- 📰 Publish Blogs (Blog Management System)
- 🛠️ Admin Dashboard (User Management, Event Control, Blog Publishing)
- 📧 Email Notifications (SendGrid & Mailgun)
- 📈 Meeting Analytics Dashboard (Chart.js)
- 💳 Stripe Payment Integration (for paid features)
- 📊 Attendance and Meeting Statistics


## 🏗️ Tech Stack

| Layer           | Technologies                            |
|-----------------|-----------------------------------------|
| Frontend        | Next.js, React, Tailwind CSS, DaisyUI   |
| Backend / API   | Node.js, Firebase, Google Calendar API  |
| Database        | MongoDB                                 |
| Authentication  | Firebase Auth, Google OAuth             |
| Email Services  | Nodemailer, SendGrid, Mailgun           |
| Payment Gateway | Stripe                                  |
| UI Enhancements | AOS (Animate on Scroll), Lottie, SweetAlert2 |

## ▶️ Getting Started (Local Setup)
### Prerequisites:

- Node.js
- MongoDB instance
- Firebase Project
- Google Calendar API credentials
- Stripe Account (for payment feature)
- SendGrid, Mailgun credentials (for email service)

### Installation Steps:

```bash
# Clone the repository
git clone https://github.com/yourusername/meetplanr.git
cd meetplanr

# Install dependencies
npm install
```

## 📦 Dependencies
### Main Dependencies:

- next
- react
- react-dom
- axios
- firebase
- firebase-admin
- googleapis
- mongodb
- @tanstack/react-query
- tailwindcss
- daisyui
- chart.js
- react-chartjs-2
- react-hook-form
- sweetalert2
- lottie-react
- moment
- aos
- stripe
- @stripe/react-stripe-js
- @stripe/stripe-js
- nodemailer
- nodemailer-mailgun-transport
- @sendgrid/mail
- react-hot-toast
- react-icons
- swiper
- react-slick
- slick-carousel
- velocityjs
- server-only
- dotenv
- react-player
- react-id-swiper
- react-infinite-logo-slider
- react-countup
- react-awesome-stars-rating
- react-datepicker
- dustjs-linkedin

### Dev Dependencies:

- jest
- @testing-library/react
- @testing-library/jest-dom
- eslint
- eslint-config-next
- daisyui
- jest-canvas-mock
- jest-environment-jsdom
- file-loader
- eslint-plugin-testing-library
- @types/jest
- @types/nodemailer
