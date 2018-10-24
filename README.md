deutschlandGeoJSON
==================

Administrative borders of Germany in GeoJSON format in different quality levels.

---

The frightening lack of reasonable geo-coordinates of Germany (including states, districts, and counties) in the practical [GeoJSON format](http://www.geojson.org/) should be resolved by this repository. As you can see from the screenshots, you can achieve very good results even with reduced quality levels.

## Credits

* Data source: [GIS-DATA](http://www.diva-gis.org/gdata)
* Implemented with [Quantum GIS](http://www.qgis.org/), following [this tutorial](http://oscarvillarreal.com/2012/07/12/create-any-map-of-the-world-in-svg/).

## Translations

- [German](https://github.com/isellsoap/deutschlandGeoJSON/blob/master/README.de.md)

## Germany

### Quality levels

#### very high

![Screenshot very high quality](/1_deutschland/1_sehr_hoch.png) 

#### high

![Screenshot high quality](/1_deutschland/2_hoch.png) 

* simplify tolerance: 0.0005
* points: reduced from 84,143 to 16,086 (80.88 % less)
* file size: reduced from **3.6 MB** to **698 KB** (80.61 % less)

#### medium

![Screenshot medium quality](/1_deutschland/3_mittel.png) 

* simplify tolerance: 0.005
* points: reduced from 84,143 to 2,660 (96.84 % less)
* file size: reduced from **3.6 MB** to **116 KB** (96.78 % less)

#### low

![Screenshot low quality](/1_deutschland/4_niedrig.png) 

* simplify tolerance: 0.02
* points: reduced from 84,143 to 758 (99.1 % less)
* file size: reduced from **3.6 MB** to **23 KB** (99.36 % less)

## Federal States

### Quality levels

#### very high

![Screenshot very high quality](/2_bundeslaender/1_sehr_hoch.png) 

#### high

![Screenshot high quality](/2_bundeslaender/2_hoch.png) 

* simplify tolerance: 0.0005
* points: reduced from 100,842 to 32,085 (68.18 % less)
* file size: reduced from **4.4 MB** to **1.4 MB** (68.18 % less)

#### medium

![Screenshot medium quality](/2_bundeslaender/3_mittel.png) 

* simplify tolerance: 0.005
* points: reduced from 100,842 to 8,775 (91.3 % less)
* file size: reduced from **4.4 MB** to **385 KB** (91.25 % less)

#### low

![Screenshot low quality](/2_bundeslaender/4_niedrig.png) 

* simplify tolerance: 0.01
* points: reduced from 100,842 to 4,481 (95.56 % less)
* file size: reduced from **4.4 MB** to **101 KB** (97.71 % less)

## Government Districts

### Quality levels

#### very high

![Screenshot very high quality](/3_regierungsbezirke/1_sehr_hoch.png) 

#### high

![Screenshot high quality](/3_regierungsbezirke/2_hoch.png) 

* simplify tolerance: 0.0005
* points: reduced from 114,777 to 45,827 (60.07 % less)
* file size: reduced from **5 MB** to **2 MB** (60 % less)

#### medium

![Screenshot medium quality](/3_regierungsbezirke/3_mittel.png) 

* simplify tolerance: 0.005
* points: reduced from 114,777 to 14,047 (87.76 % less)
* file size: reduced from **5 MB** to **623 KB** (87.54 % less)

#### low

![Screenshot low quality](/3_regierungsbezirke/4_niedrig.png)

* simplify tolerance: 0.01
* points: reduced from 114,777 to 7,344 (93.6 % less)
* file size: reduced from **5 MB** to **333 KB** (93.34 % less)

## Counties

### Quality levels

#### very high

![Screenshot very high quality](/4_kreise/1_sehr_hoch.png) 

#### high

![Screenshot high quality](/4_kreise/2_hoch.png) 

* simplify tolerance: 0.0005
* points: reduced from 183,345 to 113,565 (38.06 % less)
* file size: reduced from **8.1 MB** to **5.1 MB** (37.03 % less)

#### medium

![Screenshot medium quality](/4_kreise/3_mittel.png) 

* simplify tolerance: 0.005
* points: reduced from 183,345 to 40,433 (77.95 % less)
* file size: reduced from **8.1 MB** to **1.9 MB** (76.54 % less)

#### low

![Screenshot low quality](/4_kreise/4_niedrig.png) 

* simplify tolerance: 0.009
* points: reduced from 183,345 to 22,612 (87.67 % less)
* file size: reduced from **8.1 MB** to **1.1 MB** (86.42 % less)
