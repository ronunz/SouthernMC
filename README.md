# SouthernMC
Southern Monte Carlo - A health physics monte carlo toolkit

## Prerequisites for development
- Cmake 3.16 or higher - For building Geant and developed simulation
- C++17 Standard (or higher) Compiler - Builds use the C++ compiler, but can also be used for actual development if desired. Visual Studio suggested for Windows installations. 
- Geant4 V. 11.3.2 or newer - Geant4 source code. Should be downloaded and built, including data sets. See [Geant installation documentation](https://geant4-userdoc.web.cern.ch/UsersGuides/InstallationGuide/html/index.html).
- Root V. 6.32.12 or newer - Not necessary for executing Geant simulations, but should be included so components of the root libraries used in the simulation for output of data into TTree objects. Also used for post-simulation analysis and data visualization. 
