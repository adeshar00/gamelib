This is a C library is meant to simplify the process of building games with OpenGL ES 2.0 and SDL2.  It provides functions to open a new window, render 3D graphics, recognize user input from keyboards/mice/joysticks, and play sounds, amongst other things.  It's written to work with Emscripten, so programs written with this library can be compiled as native executables or as HTML5 games.

Below is a link to the sample I've been using to test this library as I've been building it (it's not very exciting- it simply allows you to float around and look at a few models rendered with a couple of different test shaders).  I'm testing out a crude stereoscopy mode in it at the moment (cross your eyes, and the image will hopefully appear in 3D: hold the N and M keys to adjust the distance between your virtual eyes and make the 3d-ness easier/harder to see).

**Use WASD/Space/C buttons to move around.**

**Right Click and Hold on the canvas to rotate your view.**

(Other keyboard buttons do random things...)

***[Click here for Demo](https://adeshar00.github.io/GameLib/test.html)***
