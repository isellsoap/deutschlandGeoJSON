deutschlandGeoJSON
==================

Administrative Grenzen Deutschlands im GeoJSON-Format in unterschiedlichen Qualitätsstufen.

---

Der erschreckende Mangel an vernünftigen Geo-Koordinaten von Deutschland (inklusive Bundesländern, Regierungsbezirken und Kreisen) im praktischen [GeoJSON-Format](http://www.geojson.org/) dürfte mit diesem Repository behoben sein. Wie man bei Betrachtung der Screenshots sehen kann, lassen sich auch mit geringeren Qualitätsstufen sehr gute Ergebnisse erzielen.

## Credits

* Daten-Quelle: [GIS-DATA](http://www.diva-gis.org/gdata)
* Umgesetzt mit [Quantum GIS](http://www.qgis.org/), gute Anregung durch [dieses Tutorial](http://oscarvillarreal.com/2012/07/12/create-any-map-of-the-world-in-svg/).

## Deutschland

### Qualitätsstufen

#### sehr hoch

![Screenshot sehr hohe Qualität](/1_deutschland/1_sehr_hoch.png) 

#### hoch

![Screenshot hohe Qualität](/1_deutschland/2_hoch.png) 

* simplify tolerance: 0,0005
* Knoten: von 84.143 auf 16.086 reduziert (80,88 % weniger)
* Dateigröße: von **3,6 MB** auf **698 KB** reduziert (80,61 % weniger)

#### mittel

![Screenshot mittlere Qualität](/1_deutschland/3_mittel.png) 

* simplify tolerance: 0,005
* Knoten: von 84.143 auf 2.660 reduziert (96,84 % weniger)
* Dateigröße: von **3,6 MB** auf **116 KB** reduziert (96,78 % weniger)

#### niedrig

![Screenshot niedrige Qualität](/1_deutschland/4_niedrig.png) 

* simplify tolerance: 0,02
* Knoten: von 84.143 auf 758 reduziert (99,1 % weniger)
* Dateigröße: von **3,6 MB** auf **23 KB** reduziert (99,36 % weniger)

## Bundesländer

### Qualitätsstufen

#### sehr hoch

![Screenshot sehr hohe Qualität](/2_bundeslaender/1_sehr_hoch.png) 

#### hoch

![Screenshot hohe Qualität](/2_bundeslaender/2_hoch.png) 

* simplify tolerance: 0,0005
* Knoten: von 100.842 auf 32.085 reduziert (68,18 % weniger)
* Dateigröße: von **4,4 MB** auf **1,4 MB** reduziert (68,18 % weniger)

#### mittel

![Screenshot mittlere Qualität](/2_bundeslaender/3_mittel.png) 

* simplify tolerance: 0,005
* Knoten: von 100.842 auf 8.775 reduziert (91,3 % weniger)
* Dateigröße: von **4,4 MB** auf **385 KB** reduziert (91,25 % weniger)

#### niedrig

![Screenshot niedrige Qualität](/2_bundeslaender/4_niedrig.png) 

* simplify tolerance: 0,01
* Knoten: von 100.842 auf 4.481 reduziert (95,56 % weniger)
* Dateigröße: von **4,4 MB** auf **101 KB** reduziert (97,71 % weniger)

## Regierungsbezirke

### Qualitätsstufen

#### sehr hoch

![Screenshot sehr hohe Qualität](/3_regierungsbezirke/1_sehr_hoch.png) 

#### hoch

![Screenshot hohe Qualität](/3_regierungsbezirke/2_hoch.png) 

* simplify tolerance: 0,0005
* Knoten: von 114.777 auf 45.827 reduziert (60,07 % weniger)
* Dateigröße: von **5 MB** auf **2 MB** reduziert (60 % weniger)

#### mittel

![Screenshot mittlere Qualität](/3_regierungsbezirke/3_mittel.png) 

* simplify tolerance: 0,005
* Knoten: von 114.777 auf 14.047 reduziert (87,76 % weniger)
* Dateigröße: von **5 MB** auf **623 KB** reduziert (87,54 % weniger)

#### niedrig

![Screenshot niedrige Qualität](/3_regierungsbezirke/4_niedrig.png)

* simplify tolerance: 0,01
* Knoten: von 114.777 auf 7.344 reduziert (93,6 % weniger)
* Dateigröße: von **5 MB** auf **333 KB** reduziert (93,34 % weniger)

## Kreise

### Qualitätsstufen

#### sehr hoch

![Screenshot sehr hohe Qualität](/4_kreise/1_sehr_hoch.png) 

#### hoch

![Screenshot hohe Qualität](/4_kreise/2_hoch.png) 

* simplify tolerance: 0,0005
* Knoten: von 183.345 auf 113.565 reduziert (38,06 % weniger)
* Dateigröße: von **8,1 MB** auf **5,1 MB** reduziert (37,03 % weniger)

#### mittel

![Screenshot mittlere Qualität](/4_kreise/3_mittel.png) 

* simplify tolerance: 0,005
* Knoten: von 183.345 auf 40.433 reduziert (77,95 % weniger)
* Dateigröße: von **8,1 MB** auf **1,9 MB** reduziert (76,54 % weniger)

#### niedrig

![Screenshot niedrige Qualität](/4_kreise/4_niedrig.png) 

* simplify tolerance: 0,009
* Knoten: von 183.345 auf 22.612 reduziert (87,67 % weniger)
* Dateigröße: von **8,1 MB** auf **1,1 MB** reduziert (86,42 % weniger)
