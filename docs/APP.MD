# Cityrays Mobile App

## Introduction

The CityRays mobile app is build with React Native. In order to correctly setup your development environment, please follow the steps below.

## How to get started

You can run the mobile app in two ways:

- Using `Expo`
- Using `react-native-cli`

### Expo

Expo is a set of tools and services built around React Native. It's an external platform that helps us build and run our mobile app. 

#### Using simulators

Use the following command to run the app:

```bash
npm run start
```

Then you can either:
- open an Android simulator
- open an iOS simulator
- open the web view

#### Using Expo Go

The [Expo Go app](https://apps.apple.com/us/app/expo-go/id982107779) allows you to run the mobile app locally on your own device. Install the app on your mobile device and keep in mind that your computer and mobile device need to be connected to the same network. Simply scan the QR code that appears in your terminal after you've ran:

```bash
npm run start
```

### React Native CLI

It's also possible to run the mobile app in emulators for both iOS and Android. 

### iOS

`Attention`: A Mac is required to build projects with native code for iOS. Please follow the Expo quickstart discussed above to build the mobile app using Expo instead.

Install all mentioned tools, libs,... in the list below to setup your environment:

- [XCode](https://apps.apple.com/us/app/xcode/id497799835?mt=12)
- [Watchman](https://facebook.github.io/watchman/)
- [Cocoapods](https://cocoapods.org/)
- [Ruby Version Manager](https://rvm.io/). This is needed because the default Ruby version that is shipped with macOS can differ from what is required by React Native. At the time of writing the required version is `2.7.6`. Check your Ruby version by running:

```bash
ruby --version
```

Once the setup is complete you can run the following commands:

```bash
# runs the metro bundler
# alternatively use npm run start
npx react-native start 

npx react-native run-ios
```

You can also run the app in Xcode. Make sure the metro bundler is running and then open the `xcworkspace` in the `ios-folder`.


### Android

## Useful links
- [React Native documentation](https://reactnative.dev/)