opengl8thfirstexample
=====================

OpenGL Redbook 8th Edition First Example

Compile with
============
g++ -g -o tri triangles.cpp LoadShader.cpp -lglut -lGLEW -lGLU -lGL -lX11 -lm

john@zerofluid:~/Downloads/openglfirst/another/opengl8thfirstexample$ glxinfo | grep OpenGL
OpenGL vendor string: NVIDIA Corporation
OpenGL renderer string: GeForce GT 610/PCIe/SSE2
OpenGL version string: 4.3.0 NVIDIA 313.30
OpenGL shading language version string: 4.30 NVIDIA via Cg compiler
OpenGL extensions:

john@zerofluid:~/Downloads/openglfirst/another/opengl8thfirstexample$ uname -a
Linux zerofluid 3.8.0-26-generic #38-Ubuntu SMP Mon Jun 17 21:43:33 UTC 2013 x86_64 x86_64 x86_64 GNU/Linux

Someone on StackOverflow sent me triso.cpp as a one file version of the introductory program. Whoever you are: thank you very much again. I really appreciate it.
