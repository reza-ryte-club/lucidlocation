# lucidlocation
Random location generator

##Installation

npm install -g lucidlocation

##Usage

To get random location:

    var lucidlocation = require('lucidlocation');

    var randomLocation = lucidlocation.getRandomLocation();
    console.log("Latitude: " + randomLocation.latitude + " Longitude: " + randomLocation.longitude);


