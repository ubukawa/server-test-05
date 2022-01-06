# server-test-05
Simple server test for tile map (without Azure)

# tilemap
* This test tried to develop a minimum tilemap function. This is a simple tilemap and does not fully cover ESRI's tilemap function. Thinking the tilemap function used in ArcGIS online, we have prepared a minimum function as below.  
    * Data in tilemaps at any zoomlevel are always 32 by 32 (width and height).
    * At zoom levels until 5, row and column are always 0.
    * At each zoom level, larger than zoom level 5, data in tilemaps at any row/column are the same. (if exist, it is all 1.) 

* Try to use tile map from: https"//(root dir name)/TM/ne-test/(zoom level)/(row)/(column)/(width)/(height)  
    * note1: "ne-test" is a name of dataset.  
    * note2: Both width and height should be 32.

# usage
```
git clone https://github.com/ubukawa/test-server-05
cd test-server-05
npm install
node app.js
```
(ctrl+c to stop)

# References
* ArcGIS REST API: https://developers.arcgis.com/rest/services-reference/enterprise/tile-map.htm
* Observation of ArcGIS Online tilemap function (in Japanese): https://qiita.com/T-ubu/items/6360252ece6c792732c7
* Traial of making static tilemap with GitHub page (in Japanese): https://qiita.com/T-ubu/items/317624fa7652aff9b9ed
 
