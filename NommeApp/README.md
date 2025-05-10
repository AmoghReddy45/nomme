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
├── NommeApp/                # React Native app
│   ├── src/
│   │   ├── components/     # Reusable UI components
│   │   ├── screens/        # Screen components
│   │   ├── navigation/     # Navigation configuration
│   │   ├── services/       # API and service integrations
│   │   ├── hooks/          # Custom React hooks
│   │   ├── utils/          # Helper functions
│   │   ├── constants/      # App constants
│   │   └── types/          # TypeScript type definitions
│   ├── assets/             # Images, fonts, etc.
│   └── config/             # App configuration
├── functions/              # Firebase Cloud Functions
├── docs/                   # Documentation
└── tests/                  # Test files
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

# Getting Started

> **Note**: Make sure you have completed the [Set Up Your Environment](https://reactnative.dev/docs/set-up-your-environment) guide before proceeding.

## Step 1: Start Metro

First, you will need to run **Metro**, the JavaScript build tool for React Native.

To start the Metro dev server, run the following command from the root of your React Native project:

```sh
# Using npm
npm start

# OR using Yarn
yarn start
```

## Step 2: Build and run your app

With Metro running, open a new terminal window/pane from the root of your React Native project, and use one of the following commands to build and run your Android or iOS app:

### Android

```sh
# Using npm
npm run android

# OR using Yarn
yarn android
```

### iOS

For iOS, remember to install CocoaPods dependencies (this only needs to be run on first clone or after updating native deps).

The first time you create a new project, run the Ruby bundler to install CocoaPods itself:

```sh
bundle install
```

Then, and every time you update your native dependencies, run:

```sh
bundle exec pod install
```

For more information, please visit [CocoaPods Getting Started guide](https://guides.cocoapods.org/using/getting-started.html).

```sh
# Using npm
npm run ios

# OR using Yarn
yarn ios
```

If everything is set up correctly, you should see your new app running in the Android Emulator, iOS Simulator, or your connected device.

This is one way to run your app — you can also build it directly from Android Studio or Xcode.

## Step 3: Modify your app

Now that you have successfully run the app, let's make changes!

Open `App.tsx` in your text editor of choice and make some changes. When you save, your app will automatically update and reflect these changes — this is powered by [Fast Refresh](https://reactnative.dev/docs/fast-refresh).

When you want to forcefully reload, for example to reset the state of your app, you can perform a full reload:

- **Android**: Press the <kbd>R</kbd> key twice or select **"Reload"** from the **Dev Menu**, accessed via <kbd>Ctrl</kbd> + <kbd>M</kbd> (Windows/Linux) or <kbd>Cmd ⌘</kbd> + <kbd>M</kbd> (macOS).
- **iOS**: Press <kbd>R</kbd> in iOS Simulator.

## Congratulations! :tada:

You've successfully run and modified your React Native App. :partying_face:

### Now what?

- If you want to add this new React Native code to an existing application, check out the [Integration guide](https://reactnative.dev/docs/integration-with-existing-apps).
- If you're curious to learn more about React Native, check out the [docs](https://reactnative.dev/docs/getting-started).

# Troubleshooting

If you're having issues getting the above steps to work, see the [Troubleshooting](https://reactnative.dev/docs/troubleshooting) page.

# Learn More

To learn more about React Native, take a look at the following resources:

- [React Native Website](https://reactnative.dev) - learn more about React Native.
- [Getting Started](https://reactnative.dev/docs/environment-setup) - an **overview** of React Native and how setup your environment.
- [Learn the Basics](https://reactnative.dev/docs/getting-started) - a **guided tour** of the React Native **basics**.
- [Blog](https://reactnative.dev/blog) - read the latest official React Native **Blog** posts.
- [`@facebook/react-native`](https://github.com/facebook/react-native) - the Open Source; GitHub **repository** for React Native.
