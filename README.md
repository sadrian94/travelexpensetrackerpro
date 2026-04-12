# 🌍 Travel Expense Tracker Pro

A premium, real-time, multi-currency travel expense tracking application built for groups. Log spending, track categories, and settle up with friends instantly.

![Premium UI Design](https://img.shields.io/badge/UI-Modern%20Glassmorphism-blueviolet)
![Real-time](https://img.shields.io/badge/Sync-Firebase%20Real--time-orange)
![Currency](https://img.shields.io/badge/Features-Multi--Currency-emerald)

## ✨ Features

- **🚀 Real-time Collaboration**: Shared trip IDs allow multiple users to log expenses simultaneously. Changes sync instantly across all devices.
- **💱 Multi-Currency Support**: Log expenses in any global currency (USD, EUR, JPY, etc.). The app automatically fetches live exchange rates and converts them to your trip's base currency.
- **📊 Smart Debt Settlement**: Automatically calculates the most efficient way to "settle up," telling you exactly who owes whom and how much.
- **🏷️ Categorized Tracking**: Organize spending with beautiful icons for Food, Transport, Lodging, Activities, and more.
- **📱 Mobile-First Design**: A responsive, premium UI featuring glassmorphism effects and smooth animations, optimized for on-the-go logging.
- **🔗 Easy Sharing**: No accounts required! Simply share the unique trip URL with your friends to start collaborating.
- **⏱️ Recent Trips**: Quickly switch between your current and previous trips using the built-in history tracker.

## 🛠️ Technology Stack

- **Frontend**: HTML5, Vanilla JavaScript (ES6+ Modules)
- **Styling**: [Tailwind CSS](https://tailwindcss.com/), Custom Glassmorphism CSS
- **Backend**: [Firebase Realtime Database](https://firebase.google.com/products/realtime-database)
- **APIs**: [Exchange Rate API](https://www.exchangerate-api.com/) for live currency conversion
- **Typography**: [Plus Jakarta Sans](https://fonts.google.com/specimen/Plus+Jakarta+Sans) via Google Fonts

## 🚀 Getting Started

### Prerequisites

To run this project locally with real-time syncing, you'll need a Firebase project.

### Setup Instructions

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/travelexpensetrackerpro.git
   cd travelexpensetrackerpro
   ```

2. **Configure Firebase**:
   - Go to the [Firebase Console](https://console.firebase.google.com/).
   - Create a new project.
   - Add a "Web App" to your project.
   - Open `index.html` and locate the `firebaseConfig` object (around line 282).
   - Replace the placeholder values with your actual Firebase configuration:

   ```javascript
   const firebaseConfig = {
     apiKey: "YOUR_API_KEY",
     authDomain: "YOUR_PROJECT_ID.firebaseapp.com",
     databaseURL: "https://YOUR_PROJECT_ID-default-rtdb.firebaseio.com",
     projectId: "YOUR_PROJECT_ID",
     storageBucket: "YOUR_PROJECT_ID.appspot.com",
     messagingSenderId: "YOUR_SENDER_ID",
     appId: "YOUR_APP_ID"
   };
   ```

3. **Set Database Rules**:
   Ensure your Firebase Realtime Database rules allow read/write access (for testing, you can use public rules, but ensure they are secured for production).

4. **Run the App**:
   Since it's a static HTML file, you can simply open `index.html` in any modern web browser or use a local server like `Live Server` in VS Code.

## 🤝 Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.

---

*Handcrafted with ❤️ for travelers everywhere.*
