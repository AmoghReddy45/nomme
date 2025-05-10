# Nommé - Culinary Events & Food Discovery Platform

Nommé is a platform connecting serious food lovers with culinary creators through authentic social recommendations, underground food events, and private clubs curated by taste—not clout.

## 🚀 Features

### For Foodies

- Visual-first home feed with event carousel
- Personalized food discovery through TasteGraph
- Custom food lists and collaborative collections
- Event RSVPs and social invites
- Profile with taste badges and history

### For Culinary Creators

- Event creation and promotion tools
- RSVP and ticket management
- Analytics and community engagement
- Creator profiles and content sharing

## 🛠 Tech Stack

- **Frontend**: React Native (mobile-first)
- **Backend**: Firebase
- **Authentication**: Firebase Auth
- **Database**: Firestore
- **Storage**: Firebase Storage
- **Payments**: Stripe
- **Calendar**: Google Calendar API
- **Analytics**: Firebase Analytics

## 📱 Project Structure

```
nomme/
├── app/                    # React Native app
│   ├── src/
│   │   ├── components/     # Reusable UI components
│   │   ├── screens/        # Screen components
│   │   ├── navigation/     # Navigation configuration
│   │   ├── services/       # API and service integrations
│   │   ├── hooks/         # Custom React hooks
│   │   ├── utils/         # Helper functions
│   │   ├── constants/     # App constants
│   │   └── types/         # TypeScript type definitions
│   ├── assets/            # Images, fonts, etc.
│   └── config/            # App configuration
├── functions/             # Firebase Cloud Functions
├── docs/                  # Documentation
└── tests/                # Test files
```

## 🚀 Getting Started

### Prerequisites

- Node.js (v16 or later)
- React Native development environment
- Firebase CLI
- Xcode (for iOS development)
- Android Studio (for Android development)

### Installation

1. Clone the repository:

```bash
git clone https://github.com/yourusername/nomme.git
cd nomme
```

2. Install dependencies:

```bash
npm install
```

3. Set up Firebase:

```bash
firebase init
```

4. Start the development server:

```bash
npm start
```

## 🔑 Environment Variables

Create a `.env` file in the root directory with the following variables:

```
FIREBASE_API_KEY=
FIREBASE_AUTH_DOMAIN=
FIREBASE_PROJECT_ID=
FIREBASE_STORAGE_BUCKET=
FIREBASE_MESSAGING_SENDER_ID=
FIREBASE_APP_ID=
STRIPE_PUBLISHABLE_KEY=
```

## 📝 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request
