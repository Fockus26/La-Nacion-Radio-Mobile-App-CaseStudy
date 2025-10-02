# 📻 La Nación Radio – Mobile App

A Flutter mobile application developed for La Nación Radio, the radio and podcast branch of La Nación, Venezuela’s largest news company.
The project included the design and implementation of a new mobile experience for news, podcasts, radio stations, reels, company directories, and integrated advertising.

---

## 🌍 Overview

The app integrates the multimedia ecosystem of La Nación Radio, combining live radio, podcasts, news, reels, company directories, and ads in one single experience.

A splash screen ensures proper controller loading, with retry logic in case of connection errors.
The interface highlights the brand identity with a frosted-glass style AppBar, custom banners, and a persistent mini-player across all views.

---

## ✨ Features

- ⏳ Splash screen with error handling (retry on failed loading after 30s)
- 📰 News view with categories, infinite scroll, and in-app WebView integration
- 🎙️ Radio & Podcasts with modal details (hosts, schedules, topics) + mini-player
- 📻 Live Radio Banner with quick access to the main podcast stream
- 🏢 Company directory with search, category filters, and contact info
- 🎬 Instagram Reels & YouTube video integration
- 📊 Ads integration with intercalated personalized banners across all sections
- 🎨 Custom AppBar with frosted-glass blur effect
- 📱 Bottom navigation for Home, Radio, News, and Companies

---

## 🛠 Tech Stack

- **Framework:** Flutter (Dart)
- **Backend:** WordPress REST API (direct integration)
- **Audio:** Just Audio / Audio Handler
- **Design:** Custom UI (Material + Frosted Glass)
- **Ads:** Custom ad manager integration

---

## 📂 Project Structure
```text
assets/
 ├── audio/
 ├── fonts/
 ├── icons/
 ├── images/
 └── .env
lib/
 ├── main.dart
 ├── app/
 │   ├── app_state.dart
 │   └── splash_wrapper.dart
 ├── config/
 │   ├── app_theme.dart
 │   ├── constants.dart
 │   ├── custom_nav_style.dart
 │   ├── env_constants.dart
 │   └── text_styles.dart
 ├── utils/
 │   └── responsive_values.dart
 ├── widgets/
 │   ├── companies/...
 │   ├── radio/...
 │   ├── reels/...
 │   ├── ad_banner.dart
 │   ├── connection_error_dialog.dart
 │   ├── custom_bottom_navigation_bar.dart
 │   └── ...
 └── dashboard/
     ├── controllers/...
     ├── models/...
     └── views/...
```

---

## 📸 Showcase

_(Screenshots, GIFs, or demo videos can be added here)_

---

## ⚙️ Installation & Setup

⚠️ This project was developed for a private client and is not publicly available.

The app was built and delivered using:

- Flutter SDK (v3.x or higher)
- Dart (>=2.17)
- Android Studio / VS Code with Flutter plugin
- WordPress REST API + media APIs (YouTube, Instagram)
- Custom ad manager and modular controllers

---

## 📖 Case Study

The project was delivered to La Nación Radio as part of their digital transformation strategy.
The goal was to extend their presence beyond traditional news into radio, podcasts, and digital advertising while maintaining a consistent and modern mobile-first experience.

The development required handling multiple API integrations (WordPress, YouTube, Instagram) while ensuring smooth performance on mid-range devices.
Custom UI components such as the frosted-glass AppBar, persistent mini-player, and ad banners were implemented to reinforce brand identity and enhance user experience.

---

## 📈 Learnings & Insights

- Integrating multiple APIs in a single Flutter app required modular controller architecture for maintainability and scalability.
- Implementing a mini-player with background audio highlighted the complexity of state synchronization across navigation layers.
- Designing a frosted-glass AppBar improved aesthetics but required optimization for mid-range devices.
- Ads as reusable components simplified customization and future expansion.
- Balancing multimedia content (radio, news, reels, podcasts) emphasized the importance of clear information hierarchy to avoid overwhelming users.

---

## 📜 License

This project was developed for La Nación Radio (Venezuela).
Source code is available for reference but not for commercial redistribution.
