# Cordova tech talk lab

## How to

1. Fork and Clone or Download repo
 `git clone git@github.com:[YOUR GITHUB USER NAME]/react-cordova-boilerplate.git`

2. Install nvm
  ` curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.33.2/install.sh | bash `
  ```
  export NVM_DIR="$HOME/.nvm"
  [ -s "$NVM_DIR/nvm.sh" ] && . "$NVM_DIR/nvm.sh" # This loads nvm
  ```

     https://github.com/creationix/nvm#installation

3. Install node v8.2.1
  `nvm install node v8.2.1`
  - Make sure you are using node v8.2.1
  `nvm use v8.2.1`
  
4. Move into repo
  `cd [you cloned repo directory]`

5. Install dependencies
   `npm install`

6. Install cordova
  `npm i -g cordova`

7. Add cordova browser platform
  `cordova platform add browser`

8. Run app
  `cordova run browser`


## Street Cred
  * Alter the application to suit your fancy

  * Install the andriod and or ios platform(s)
    - https://cordova.apache.org/docs/en/latest/guide/platforms/android/index.htm
    - https://cordova.apache.org/docs/en/latest/guide/platforms/ios/index.html

  * Install on your phone or tablet and use the app!


## Android
  * Install JDK (8 or better)
  * Install Android Studio - https://developer.android.com/studio/install.html
  * Add SDK packages
  * Add an emulator

  ### If you run into this error on Fedora / RHEL install gradle via dnf
  `Error: Could not find an installed version of Gradle either in Android Studio,
or on your system to install the gradle wrapper. Please include gradle 
in your path, or install Android Studio`
  