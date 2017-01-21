# \<speedy-web\>

Front end for speedy-logger built with Polymer 1.0. Use this to connect to your firebase instance storing speedy logger data. It will display bandwidth and latency results. See a working demo [here](https://analytics.mattymil.com).

To get going:
- Clone the project
- Run Bower install
- Add Firebase config details in the ```config``` object located in ```src/speedy-charts/speedy-charts.html```
- Perform the below Polymer setup and build steps
- Deploy from the generated bundled or unbundled folders depending on your server config.

## Install the Polymer-CLI

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your application locally.

## Viewing Your Application

```
$ polymer serve
```

## Building Your Application

```
$ polymer build
```

This will create a `build/` folder with `bundled/` and `unbundled/` sub-folders
containing a bundled (Vulcanized) and unbundled builds, both run through HTML,
CSS, and JS optimizers.

You can serve the built versions by giving `polymer serve` a folder to serve
from:

```
$ polymer serve build/bundled
```

## Running Tests

```
$ polymer test
```

Your application is already set up to be tested via [web-component-tester](https://github.com/Polymer/web-component-tester). Run `polymer test` to run your application's test suite locally.

## Versions
- 1.0.0 Initial release
- 1.1.0 Added favicon.
