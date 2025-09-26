# 🍴 MealBridge Sri Lanka

## 📋 Project Overview

**Project overview and documentation for MealBridge Sri Lanka - an advanced, real-time food donation platform with GPS integration and smart matching technology. This repo contains only project details and demo links, no source code.**

🌐 **Live Demo**: [mealbridge.lk](https://mealbridge.lk/)

MealBridge is a cutting-edge, real-time platform designed to reduce food waste and hunger by intelligently connecting food donors (individuals, restaurants, businesses) with recipients (NGOs, communities, and individuals) and volunteer delivery agents. The platform features GPS-based location services, smart matching algorithms, and a comprehensive backend API for enhanced performance and user experience.

## 🌟 Features

### For Food Donors

- **Quick Registration**: Sign up with email or Google in seconds
- **Easy Food Listing**: List surplus food with quantity, expiry, images, and pickup location
- **GPS Location Capture**: Auto-populate address fields with precise GPS coordinates
- **Smart Matching**: Backend-powered intelligent matching with recipients
- **Donation Dashboard**: Track all your donations and their impact
- **Profile and Notifications**: Manage your info, get reminders and updates

### For Recipients

- **Smart Food Discovery**: GPS-based matching within 30km radius
- **Distance Display**: See exact distance to food listings
- **Match Scoring**: Get personalized match scores based on location and preferences
- **Browse Food Listings**: Search for available donations by location and type
- **Request Donations**: Request food deliveries easily
- **Instant Notifications**: Be alerted when suitable donations become available

### For Volunteers

- **Pickup \& Delivery Tracking**: See donations to deliver based on your location
- **Earn Badges**: Recognition for your community support
- **Volunteer Dashboard**: Track deliveries, hours, and community impact
- **Rating System**: Receive ratings and feedback from recipients
- **Badge System**: Earn digital badges for milestones and achievements

### For Administrators

- **Comprehensive Admin Dashboard**: Full platform management and oversight
- **User Management**: View, edit, activate, suspend, and manage all users
- **Food Listings Moderation**: Approve, reject, or edit food listings for safety
- **Analytics & Reporting**: Advanced analytics with interactive charts and data export
- **Notification Management**: System-wide notification control and user alerts
- **Security Monitoring**: User verification, access control, and security oversight
- **Content Management**: Manage community stories and platform content
- **System Settings**: Configure platform-wide settings and feature toggles
- **Real-time Monitoring**: Live system health and activity monitoring

### Platform Features

- **Multi-role System**: Separate dashboard and permissions for Donor, Recipient, Volunteer, Admin
- **Multi-language Support**: Full UI translation in English, Sinhala (සිංහල), and Tamil (தமிழ্)
- **Realtime Data**: All activity updates instantly (Supabase Database)
- **Backend API**: Cloudflare Workers-powered backend for smart matching and business logic
- **GPS Integration**: Google Maps API for precise location services and distance calculations
- **Smart Matching Algorithm**: Intelligent donor-recipient matching within 30km radius using GPS coordinates
- **Auto-Population Services**: Reverse geocoding to auto-fill address fields from GPS coordinates
- **Real-time Notifications**: Live notification center with instant updates
- **Admin Dashboard**: Comprehensive admin panel for platform management
- **Community Events**: Social features for community building and engagement
- **Analytics & Reporting**: Advanced analytics with interactive charts and data export
- **Security Features**: Role-based access control, rate limiting, and secure authentication
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

## 🔔 Real-time Notification System

MealBridge features a comprehensive real-time notification system that keeps all users informed and engaged:

### Notification Types

- **Food Requests**: Instant alerts when recipients request your donations
- **Food Claims**: Notifications when donations are claimed or status changes
- **Delivery Updates**: Real-time delivery status updates for volunteers and recipients
- **Event Notifications**: Community event invitations and updates
- **System Alerts**: Platform-wide announcements and maintenance notices

### Features

- **Live Updates**: Real-time notifications using Supabase real-time subscriptions
- **Smart Routing**: Notifications automatically route users to relevant dashboard sections
- **Unread Count**: Visual indicators for unread notifications
- **Mark as Read**: Easy notification management with bulk actions
- **Mobile Responsive**: Optimized notification center for all devices
- **Contextual Actions**: Quick actions directly from notification center

### Admin Notification Management

- **System-wide Notifications**: Send announcements to all users or specific roles
- **Priority Levels**: High, medium, and low priority notification management
- **Bulk Operations**: Mass notification management and cleanup
- **Real-time Monitoring**: Live notification feed and system health monitoring

## 👥 Community Features

MealBridge fosters community engagement through social features and collaborative tools:

### Community Events

- **Event Creation**: Users can create and manage community events
- **Event Discovery**: Browse and join events in your area
- **Event Notifications**: Get notified about new events and updates
- **Event Management**: Admin tools for event moderation and oversight

### Success Stories

- **Community Stories**: Share and read success stories from the community
- **Impact Sharing**: Document the positive impact of food sharing
- **Story Management**: Admin content management for community stories
- **Inspiration Feed**: Motivate the community with real success stories

### Social Engagement

- **User Profiles**: Comprehensive profiles with activity history
- **Impact Tracking**: Track and display community impact metrics
- **Badge System**: Recognition system for volunteers and active users
- **Community Building**: Tools to strengthen local food sharing networks

## 🔒 Security Features

MealBridge implements comprehensive security measures to protect users and data:

### Authentication & Authorization

- **Multi-factor Authentication**: Google OAuth + Email/Password authentication
- **Role-based Access Control**: Granular permissions for Donor, Recipient, Volunteer, Admin roles
- **Session Management**: Secure session handling with automatic timeout
- **Route Protection**: Authentication guards for protected routes and admin areas

### Data Protection

- **Input Validation**: Comprehensive form validation and data sanitization
- **SQL Injection Prevention**: Parameterized queries and secure database access
- **XSS Protection**: Content sanitization and secure rendering
- **CSRF Protection**: Cross-site request forgery prevention

### API Security

- **Rate Limiting**: Protection against abuse and DDoS attacks
- **CORS Configuration**: Proper cross-origin resource sharing setup
- **API Key Management**: Secure handling of external API keys
- **Request Validation**: Server-side validation of all API requests

### Admin Security

- **Admin-only Access**: Restricted admin dashboard access
- **Audit Logging**: Security event logging and monitoring
- **User Verification**: Email verification and account validation
- **Security Monitoring**: Real-time security alerts and notifications

## 💻 Technology Stack

### Frontend

- **Framework**: React 18 with TypeScript
- **Build Tool**: Vite
- **State Management**: React Context API + TanStack React Query
- **Styling**: Tailwind CSS
- **UI Components**: Heroicons, Lucide React, Headless UI, Radix UI
- **Charts**: Recharts
- **Routing**: React Router DOM
- **Forms**: Class Variance Authority (CVA)
- **Utilities**: clsx, tailwind-merge

### Backend

- **Runtime**: Cloudflare Workers
- **Framework**: Hono
- **Language**: TypeScript
- **Deployment**: Wrangler CLI

### Services & APIs

- **Auth/Database/Storage**: Supabase (Auth, Database, Storage)
- **Location Services**: Google Maps API (Geocoding, Distance Calculation)
- **Email Notifications**: EmailJS
- **Translation**: Google Translate API
- **Security**: hCaptcha, Cloudflare Turnstile

### Development Tools

- **Linting**: ESLint with TypeScript support
- **Type Checking**: TypeScript 5+
- **CSS Processing**: PostCSS, Autoprefixer
- **Package Manager**: npm

### Deployment

- **Frontend**: Netlify
- **Backend**: Cloudflare Workers
- **Domain**: Custom domain support

## 📱 Usage

- **Donors**: Register, capture GPS location, list food with auto-populated address fields, track donations
- **Recipients**: Use GPS location to find food within 30km radius, see distance and match scores, request meals
- **Volunteers**: See delivery requests, track pickups and deliveries, earn digital badges
- **Smart Matching**: Backend automatically matches donors and recipients based on location, preferences, and availability

## 📊 Current Statistics

- **Registered Users**: 1,500+
- **Meals Donated**: 3,200+
- **Active NGOs/Orgs**: 150+
- **Major Areas Served**: Colombo, Kandy, Galle, Jaffna

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

### ✅ Completed Features

- [x] **GPS Location Services** - Auto-populate address fields with GPS coordinates
- [x] **Smart Backend Matching** - Intelligent donor-recipient matching with distance calculation
- [x] **Google Maps Integration** - Precise location services and distance display
- [x] **Backend API** - Cloudflare Workers-powered business logic
- [x] **Admin Dashboard** - Comprehensive admin panel for platform management
- [x] **Real-time Notifications** - Live notification system with instant updates
- [x] **Community Features** - Events, stories, and social engagement tools
- [x] **Analytics & Reporting** - Advanced analytics with interactive charts
- [x] **Security Features** - Role-based access control and comprehensive security
- [x] **Multi-language Support** - Full UI translation in English, Sinhala, and Tamil
- [x] **Volunteer Badge System** - Recognition system for community volunteers
- [x] **User Management** - Complete user administration and moderation tools

### 🚀 Upcoming Features

- [ ] **Mobile App** - React Native mobile application
- [ ] **SMS Notifications** - SMS support for notifications
- [ ] **Advanced Search** - Enhanced filtering and search capabilities
- [ ] **Feedback System** - Donor/recipient feedback and rating system
- [ ] **Volunteer Scheduling** - Advanced volunteer coordination system
- [ ] **AI-Powered Matching** - Machine learning for improved food matching
- [ ] **Blockchain Integration** - Transparent donation tracking
- [ ] **IoT Integration** - Smart sensors for food quality monitoring

**Let's build a Sri Lanka where no meal goes to waste and no one goes hungry.**

For more on food security in Sri Lanka, visit [World Food Programme Sri Lanka](https://www.wfp.org/countries/sri-lanka).

**Powered by MealBridge — 2025**
