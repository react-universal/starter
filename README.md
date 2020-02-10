<p align="center" style="margin-bottom: 0px !important;">
  <img width="600" src="https://raw.githubusercontent.com/react-universal/react-universal/master/src/images/logo.jpg" alt="React Universal Component" align="center">
</p>

A React Universal starter that builds to the Web, Android, iOS, and Electron. This project is a part of the React Universal ecosystem. Checkout the [React Universal docs](https://github.com/react-universal/react-universal) to learn more.


## Web
React Native on the web is supported by [react-native-web](https://github.com/necolas/react-native-web), please check the documentation to learn more.

```
npm run web
```

Config: `./web/webpack.config.js`. Config sets up an alias for `react-native` to `react-native-web`. Runs on `localhost:8080`.

```
npm run build-web
```
Uses `./web/webpack.config` to build a production web build to `./web/dist`.

<br>

## Electron
Electron with React requires two commands to run and uses [react-native-web](https://github.com/necolas/react-native-web).

```
npm run electron
``` 
Starts the Electron window using config `./electron/main.js` and 

```
npm run server
``` 
Runs react in the electron window using config `./electron/webpack.config.js`.

<br>

## Android
```
npm run android
```
Simply runs `react-native run-android`, read the React Native docs for more information.

<br>

## iOS
```
npm run ios
```
Simply runs `react-native run-ios`, read the React Native docs for more information.

<br>
