# WFC
Using the unity WFC assets to understand how the code works
# How to generate tilemap
Add the script TilePainter to draw the map. Give Pallate necessary prefabs to draw the tilemap. For training, add the Training script with the tile gameobject. Compile it in the editor. It will collect the orientation of the gameobject after execution. Now add a gameobject and attach the script OverLapWFC with the gameobject and add the  gameobject that have the script Training in the editor of the OverLapWFC. And generate and run in the editor for tilemap.

![Input Img](https://github.com/jawadefaj/WFC/blob/tile/InputTile.PNG)
![Output Img](https://github.com/jawadefaj/WFC/blob/tile/OutputTile.PNG)
# Constrains
1) All the tiles between two road tiles are rock tile.
2) For the square tile, the indside tiles are flower tile.
3) Each road corner tile is connected with a verticle and a horizontal tile.
