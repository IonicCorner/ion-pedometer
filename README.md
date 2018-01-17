# ion-pedometer
Ionic Native Padometer demo (download ion-pedometer.apk)

*NOTE* - this functionality/Pligin Only working on real Device, iOS have some extra features which is not available in android.

step 1
-------------------
Install the Cordova and Ionic Native plugins

$ ionic cordova plugin add cordova-plugin-pedometer

$ npm install --save @ionic-native/pedometer

step 2
------------------
import this line to app.module.ts and perticuler page.ts file.

import { Pedometer } from '@ionic-native/pedometer';

constructor(private _ngZone: NgZone,
  			public navCtrl: NavController,
  			public pedometer: Pedometer) {
        
  }

step 3
-----------------
use pedometer functions for get pedometer updates.

1- startPedometerUpdates()

2- stopPedometerUpdates()

