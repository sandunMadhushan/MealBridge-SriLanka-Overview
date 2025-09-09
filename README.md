# 🍴 MealBridge Sri Lanka

## 📋 Project Overview

**Project overview and documentation for MealBridge Sri Lanka - a real-time food donation platform. This repo contains only project details and demo links, no source code.**

🌐 **Live Demo**: [mealbridge.madhushan.me](https://mealbridge.madhushan.me/)

MealBridge is a modern, real-time platform designed to reduce food waste and hunger by connecting food donors (individuals, restaurants, businesses) with recipients (NGOs, communities, and individuals) and volunteer delivery agents, through an easy digital system.

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
- **Multi-language Support**: Full UI translation in English, Sinhala (සිංහල), and Tamil (தமிழ்)
- **Realtime Data**: All activity updates instantly (Firebase Firestore)
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
- **Build Tool**: Vite
- **State Management**: React Context API + TanStack React Query
- **Auth/Database/Storage**: Supabase (Auth, Database, Storage)
- **Translation**: Google Translate API
- **Styling**: Tailwind CSS
- **UI Components**: Heroicons, Lucide React
- **Charts**: Recharts
- **Routing**: React Router DOM
- **Deployment**: Netlify

## 🚀 Getting Started

### Prerequisites

- Node.js (v16+ recommended)
- Supabase project (with Auth, Database, Storage enabled)
- Netlify/GitHub account for deployment

### Installation

1. **Clone the repository**

```bash
git clone https://github.com/sandunMadhushan/MealBridge-LK.git
cd MealBridge-LK
```

2. **Set environment variables**
   - Copy the example file:

```bash
cp .env.example .env
```

    - Add your Supabase config values in `.env`:

```
VITE_SUPABASE_URL=your_supabase_project_url
VITE_SUPABASE_ANON_KEY=your_supabase_anon_key
```

3. **Install dependencies**

```bash
npm install
```

4. **Start the development server**

```bash
npm run dev
```

Your app will be running at [http://localhost:5173](http://localhost:5173) (Vite's default port)

## 📦 Deployment

- One-click deploy on Netlify (connect repo, set env vars)
- Builds with `npm run build` (output in `/dist`)

## 📱 Usage

- Donors, recipients, and volunteers can all register \& log in via Google or email/password.
- Donors post food, see their dashboard, and manage their profile.
- Recipients search and request listed food.
- Volunteers see requests and deliver as assigned, earning digital badges.

## 📊 Current Statistics

- **Registered Users**: 1,500+
- **Meals Donated**: 3,200+
- **Active NGOs/Orgs**: 150+
- **Major Areas Served**: Colombo, Kandy, Galle, Jaffna

## 🙌 Contributing

1. Fork the repo
2. Create a feature branch (`git checkout -b feature/my-feature`)
3. Commit changes (`git commit -m "Add my feature"`)
4. Push to your branch (`git push origin feature/my-feature`)
5. Open a Pull Request!

**Development Guidelines**

- Follow code style in the project
- Use clear commit messages
- Add/update docs for all significant feature additions

## 📜 License

MIT License — see [LICENSE](LICENSE)

## 👤 Author \& Team

- **Project Lead / Developer:** Sandun Madhushan (sandunhmadhushan@gmail.com)
- [GitHub Profile](https://github.com/sandunMadhushan)
- Contributors: [Sandun Madhushan](https://github.com/sandunMadhushan), [Ovini Wijessoriya](https://github.com/oviniWijesooriya)

## 📞 Contact

- **Email:** mealbridge.lk@gmail.com
- **Website:** [MealBridge Sri Lanka](https://mealbridgelk.netlify.app)
- **GitHub:** [https://github.com/sandunMadhushan/MealBridge-LK](https://github.com/sandunMadhushan/MealBridge-LK)

## 🙏 Acknowledgments

- All Sri Lankan NGOs and restaurants supporting the project
- Open source community (Supabase, React, Tailwind CSS)
- Early testers and volunteers

## 🚧 Roadmap & Future Plans

- [ ] Mobile app (React Native)
- [ ] Analytics dashboards for donors
- [ ] SMS notification support
- [ ] Enhanced mapping features with Google Maps API
- [ ] Advanced filtering and search capabilities
- [ ] Donor/recipient feedback and rating system
- [ ] Volunteer scheduling and coordination system

**Let's build a Sri Lanka where no meal goes to waste and no one goes hungry.**

For more on food security in Sri Lanka, visit [World Food Programme Sri Lanka](https://www.wfp.org/countries/sri-lanka).

**Powered by MealBridge — 2025**
