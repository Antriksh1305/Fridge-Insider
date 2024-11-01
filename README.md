# Fridge Insider

Fridge Insider is a React Native app designed to help users efficiently manage fridge inventory, track expiration dates, and minimize food waste. The app provides timely alerts for near-expiry items, suggests recipes based on available ingredients, and plans to offer scheduling options for expired food disposal or donation.

## Features

- **Inventory Management**: Easily add, view, and manage items in your fridge, with detailed information such as expiration dates, quantities, and categories.
- **Expiration Alerts**: Get timely notifications for items nearing their expiration to help prevent food wastage.
- **Recipe Suggestions**: Discover recipes based on the items currently available in your fridge, helping you make the most of what you have.
- **Upcoming Scheduling Feature**: Schedule notifications for expired items to dispose of or donate, making fridge management easier and more eco-friendly.

## Technologies

- **React Native**: For a cross-platform mobile experience on iOS and Android.
- **JavaScript (ES6+)**: For robust and clean code structure.
- **React Navigation**: Seamless navigation across app screens.
- **Notifications**: Integrated push notifications for expiration reminders.

## Getting Started

### Prerequisites
Ensure you have the following installed:
- [Node.js](https://nodejs.org/) (>= 14.x)
- [npm](https://www.npmjs.com/) (>= 6.x)
- [Expo CLI](https://docs.expo.dev/get-started/installation/)

## Installation

>**Note**: Make sure you have completed the [React Native - Environment Setup](https://reactnative.dev/docs/environment-setup) instructions till "Creating a new application" step, before proceeding.

## Step 1: Start the Metro Server

First, you will need to start **Metro**, the JavaScript _bundler_ that ships _with_ React Native.

To start Metro, run the following command from the _root_ of your React Native project:

```bash
# using npm
npm start

# OR using Yarn
yarn start
```

## Step 2: Start your Application

Let Metro Bundler run in its _own_ terminal. Open a _new_ terminal from the _root_ of your React Native project. Run the following command to start your _Android_ or _iOS_ app:

### For Android

```bash
# using npm
npm run android

# OR using Yarn
yarn android
```

### For iOS

```bash
# using npm
npm run ios

# OR using Yarn
yarn ios
```

If everything is set up _correctly_, you should see your new app running in your _Android Emulator_ or _iOS Simulator_ shortly provided you have set up your emulator/simulator correctly.

This is one way to run your app — you can also run it directly from within Android Studio and Xcode respectively.

## Step 3: Modifying your App

Now that you have successfully run the app, let's modify it.

1. Open `App.tsx` in your text editor of choice and edit some lines.
2. For **Android**: Press the <kbd>R</kbd> key twice or select **"Reload"** from the **Developer Menu** (<kbd>Ctrl</kbd> + <kbd>M</kbd> (on Window and Linux) or <kbd>Cmd ⌘</kbd> + <kbd>M</kbd> (on macOS)) to see your changes!

   For **iOS**: Hit <kbd>Cmd ⌘</kbd> + <kbd>R</kbd> in your iOS Simulator to reload the app and see your changes!



## Roadmap

- [x] Item Tracking & Expiration Management
- [x] Expiration Alerts
- [x] Recipe Suggestions
- [ ] Scheduling for Expired Food
- [ ] Enhanced Recipe Recommendations
- [ ] Integration with Smart Fridges (Long-term)


## Congratulations! :tada:

You've successfully run and modified your React Native App. :partying_face:

### Now what?

- If you want to add this new React Native code to an existing application, check out the [Integration guide](https://reactnative.dev/docs/integration-with-existing-apps).
- If you're curious to learn more about React Native, check out the [Introduction to React Native](https://reactnative.dev/docs/getting-started).

## Contributing

We welcome contributions! Please feel free to submit pull requests to improve Fridge Insider. Ensure your code adheres to our style guidelines and includes relevant tests.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

# Troubleshooting

If you can't get this to work, see the [Troubleshooting](https://reactnative.dev/docs/troubleshooting) page.

# Learn More

To learn more about React Native, take a look at the following resources:

- [React Native Website](https://reactnative.dev) - learn more about React Native.
- [Getting Started](https://reactnative.dev/docs/environment-setup) - an **overview** of React Native and how setup your environment.
- [Learn the Basics](https://reactnative.dev/docs/getting-started) - a **guided tour** of the React Native **basics**.
- [Blog](https://reactnative.dev/blog) - read the latest official React Native **Blog** posts.
- [`@facebook/react-native`](https://github.com/facebook/react-native) - the Open Source; GitHub **repository** for React Native.
