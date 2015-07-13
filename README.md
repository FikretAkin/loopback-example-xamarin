# LoopBack Xamarin SDK example application 

This repository contains a mobile app that demonstrates the Loopback Xamarin SDK.  It contains:

* `Server` directory: Loopback server for the app.
* `Client` directory: The ToDo client app, created in Xamarin Studio with Xamarin Forms for iOS.

## Prerequisites

- Install [Xamarin Studio](http://xamarin.com/studio).
- Install [LoopBack](http://loopback.io/)
- Install [the LoopBack Xamarin SDK](https://github.com/strongloop/loopback-sdk-xamarin)

###  Run the server app

You can either run the LoopBack server app yourself, or connect to the demo app running at http://xamarindemo.strongloop.com.

**To run your own server app**:

1. Go to server folder: 
  ```$ cd server```
1. Install dependencies:
  ```$ npm install```
1.  Run the application:
  ```$ node .```

**To use StrongLoop's server app**

Alternatively, you can run the Xamarin client app against http://xamarindemo.strongloop.com.

Edit [LBXamarinSDK.cs](https://github.com/strongloop/loopback-example-xamarin/blob/master/Client/Todo%20App/TodoApp/TodoApp/LBXamarinSDK.cs) and change BASE_URL to `http://xamarindemo.strongloop.com/api`.

### Compile and run the client app

1. Go to `Client/ToDo App` folder.
1. Open `TodoApp.sln` project in Xamarin Studio.
1. Compile and run.

### Links ###

* [Loopback](http://loopback.io)
* [SDK Repository](https://github.com/strongloop/loopback-sdk-xamarin)
* [Perfected Tech](http://perfectedtech.com)
* [Xamarin Studio](http://xamarin.com)