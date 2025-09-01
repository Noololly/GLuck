# GLuck

This is my first attempt at writing a program to render something.

## Libraries used

In this program I used OpenGL with [GLFW](https://www.glfw.org/) to window it and [GLAD](https://github.com/Dav1dde/glad) to load OpenGL instead of using my system headers.
In the example by GLFW, they used a linear algebra library called [linmath.h](https://github.com/datenwolf/linmath.h) 

## Compiling

If, for some reason, you want to try out my code; here are some instructions :)

Clone the repo:
```bash
git clone https://github.com/noololly/GLuck.git
```
```bash
cd GLuck && mkdir build && cd build
```
```bash
cmake .. && make -j$(nproc)
```
```bash
chmod +x GLuck
./GLuck
```
