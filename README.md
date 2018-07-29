# Bus Data

Derived from nextbus in an attempt to avoid throttling their service. No schedule data contained as it's just way too much hassle to keep track of.

## Breakdown

### `routes.json` 

All data contained within data attribute (I needed to include the copyright)
Within data each route is listed under its ID tag name, within which there is:

- title: full name of route
- color: 6 character hex color
- tag: same as key, the identifier used
- oppositeColor: may not be used, just the secondary color
- max/min: extreme coordinates to fit the full route within view
- stops: ....messy. This is an array containing each set of stops which are available. Most services use inbound and outbound, all other options are listed under the name the service uses


### `stops.json`

Similar to routes for setup, data contains:

- lon: longitude
- lat: latitude
- title: full name
- shortTitle: for where the title is too long
- stopId: alternative identifier for stop used in some locations

## legal stuff

All route data is copyright the respective owners (copyright included in files).
