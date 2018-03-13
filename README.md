# Ember Tutorial + ArcGIS

Lkely the first step in learning Ember.js is the [Super Rentals Tutorial](https://guides.emberjs.com/v3.0.0/tutorial). The Super Rentals application example [implements a very lightweight map control utilizing Google Maps](https://guides.emberjs.com/v3.0.0/tutorial/service/). Although Google Maps is the map control is used, the tutorial utlizes a Utility to "...abstract the Google API away from our Maps service, which will allow for future reuse of the maps API within the application, easier refactoring to alternate maps implementations." This is the starting point for this project, replace Google Maps with the [ArcGIS JavaScript API v4.x](https://developers.arcgis.com/javascript/).

## Current Status

Currently, this is just an idea, something I want to get done. It is an attempt to apply Tom Wayson's excellent work on the [Ember-Esri-loader](https://github.com/Esri/ember-esri-loader) to the Ember Tutorial.

## Prerequisites

You will need the following things properly installed on your computer.

* [Git](https://git-scm.com/)
* [Node.js](https://nodejs.org/)
* [Ember CLI](https://ember-cli.com/)
* [Yarn](https://yarnpkg.com)
* [Google Chrome](https://google.com/chrome/)

## Installation

* `git clone <repository-url>` this repository
* `cd super-rentals`
* `yarn install`

## Running / Development

* `ember serve`
* Visit your app at [http://localhost:4200](http://localhost:4200).
* Visit your tests at [http://localhost:4200/tests](http://localhost:4200/tests).

### Code Generators

Make use of the many generators for code, try `ember help generate` for more details

### Running Tests

* `ember test`
* `ember test --server`

### Linting

* `npm run lint:js`
* `npm run lint:js -- --fix`

### Building

* `ember build` (development)
* `ember build --environment production` (production)

### Deploying

Specify what it takes to deploy your app.

## Further Reading / Useful Links

* [ember.js](https://emberjs.com/)
* [ember-cli](https://ember-cli.com/)
* [ArcGIS JavaScript API](https://developers.arcgis.com/javascript/)
* Development Browser Extensions
  * [ember inspector for chrome](https://chrome.google.com/webstore/detail/ember-inspector/bmdblncegkenkacieihfhpjfppoconhi)
  * [ember inspector for firefox](https://addons.mozilla.org/en-US/firefox/addon/ember-inspector/)
