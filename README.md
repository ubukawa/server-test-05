# server-test-05
Simple server test for tile map (without Azure)

# tilemap
* This test developed the tilemap function. This is a simple tile map and does not fully cover ESRI's tilemap function. Thinking the tilemap used in ArcGIS online, we have prepared a minimum function as below.  
    * Data in tilemaps at any zoomlevel are always 32 by 32 (width and height).
    * At zoom levels until 5, row and column are always 0.
    * At each zoom level, larger than zoom level 5, data in tilemaps at any row/column are the same. (if exist, it is all 1.) 

* Try to use tile map from: https"//<root dir name>/TM/ne-test/<zoom level>/<row>/<column>/<width>/<height>  
    * note1: "ne-test" is a name of dataset.  
    * note2: Both width and height should be 32.
 
