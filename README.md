# React Native


## Introduction 

<ul>
<li>Build mobile apps using JavaScript.</li>
<li>Same designs as React.</li>
<li>It uses the same fundamental UI building blocks as regular iOS and Android apps.</li>
<li>One can use both Class based and Function based components</li>
<li>Features:</li>
<ul>
<li>React – Framework for building web and mobile apps using JavaScript</li>
<li>Native –  Native component controlled by JS</li>
<li>Platforms – Supports both iOS and Android</li>
</ul>
</ul>

### Advantage

* No need to learn new language or framework for developing mobile application.
* Develop cross platform applications
* Huge community around React Native

### Limitations

* If some native component is required which is not created then you need to write platform (Android or iOS) specific code.


## How to Create React Native Apps
* Expo Go
    * An open-source platform for making universal native apps for Android, iOS, and the web with JavaScript and React.
    * Quick setup
    * Beginner friendly
* React Native CLI
    * Needs android studio
    * Setup is a bit time taking
    * Used for more advanced applications


## Creating apps with Expo

Use the boiler plate to create a sample application.

```sh
npx create-expo-app myFirstApp
```

Edit `App.js` and put `Hello World`.

```js
<View style={styles.container}>
    <Text>Hello World!</Text>
    <StatusBar style="auto" />
</View>
```

Let's run the application. 

```sh
npm start
```
Install `Expo Go` app from Play store and App store. Make sure your phone and laptop are connected with same wifi.
<br>
You will get a QR code which you have to scan from phone. And the app will start building on your phone.