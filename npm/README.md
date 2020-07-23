# Nepal.Js 
![Last Commit](https://img.shields.io/github/last-commit/ramanic/nepal.js) ![Badge](https://img.shields.io/npm/l/nepal-js)

>A JavaScript Object for all the location in Nepal. It contains all the regions,zones,provinces,districts,city and postal/zip codes.<br>

![Nepal.js](https://github.com/ramanic/Nepal.js/raw/master/screenshots/nepal.png?raw=true "Nepal.js")

## Installation
You can install the package using npm or directly include the js file in your html file.<br>

**Using NPM**<br>
Install the package using following command 
```
npm install nepal-js
```
Impot Package:
```
const Nepal = require('nepal-js');
```

**Directly Including in HTML file.**<br>
Download [Nepal.js](https://raw.githubusercontent.com/ramanic/Nepal.js/master/js/Nepal.js) file and include it insied your HTML file as below,
You can also use minified version [Nepal-min.js](https://raw.githubusercontent.com/ramanic/Nepal.js/master/js/Nepal-mini.js)
```
<script type="text/javascript" src="Nepal.js"></script>

```

## Code Examples

```
Nepal.Cities // Returns list of municipality and vdc of Nepal.
```
![City](https://github.com/ramanic/Nepal.js/raw/master/screenshots/city.png?raw=true "City")

Similarly,
```
Nepal.Districts // Returns list of district in Nepal with postal/zim codes and other information.
Nepal.Zones //Return list of zones in Nepal with headqauters
Nepal.Regions //Return list of Development Regions
Nepal.Provinces //Return list of Provinces with headquater
```
![Examples](https://github.com/ramanic/Nepal.js/raw/master/screenshots/examples.png?raw=true "Examples")

**Some of the built in functions**
```
Nepal.getCitiesByDistrict("Chitwan") //Returns all the vdc and municiplaity in Kaski District

Nepal.getDistrictsByZone("Mechi") //Return all the Districts in Mechi Zone

Nepal.getDistrictsByRegion('Western') //Returns all the Districts if western Region

Nepal.getDistrictsByProvince(1) //Returns all the Districts of Province 1

Nepal.getZonesByRegion('Central') //Returns all the zones in Central Region

Nepal.getPostalCode('Kaski') //Return Postal Codes of Kaski District.

```
![Examples](https://github.com/ramanic/Nepal.js/raw/master/screenshots/examples2.png?raw=true "Examples")

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License
[MIT](https://choosealicense.com/licenses/mit/)



