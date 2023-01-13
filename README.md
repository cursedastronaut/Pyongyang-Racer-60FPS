# Pyongyang-Racer-60FPS
Pyongyang Racer game at 60FPS

Why ?
----------------


Pyongyang Racer is a game I like playing showing others, to show
how North Korea (DPR Korea) can handle game-making.
When made, this game was meant to run on low-hardware with a
HUGE latency. Now, since our computers have no such limitations,
and that Flash is pretty dead, I decided "Why not make it fluid"

The code
---------------

Most of the code is in src/, but these are also in the SWF file.
The game is based on PaperVision3D, a 3D engine for flash, but also seems to be based on a game called Rock Racer...? I did not find any information about it.

The **text** said by the **traffic girls**, and other UI element is stored in [common.txt](https://github.com/cursedastronaut/Pyongyang-Racer-60FPS/blob/master/common.txt).

The text bubbles appearing when you find a picture of a "monument" are stored in [info.dat](https://github.com/cursedastronaut/Pyongyang-Racer-60FPS/blob/master/info.txt).

Finally, the whole map seems to be stored in [1.dat](https://github.com/cursedastronaut/Pyongyang-Racer-60FPS/blob/master/1.dat).

Is DeltaTime implemented ?
---------------
No. With little, to no information on the 3D engine and me having to do other things, I couldn't find a way to implement deltaTime. The game is meant to be run at 60FPS, and the values have been divided by 5 to match the original gameplay. (The game originately ran at 12FPS, and 60/12 = 5).