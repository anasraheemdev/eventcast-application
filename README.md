# EventCast V3 (Mobile)

EventCast V3 is a modern **React Native mobile application** designed for event management and live engagement. It allows users to discover, register, and participate in events while giving organizers tools to manage attendees, tickets, and live streaming seamlessly.

---

## 📱 Features
- **Cross-Platform** – Built with React Native for both iOS and Android.
- **Event Discovery** – Browse and search for upcoming events.
- **User Authentication** – Secure signup/login with role-based access.
- **Ticket Booking** – Purchase and manage event tickets directly in the app.
- **Live Streaming** – Watch live events from within the application.
- **Push Notifications** – Get reminders and updates for registered events.
- **Profile & Dashboard** – Personalized dashboard for users and event organizers.

---

## 🛠️ Installation

### Prerequisites
Make sure you have installed:
- Node.js (>= 16.x)
- npm or yarn
- React Native CLI / Expo CLI
- Android Studio / Xcode (for Android/iOS builds)

### Steps
```bash
# Clone the repository
git clone https://github.com/your-username/EventCastV3.git
cd EventCastV3

# Install dependencies
npm install

# Setup environment variables
cp .env.example .env
# (Update .env with API keys, endpoints, and credentials)

# Start the Metro bundler
npm start

# Run on Android
npm run android

# Run on iOS
npm run ios
```

---

## 📂 Project Structure
```
EventCastV3/
├── android/            # Native Android code
├── ios/                # Native iOS code
├── src/                # Application source
│   ├── assets/         # Images, icons, fonts
│   ├── components/     # Reusable UI components
│   ├── navigation/     # React Navigation setup
│   ├── screens/        # App screens (Events, Profile, Tickets, etc.)
│   ├── services/       # API and business logic
│   ├── store/          # Redux or Context API store
│   └── utils/          # Utility functions
├── App.js              # Entry point
├── package.json        # Dependencies and scripts
└── README.md           # Documentation
```

---

## ⚙️ Environment Variables
Configure the `.env` file with:
```
API_BASE_URL=https://api.eventcast.com
STREAM_API_KEY=your_stream_api_key
AUTH_SECRET=your_jwt_secret
PUSH_NOTIFICATIONS_KEY=your_push_service_key
```

---

## 📖 Usage
1. Install and open the app.
2. Sign up or log in.
3. Browse and join upcoming events.
4. Purchase/manage tickets.
5. Watch live events directly inside the app.
6. Get push notifications for updates and reminders.

---

## 🧪 Testing
Run unit and UI tests with:
```bash
npm run test
```

For end-to-end tests:
```bash
npm run e2e
```

---

## 📦 Deployment
- **Android**: Generate APK/AAB via Android Studio or `npm run android:build`
- **iOS**: Build via Xcode or `npm run ios:build`
- Use **Fastlane** or **EAS (Expo Application Services)** for CI/CD pipelines.

---

## 📊 Roadmap
- [ ] Offline mode with local storage
- [ ] QR-based ticket scanning
- [ ] Multi-language support
- [ ] Social sharing & event invites

---

## 🤝 Contributing
Contributions are welcome!
1. Fork the repository
2. Create a new branch (`feature/your-feature`)
3. Commit changes
4. Push and create a PR

---

## 📜 License
Licensed under the **MIT License**.

---
