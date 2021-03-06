# Realm Draw Demo

Realm Draw is a simple drawing app designed to show off the collaborative features of the [Realm Mobile Platform](https://realm.io/news/introducing-realm-mobile-platform/).

Any number of users may draw on a single shared canvas in any given moment, with contributions from other devices appearing on the canvas in real-time.

This version is the Android version.

## Installation Instructions

1. [Install the Realm Platform](https://realm.io/docs/get-started/installation/developer-edition/#installing-realm-object-server) Developer Edition.
2. Run a local instance of the Realm Platform: `ros start`.
3. Open the Android Project located at `realm-draw/RealmDraw` with Android Studio, and build the Draw app and deploy it to an Android device.
4. When Realm Draw starts you will be automatically be logged in as demo@realm.io and be able to start drawing. The Realm Object server address you enter can be local or it can be an instance running on any of our other supported Linux platforms which may also be downloaded from [Realm](https://realm.io). In either case you should ensure your firewall allows access to ports 9080 and 27800 as these are needed by the application in order to communicate wth the Realm Object Server.


## Screenshots

Nexus 6P Phone<br>
![Nexus 6P](AndroidPhoneScreenshot.png?raw=true "Nexus 6p")


Pixel C Tablet
![Pixel C](AndroidTabletScreenshot.png?raw=true "Pixel C")

