
# Tile Game

Tile Game created using pygame and PIL library In the code that will be in the separate file, a tile game is implemented. In this game, the user can input a 300x300 image to play with. The game takes this image and cuts it to the specifications that the user suggests. The user can suggest the size of the square matrx side to be anywhere from 3 - 9. The image is sliced and each individual image is cropped to slightly smaller than its actual size. Each image then has a border imposed on it so that it conforms to the grid. The reason for this is because the idea behind the game was to have dxd - 1 images where d is the size of the square matrix. The final space would be a blank spot where each image was physically moved so that a slight animation could be een as well. The only problem was that it left a trainling space. Because of this we imposed the border. For the rest of the code, pygame was used wherein the tile movement was specified for each movement. The moves were also blocked if it would mean that the tile would leave the border of the game. The frames per second as well as the randomization moves before the start of the game can be specified. The randomization actually performs moves in front of the user. The jumble button also creates an infinite loop which can only be stopped by pushing the spacebar. The game itself can be played using both the conventional arrow keys and the WASD set as well. The code has not been modified yet to include the mouse input or touch input but that is their for further work. Suggestions appreciated. Enjoy!

## Requirements

```python
pip3 install image_slicer
pip3 install pygame
```