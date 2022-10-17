# using_sdl

This is me messing around with using SDL2 instead of Winit for window creation in rust.<br>
Currently it only creates a window, but now I need to sort out how I wish to draw to it (OpenGL, WGPU, etc)

<img width="932" alt="Screen Shot 2022-10-17 at 23 20 24" src="https://user-images.githubusercontent.com/61964090/196217096-29e1731f-5774-46dd-abd1-4b826e31a322.png">

## Building and running

This program requires SDL2 to be seperately installed in order to compile. Assuming it is dynamically linked (which i believe it is), you also need SDL2 installed in order to even run it. This is not exactly ideal and may be changed in the future.
