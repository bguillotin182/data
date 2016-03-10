## data

JSON files that may be used during training sessions.

### astro.json

Data mainly extracted from: https://en.wikipedia.org/wiki/List_of_Solar_System_objects_by_size, using [csvtojson](https://www.npmjs.com/package/csvtojson)

Other great resource (in French): http://www.le-systeme-solaire.net

#### sample

```js
{
  "name": "Uranus",
  "radius": 25362,
  "volume": 68340,
  "mass": 86832,
  "density": 1.27,
  "gravity": 8.87,
  "distance": 2871,
  "satellitesCount": 27,
  "hasRings": true,
  "discoveredAt": [1781, 3, 13],
  "type": "ice giant"
}
```
