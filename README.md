# Naptime
Demo of Nap logic to reduce jet lag

This demo is run as a command-line utility.  It relies on Node.js.  The flight info and other parameters are supplied by a json file.

## Execution
```
node naptime.js trip0.json
```

## Example Trips
Included are the naptime.js, plus 4 trip examples.

#### trip0.js
Baseline trip, with a single leg, requiring no adjustments to the preferred nap time.

#### trip1.js
Trip, with a single leg

#### trip2.js
Trip, with 2 legs, and a long layover, requiring nap adjustment

#### trip3.js
Trip, with 2 legs, and a short layover, requiring nap adjustment


## Example Output
Included is the output of the console for each trip.  This is located in the results folder, and named the same as the trip with a text extension.
