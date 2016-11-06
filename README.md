# FP-Rotation  
## Library for first person movement on BGT audiogames.  
With this BGT library you can implement a easy movement function to your BGT audiogame projects. The library include the following features:  
* 2D and 3D first person movement function including x, y and z axis  
* Calculate the facing direction using the 4 cardinal points and its variants  
* Calculate a 1D, 2D and 3D distance between the player and any point on the map  
* Calculate the angle of facing between the player and any point on a 2D map  
* Calculate a closer facing direction of the player  
* Fix the degrees that the player is facing at a range of 0 to 360

### Requirements  
BGT Engine version 1.1 (revision 1)

### How to use FP-Rotation library?  
First you need to copy a FP-Rotation src dir to your audiogame project path.  
In your main script file add the following line at the top:  
> \#include "src/fp_rotation.bgt"  
Now you can use all the functions of FP-Rotation library

### Credits  
This BGT library is a modified and improved version of rotation library created by [Samtupy][1]. Special thanks for him to create this BGT library.  
I modified the original library to implement some new features and improve performance, also the source code now complies with the common directives of writing code to be much more understandable.

* Samtupy Twitter account: [@samtupy1][2]
* SiegSBDeveloper Twitter account: [@SiegSBDeveloper][3]

[1]: http://www.samptupy.com
[2]: https://twitter.com/samtupy1
[3]: https://twitter.com/SiegSBDeveloper