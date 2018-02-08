node-geolite2
========

Maxmind's GeoLite2 Free Databases

This product includes GeoLite2 data created by MaxMind, available from [http://www.maxmind.com](http://www.maxmind.com).

_forked from https://github.com/runk/node-geolite2 pending acceptance of a PR_

## Usage

```javascript
var geolite2 = require('geolite2');
var maxmind = require('maxmind');

var lookup = maxmind.open(geolite2.paths.city); // or geolite2.paths.country
var city = lookup.get('66.6.44.4');
```

## License

MIT; databases are [CC-BY-SA 4.0](http://creativecommons.org/licenses/by-sa/4.0/). Please see [this page](https://dev.maxmind.com/geoip/geoip2/geolite2/) for preferred attribution.
