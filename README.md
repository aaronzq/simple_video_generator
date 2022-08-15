# Simple Video Generators
Matlab apps to generate simple videos for imaging research articles. 


## Generate Movie Pair

![Screenshot](./assets/GenerateMoviePair1.jpg)

### Function
Tile two movie side by side and add time stamps and legends (as many as we want). 

### Installation
Open Matlab and double click the __GenerateMoviePair.mlappinstall__ file. The app will be added to the _APPS_ Tab in Matlab. 

### Usage
1. Select two movies (tif or tiff stack, same size) by clicking buttons __Left Frame__ and __Right Frame__;
2. Choose Index Offset and Total frames;
3. Add time stamps and legends (if applicable) by clicking button __Add__ beside their corresponding menus;
4. Preview by draging the __Time__ slider;
5. Click on button __Render__. 

### Options
- Index Offset: The preview frame index will be the frame index in __Time__ slider added by this __Index Offset__.
- Total frames: The total number of frames to be previewed and rendered.
- Adjust image contrast: Adjust __Lower Clip__ and __Upper Clip__ to clip the lower and upper intensity and stretch the histogram.
- Add time stamps: Choose one time stamps from the drop-down menu and edit its position __X__, __Y__ and __Size__. The Time Step has a unit as millisecond. Therefore the time stamp of a certain frame $i$ will be $i * Time Step$ ms.
- Add legends: Similar to time stamps, except that the text box defines the string to show as it is.  