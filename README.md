# VDL

![C](https://img.shields.io/badge/c-%2300599C.svg?style=for-the-badge&logo=c&logoColor=white)
[![Licence](https://img.shields.io/static/v1.svg?label=lLicense&message=ZLib&color=blue&style=for-the-badge)](./LICENSE)

VDL - a low-level, cross-platform development library for OpenGL written in portable C(99).

## Features

* Written in portable C (C99)
* Zlib license: free for any project, including commercial ones;
* Cross-platform : Windows and X11 (any system running Xorg)
* Native : Uses `wGL` and `GLX`, `winmm` and `ALSA`.

## Further reading

For further reading, documents are available in [docs](./docs/). The the planning document ([PLAN.md](./docs/PLAN.md)) is a technical sort of changelog.

Homepage : [here](https://adamonair.neocities.org/vdl).

## Build

### Dependencies :

* [WGL](https://registry.khronos.org/OpenGL/api/GL/wgl.h)
* [GLX](https://dri.freedesktop.org/wiki/GLX/)
* [OpenGL](https://www.opengl.org/)
* [stb](https://github.com/nothings/stb)

> [!NOTE]  
> In [CMakeLists.txt](./CMakeLists.txt), you can find the list of dependencies.

## Download

On UNIX, VDL can be installed through the [install script](https://github.com/AdamOnAir/pkg/blob/trunk/installer.sh).
## License

Distribute, modify and use freely under the terms of the [ZLib License](./LICENSE).

<!--
Copyright (C) 2024 Ellouze Adam <elzadam11@tutamail.com>
  
This software is provided 'as-is', without any express or implied
warranty.  In no event will the authors be held liable for any damages
arising from the use of this software.

Permission is granted to anyone to use this software for any purpose,
including commercial applications, and to alter it and redistribute it
freely, subject to the following restrictions:
  
1. The origin of this software must not be misrepresented; you must not
   claim that you wrote the original software. If you use this software
   in a product, an acknowledgment in the product documentation would be
   appreciated but is not required. 
2. Altered source versions must be plainly marked as such, and must not be
   misrepresented as being the original software.
3. This notice may not be removed or altered from any source distribution.
-->
