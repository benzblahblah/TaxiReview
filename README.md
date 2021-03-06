# Taxi Review

This hybrid mobile application is a part of the Hybrid Mobile Development (CS 4404) project that created by Assumption University students.

# Getting Started

### How to set up:

Download and install the latest [Node.js](https://nodejs.org/en/). Then, install the Ionic CLI and Cordova:

```bash
$ npm install -g ionic cordova
```

### How to run with the Ionic CLI:

First, clone this repository and install all the required dependencies:

```bash
$ git clone https://github.com/Cwanyo/TaxiReview
$ cd TaxiReview
$ npm install
```

After all the dependencies are installed, run the following command to launch the app in the browser:

```bash
$ ionic serve
```

To run it on ios:

```bash
$ ionic cordova platform add ios
$ ionic cordova run ios
```

or on android:
```bash
$ ionic cordova platform add android
$ ionic cordova run android
```

# Architecture
- [Ionic 3](https://ionicframework.com) & [Cordova](https://cordova.apache.org) - The hybrid application framework
- [Firebase](https://firebase.google.com) - Used for authentication, realtime database, cloud storage and hosting

# API
- [OpenALPR](https://github.com/openalpr/openalpr) - Automatic license plate recognition library

# Description
The application that allows users to find and check taxi reviews from other users in realtime

<p align="center">
    <img src="doc/Poster_taxireview_A1.png" height="750px">
</p>

# Features

### Account registration 
- Login via Google or Facebook

### Find taxi
- Take a photo or typing in the licence plate number to find the taxi

### Create taxi review
- Give rating according to categories (e.g. service,politeness or cleanness)
- Comment in text

### View reviews
- Show taxi details
- Show overall rating and comment from other users in realtime

# Prototype
![Prototype Taxi Review](doc/prototype.png)
Link to our [prototype](https://creator.ionic.io/share/dd7f0f339376)

# Known issues and bugs
- There are no effective ways to sort data in the descending order for firebase realtime database

# Contributors
- Chatchawan yoojuie
- Vorapat phorncharroenroj

Link to our [website](https://taxireview-wvn.firebaseapp.com)