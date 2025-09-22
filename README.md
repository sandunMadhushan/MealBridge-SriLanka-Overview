# 🍴 MealBridge Sri Lanka

## 📋 Project Overview

**Project overview and documentation for MealBridge Sri Lanka - an advanced, real-time food donation platform with GPS integration and smart matching technology. This repo contains only project details and demo links, no source code.**

🌐 **Live Demo**: [mealbridge.lk](https://mealbridge.lk/)

MealBridge is a cutting-edge, real-time platform designed to reduce food waste and hunger by intelligently connecting food donors (individuals, restaurants, businesses) with recipients (NGOs, communities, and individuals) and volunteer delivery agents. The platform features GPS-based location services, smart matching algorithms, and a comprehensive backend API for enhanced performance and user experience.

## 🌟 Features

### For Food Donors

- **Quick Registration**: Sign up with email or Google in seconds
- **Easy Food Listing**: List surplus food with quantity, expiry, images, and pickup location
- **Donation Dashboard**: Track all your donations and their impact
- **Profile and Notifications**: Manage your info, get reminders and updates

### For Recipients

- **Browse Food Listings**: Search for available donations by location and type
- **Request Donations**: Request food deliveries easily
- **Instant Notifications**: Be alerted when suitable donations become available

### For Volunteers

- **Pickup \& Delivery Tracking**: See donations to deliver based on your location
- **Earn Badges**: Recognition for your community support

### Platform Features

- **Multi-role System**: Separate dashboard and permissions for Donor, Recipient, Volunteer
- **Multi-language Support**: Full UI translation in English, Sinhala (සිංහල), and Tamil (தமிழ্)
- **Realtime Data**: All activity updates instantly (Supabase Database)
- **Backend API**: Cloudflare Workers-powered backend for smart matching and business logic
- **GPS Integration**: Google Maps API for precise location services and distance calculations
- **Smart Matching Algorithm**: Intelligent donor-recipient matching within 30km radius using GPS coordinates
- **Auto-Population Services**: Reverse geocoding to auto-fill address fields from GPS coordinates
- **Enhanced Notifications**: Real-time notifications with EmailJS integration
- **Profile Editing**: Change your info and photo at any time
- **Mobile-responsive UI**: Works on phone, tablet, and desktop
- **Secure Auth**: Google + Email/Password sign-in

## 🌐 Multi-Language Support

MealBridge supports three languages to serve Sri Lanka's diverse community:

- **🇬🇧 English** - Default language for international users
- **🇱🇰 සිංහල (Sinhala)** - Native language support for Sinhala speakers
- **🇱🇰 தமிழ் (Tamil)** - Native language support for Tamil speakers

### How it Works

- **Google Translate Integration**: Powered by Google Translate for real-time, accurate translations
- **Smart Language Detection**: Automatically detects user's browser language preference
- **Persistent Preferences**: Remembers your language choice across sessions
- **Seamless Experience**: Smooth transitions with loading indicators and notifications

### Features

- Language selector in the header for easy switching
- Real-time translation with smooth animations
- Mobile-responsive language picker
- Accessibility-compliant design
- Local storage of language preferences

To change language, simply click the language selector (🌐) in the header and choose your preferred language.

## 💻 Technology Stack

- **Frontend**: React 18 with TypeScript
- **Backend**: Cloudflare Workers with Hono framework
- **Build Tool**: Vite
- **State Management**: React Context API + TanStack React Query
- **Auth/Database/Storage**: Supabase (Auth, Database, Storage)
- **Location Services**: Google Maps API (Geocoding, Distance Calculation)
- **Email Notifications**: EmailJS
- **Translation**: Google Translate API
- **Styling**: Tailwind CSS
- **UI Components**: Heroicons, Lucide React
- **Charts**: Recharts
- **Routing**: React Router DOM
- **Deployment**: Netlify (Frontend) + Cloudflare Workers (Backend)

## 📱 Usage

- **Donors**: Register, capture GPS location, list food with auto-populated address fields, track donations
- **Recipients**: Use GPS location to find food within 30km radius, see distance and match scores, request meals
- **Volunteers**: See delivery requests, track pickups and deliveries, earn digital badges
- **Smart Matching**: Backend automatically matches donors and recipients based on location, preferences, and availability

## 📊 Current Statistics

- **Registered Users**: 2,500+
- **Meals Shared**: 50,000+
- **Partner Businesses**: 150+
- **Cities Covered**: 25
- **Major Areas Served**: Colombo, Kandy, Galle, Jaffna, Anuradhapura

## License

**All Rights Reserved** © 2025 Sandun Madhushan

This project and all associated documentation, code, concepts, and intellectual property are the exclusive property of Sandun Madhushan. No part of this project may be reproduced, distributed, or transmitted in any form or by any means, including photocopying, recording, or other electronic or mechanical methods, without the prior written permission of the owner, except in the case of brief quotations embodied in critical reviews and certain other noncommercial uses permitted by copyright law.

For permission requests, contact: sandunhmadhushan@gmail.com

## 👤 Author \& Team

- **Project Lead / Developer:** Sandun Madhushan (sandunhmadhushan@gmail.com)
- [GitHub Profile](https://github.com/sandunMadhushan)
- Contributors: [Sandun Madhushan](https://github.com/sandunMadhushan), [Ovini Wijessoriya](https://github.com/oviniWijesooriya)

## 📞 Contact

- **Email:** contact@mealbridge.lk
- **Website:** [MealBridge Sri Lanka](https://mealbridge.lk)
- **GitHub:** [https://github.com/sandunMadhushan](https://github.com/sandunMadhushan)

## 🙏 Acknowledgments

- All Sri Lankan NGOs and restaurants supporting the project
- Open source community (Supabase, React, Tailwind CSS)
- Early testers and volunteers

## 🚧 Roadmap & Future Plans

- [x] **GPS Location Services** - Auto-populate address fields with GPS coordinates
- [x] **Smart Backend Matching** - Intelligent donor-recipient matching with distance calculation
- [x] **Google Maps Integration** - Precise location services and distance display
- [x] **Backend API** - Cloudflare Workers-powered business logic
- [ ] Mobile app (React Native)
- [ ] Analytics dashboards for donors
- [ ] SMS notification support
- [ ] Advanced filtering and search capabilities
- [ ] Donor/recipient feedback and rating system
- [ ] Volunteer scheduling and coordination system

**Let's build a Sri Lanka where no meal goes to waste and no one goes hungry.**

For more on food security in Sri Lanka, visit [World Food Programme Sri Lanka](https://www.wfp.org/countries/sri-lanka).

**Powered by MealBridge — 2025**
