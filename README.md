# ArtiScales.github.io
The spatial simulation platform ArtiScales supports the integration of regional and local planning policies that aim to control residential development. It integrates two models: [MUP-City](https://sourcesup.renater.fr/mupcity/en.html) and [SimPLU3D](https://simplu3d.github.io/).

MUP-City simulates scenarios of residential development for an entire urban region given a set of planning rules. The first rule ensures that the pattern of cells worth urbanising is fractal. The other planning rules take account of the proximity of roads, accessibility of shops and services, accessibility to public transport, proximity of open spaces, and the presence of areas that cannot be built on. The identification of cells worth urbanising takes the form of a raster map of potential building cells, each characterised by the worth of urbanising them. How worthwhile it is for a cell to be urbanised ranges from zero to one.

SimPLU3D simulates the potential building possibilities in a cluster of houses (*i. e.* a land parcel or a group of parcels) by generating 3D buildings configurations that respect the constraints of the local urban masterplan (in French, *Plan Local d'Urbanisme - PLU*).

**Example of simulation result**
![Example of simulation result](ArtiScalesExampleSimulationResults.png)
