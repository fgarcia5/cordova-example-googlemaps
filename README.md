# Cordova App + Google Maps PLugin
Cordova App - Proof of concept Google Maps Plugin (https://github.com/mapsplugin/cordova-plugin-googlemaps/)

## :large_blue_diamond: Installation

### Step 1: Start by cloning this repo

```bash
$ git clone https://github.com/fgarcia5/cordova-example-googlemaps.git
```
### Step 2: Setting Google Maps API Key
Open `cordova-example-googlemaps/config.xml` and set keys in `GOOGLE_MAPS_ANDROID_API_KEY` and `GOOGLE_MAPS_IOS_API_KEY` properties

### Step 3: Building and Running the Cordova App
```bash
// Only first time
$ npm install
$ npm install -g cordova # you should have cordova installed

// Into project folder
$ cordova platform add [android|ios] # the plugins will be added automatically
$ cordova [run|emulate] [android|ios]
```
