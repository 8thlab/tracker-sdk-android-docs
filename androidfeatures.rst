Used android features
========================


Library use different features depending on android version

* API level 18+:
	* Bluetooth Low Energy scanning - `Android docs <https://developer.android.com/guide/topics/connectivity/bluetooth-le.html#find>`_
* API level <18:
	* Bluetooth scanning - `Android docs <https://developer.android.com/guide/topics/connectivity/bluetooth.html#DiscoveringDevices>`_


Because of used features apropriate permission are present in `AndroidManifest.xml <https://github.com/8thlab/tracker-sdk-android/blob/master/lib/src/main/AndroidManifest.xml>`_

* BLUETOOTH
* BLUETOOTH_ADMIN
* ACCESS_COARSE_LOCATION
* INTERNET
* ACCESS_NETWORK_STATE