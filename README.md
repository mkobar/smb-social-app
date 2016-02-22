# snb-social-app

##Social Networks for Buildings (SNB) Mobile and Web App
===
[![License](https://img.shields.io/badge/license-MIT-orange.svg?style=flat-square)](https://github.com/mkobar/snb-social-app/blob/master/LICENSE)
![Platform](https://img.shields.io/badge/platform-Android-brightgreen.svg)
![Platform](https://img.shields.io/badge/platform-iOS-blue.svg)
![Platform](https://img.shields.io/badge/platform-Web-orange.svg)

Entry for The Stamford Hackathon, Stamford CT 20 Feb 2016

### The Idea
The idea is to make micro-social networks for building-sized co-located communities, and include the building as both a persona and participant.  Any posts made in the building are automatically aggrated to the building's account and then automatically routed to the correct location or individual in the building (e.g. facilities management, building event coordinators, etc.) and some (most) are also available to all the network members (while in the building).

### How It Works
So this service uses geolocation and a geo-fence to determine the user's location and the building they are linked to.
We tried to use the [Estimote](http://estimote.com/) and [Blue Byte](http://www.bluebite.com/) beacons to use the Eddystone URL protocol, which would allow use of the web app or navigation to the buildings web site automatically when the user was within range on a single beacon.  We could not get our hardware to work for this over the weekend, but did find some useful software for this (see **Resources** below).

### How It Was Built
This mobile application was built with the sweet [Ionic Framework](http://ionicframework.com/) (Angular.js/JavaScript/CSS/HTML5) and uses the Google [FireBase](https://www.firebase.com/) service for authentication and cloud data storage.

### Live Demos
Apple *iPhone* and any *Android* smartphones (or tablets) can run the mobile SNB app from the _free_ **Ionic View app** (available on "the App stores"), using the preview code: **ba453561**

Live web app version of SNB can be found here:  http://capricious-stream.surge.sh

The GitHub repository for the web app is here: https://github.com/mkobar/snb-social-web

Currently the building is hard-coded to the **Stamford Innovation Center** building 

(175 Atlantic Street Stamford, CT 06901 - [View Map](https://www.google.com/maps/place/175+Atlantic+St,+Stamford,+CT+06901/@41.0529486,-73.5420202,17z/)).

Please contact me directly if you wish to use this application for your building.

##Resources

Stamford Hackathon GitHub site: https://github.com/StamfordHackathon

### EddyStone
https://github.com/sandeepmistry/node-eddystone-beacon-scanner

https://github.com/sandeepmistry/node-bleacon

https://github.com/g-ortuno/eddystone-chrome-apps-demo

https://github.com/evothings/cordova-eddystone

https://github.com/dermike/eddystone-bookmarklet

https://github.com/ragingwind/node-eddystone-beacon-emulator

https://github.com/ragingwind/eddystone-beacon-mobile-chrome-app-scanner

https://github.com/don/node-eddystone-beacon

https://github.com/google/beacon-platform

https://github.com/google/eddystone

### iBeacon
https://github.com/KillerCodeMonkey/iBeacon-nfc

### FireBase
https://github.com/ion-book/firebaseStarter

### GeoFence
https://github.com/mkobar/snb-social-geofence

### Ionic
https://github.com/driftyco/front-page

## License

Released under the [MIT License] (http://opensource.org/licenses/MIT)
Copyright @ 2016 [RKOSecurity] (http://www.rkosecurity.com)

