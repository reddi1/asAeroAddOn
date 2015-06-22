# asAeroAddOn Script #

[![Build Status](https://travis-ci.org/reddi1/asAeroAddOn.svg?branch=master)](https://travis-ci.org/reddi1/asAeroAddOn)

## Purpose ##

Adds local times to the aircraft performance page.

## Installation ##

### Tampermonkey ###

1. Open Tapermonkey's dashboard.
2. Click on the `Utilities` tab on the right.
3. Paste `https://raw.githubusercontent.com/reddi1/asAeroAddOn/master/airline.user.js` into the text area, and click `Import`.
4. When the editor has loaded, click `Install` (*NOT* `Process with Chrome`).

### Greasemonkey ###

1. Navigate to `https://raw.githubusercontent.com/reddi1/asAeroAddOn/master/airline.user.js`.
2. Right click on the page, and click `Save Page As`.
3. While Firefox is still open, open a File Manager of any sort, and navigate to the directory you saved the script.
4. Drag & drop the script file onto the Firefox window.
5. Press `Install`.

## License

Code licensed under [MIT-LICENSE](https://github.com/reddi1/asAeroAddOn/blob/master/LICENSE)

The source for the airport codes and timezone data is the [openflights.org](https://github.com/jpatokal/openflights/blob/master/data/airports.dat) database.
The database is released under [Open Database License (ODbL) v1.0](https://github.com/reddi1/asAeroAddOn/blob/master/ODbL-LICENSE) and its contents are released under [Database Contents License (DbCL) v1.0](https://github.com/reddi1/asAeroAddOn/blob/master/DbCL-LICENSE).