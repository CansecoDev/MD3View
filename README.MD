# MD3View
![Ravenclaw Model in MD3View](https://img.imgur.com/88shPWm.png)

Quake III MD3/MDR model viewer and MD3/GLM exporter. Provides a way to visualize model files and export them to different formats from some id Tech 3 games.

Features:

- Visualize MD3/MDR files.
- Export as MD3 from MDR.
- Export as GLM from MD3 or MDR.
- Multiple view models; wireframe, flat, textured, shaded, LOD, Picmic.
- Advanced animation visualization.

# [Download](https://github.com/CansecoDev/MD3View/releases)

## Installation

- Create a new directory anywhere, this will be your working directory. Then another directory inside called `base`.
- Extract the contents of all asset bundles into that `base` directory; `assets0.pk3`, `assets1.pk3`, and so on, in ascending order, replacing anything when asked for.
- Drop `MD3View.exe` into your working directory.
- You now should have something like this:
```
├── My Work  Directory
│   ├── MD3View.exe
│   ├── base
│   │   ├── botfiles
│   │   ├── botroutes
│   │   ├── cfg
│   │   ├── ...
```

## Building

#### Required software:

- [Visual Studio 17 (like VS Community 2022)](https://visualstudio.microsoft.com/)
- Required VS Workload: **Desktop Development for C++**
- Required Desktop Development for C++ Detail to check (default unchecked): **C++ MFC for latest v143 build tools (x86 & x64)**

#### Procedure:

- Open the `MD3View.sln` solution with Visual Studio 2022 and build it after selecting `Release`.

## Copyright

- Copyright (C) 2010-2011 Matthew Baranowski, Sander van Rossen & Raven Software.
- Licensed under [GPLv2](https://github.com/CansecoDev/MD3View/blob/main/LICENSE.MD).
