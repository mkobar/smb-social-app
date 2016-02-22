# snb-social-app

##Social Networks for Buildings (SNB) Ionic and Web App
===
[![License](https://img.shields.io/badge/license-MIT-orange.svg?style=flat-square)](https://github.com/adrianlee44/lorax/blob/master/LICENSE-MIT)

for The Stamford Hackathon, Stamford CT 20 Feb 2016

### The Idea
The idea is to make micro-social networks for building-sized co-located communities, and include the building as both a persona and participant.  Any posts made in the building are automatically aggrated to the building's account and then automatically routed to the correct location or individual in the building (e.g. facilities management, building event coordinators, etc.) and some (most) are also available to all the network members (while in the building).

### How It Works
So this service uses geolocation and a geo-fence to determine the user's location and the building they are linked to.
We tried to use the [estimote](http://estimote.com/) and [Blue Byte](http://www.bluebite.com/) beacons to use the Eddystone URL protocol, which would allow use of the web app or navigation to the buildings web site automatically when the user was within range on a single beacon.  We could not get our hardware to work for this over the weekend, but did find some useful software for this (see resources).

### How It Was Built
This application was built with the Ionic Framework (Angular.js/JavaScript) and uses the Google FireBase service for authentication and cloud data storage.

### Live Demos
Apple *iPhone* and any *Android* smartphones can run the app from the **Ionic View app**, using the preview code: **ba453561**

Live web app version can be found here:  [http://capricious-stream.surge.sh](http://capricious-stream.surge.sh)

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

### Ionic
https://github.com/driftyco/front-page

## License

Released under the [MIT License] (http://opensource.org/licenses/MIT)
Copyright @ 2016 [RKOSecurity] (http://www.rkosecurity.com)

