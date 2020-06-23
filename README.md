# ionicPushNotificationOneSignal
ionic 5 push notification OneSignal/Firebase

follow this tutorial https://devdactic.com/push-notifications-ionic-onesignal/ for more detail.

## Environment settings 

**Ionic:**
  - Ionic CLI                     : 6.10.1
  - Ionic Framework               : @ionic/angular 5.2.2
  - @angular-devkit/build-angular : 0.901.9
  - @angular-devkit/schematics    : 9.1.9
  - @angular/cli                  : 9.1.9
  - @ionic/angular-toolkit        : 2.2.0

**Cordova:**
  - Cordova CLI       : 9.0.0 (cordova-lib@9.0.1)
  - Cordova Platforms : android 8.1.0
  - Cordova Plugins   : cordova-plugin-ionic-keyboard 2.2.0, cordova-plugin-ionic-webview 4.2.1, (and 4 other plugins)

**Utility:**
  - cordova-res : 0.14.0
  - native-run  : not installed

**System:**
  - NodeJS            : v10.15.0
  - npm               : 6.4.1
  
## Instructions
- download project
- create the corret environment as described above
- esecute npm install
- change **YOUR ONESIGNAL APP ID** and **YOUR ANDROID ID** with your APP ID (OneSignal) and ANDROID ID (firebase) in "https://github.com/AndreaCimetta/ionicPushNotificationOneSignal/blob/a42cdeed1340958a46fcdc86b08b81c1926199df/src/app/app.component.ts#L36"
- **iOS**
  - ionic cordova platform add ios
  - ionic cordova build ios
- **Android**
  - ionic cordova platform add android
  - ionic cordova build android
