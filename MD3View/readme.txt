- MD3View v1.63

Quake III MD3/MDRmodel viewer and MD3/GLM exporter. Provides a way to visualize model files and export them to different formats from some id Tech 3 games.

- Features:

Visualize MD3/MDR files.
Export as MD3 from MDR.
Export as GLM from MD3 or MDR.
Multiple view models; wireframe, flat, textured, shaded, LOD, Picmic.
Advanced animation visualization.

- Installation

Create a new directory anywhere, this will be your working directory. Then another directory inside called "base".
Extract the contents of all asset bundles into that "base" directory; "assets0.pk3", "assets1.pk3", and so on, in ascending order, replacing anything when asked for.
Drop "MD3View.exe" into your working directory.
You now should have something like this:

├── My Work  Directory
│   ├── MD3View.exe
│   ├── base
│   │   ├── botfiles
│   │   ├── botroutes
│   │   ├── cfg
│   │   ├── ...

- Copyright

Copyright (C) 2010-2011 Matthew Baranowski, Sander van Rossen & Raven Software.
Licensed under GPLv2, see LICENSE.MD for details.

- Changelog

1.6  Original release
1.61 Skewing-free GLM export fix by Mr. Wonko
1.62 Fixed bounding box for animated models and added option for display of vertex normals by Archangel
1.63 Added ID_VIEW_VERTEXNORMALS to Dutch Accelerator and loading models that exceed legacy Q3 vertex limits by Archangel