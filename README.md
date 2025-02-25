<img src="https://github.com/Appboy/appboy-react-sdk/blob/master/braze-logo.png" width="300" title="Braze Logo" />

# Braze React SDK

Effective marketing automation is an essential part of successfully scaling and managing your business. Braze empowers you to build better customer relationships through a seamless, multi-channel approach that addresses all aspects of the user life cycle Braze helps you engage your users on an ongoing basis.

## SDK Integration

See our Technical Documentation for instructions on integrating Braze into your React Native application.
- [iOS Documentation](https://www.braze.com/documentation/React_Native/iOS/)
- [Android Documentation](https://www.braze.com/documentation/React_Native/Android_and_FireOS/)


## Components

- `AppboyProject` - Contains the AppboyProject sample app with integration examples for the React Native bridge. This sample app integrates the iOS bridge via manual linking, and the iOS SDK via Cocoapods.
- `HelloReact` - Contains the HelloReact sample app, which integrates the iOS bridge using Cocoapods via a local Podspec.

## Running the Sample App

The following commands apply to both sample projects and use the `AppboyProject` directory as an example.

```
cd AppboyProject/
npm install
```

### iOS
Our sample app integrates the native Braze iOS SDK through [Cocoapods](https://guides.cocoapods.org/using/getting-started.html).

From the `AppboyProject` directory:
```
sudo gem install cocoapods
cd ios/
pod install
cd ../
react-native run-ios
```

### Android
From the `AppboyProject` directory:
```
react-native run-android
```
