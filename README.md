# PhotonLabeler
**Version 2.0**

Software for visual interpretation and labeling of ICESat-2 Geolocated Photon data (ATL03)
<img width="1020" alt="PhotonLabeler UI" src="https://user-images.githubusercontent.com/57913239/233867360-8e42d7a4-3512-410e-845f-45323d601999.PNG">

**_PhotonLabeler_** is a free graphic user interface (GUI) for visualization and manual labeling of ICESat-2 Geolocated Photon data (ATL03) through visual interpretation. The software is developed with MATLAB AppDesigner (MATLAB R2020a +) and uses MATLAB functions to read and plot ATL03 Hierarchical Data Format (HDF) files. To support manual labeling of points, the software provides the following:
1) Definition of different point classes i.e. a user can specify the name, code and color of a defined point class
2) Point selections tools (rectangle, polygon or polyline-based selection)
3) Geo-linking to high-resolution web maps to provide ancillary information during visual interpretation
4) Saving and loading of a labeling session i.e. a can saved a session and load it to continue the labeling task.
5) Saving of plot graphics to include in documents or presentations

**Main updates in v2.0**

1)	New User Interface - All tools organized in one panel (left) for easier tool selection 
2)  The Create New Session Dialog has been split to enable independent loading of ATL03 data and setting of session parameters  
3)	Added capability to link ATL08 photon class values   to speed-up creating of labeled data
4)	Added capability to add trackmarks for quick navigation to section of interest along a track
5)	Added option to render point cloud by signal confidence and plot calculated ATL08 terrain canopy height values
6)	Point selection tools are now state (on/off) buttons. Click to start and click to stop the tool. 
7)	Added button to enable skipping to beginning or end of track

<a href = https://github.com/Oht0nger/PhoLabeler/releases/tag/v2.0>Download the version 2.0 and user manual</a>

<a href = https://github.com/Oht0nger/PhoLabeler/releases/tag/v1.0>Download the version 1.0 and user manual</a>

---
**Installing PhotonLabeler**

**_PhotonLabeler_** is available as a compiled MATLAB binary which can be installed as a stand-alone software without a MATLAB license. The software does require MATLAB Runtime (free, 1.5Gb+) though, which can be downloaded and installed prior or during the installation of the software. For best performance, we recommend installing the software on a systems with 8 Gb + RAM with any Intel or AMD x86-64 processor with four logical cores or more. Further details on how to use the software are available in the user manual( See download files)

---
**Software citation**

Malambo, L., & Popescu, S. (2020). PhotonLabeler: An Inter-Disciplinary Platform for Visual Interpretation and Labeling of ICESat-2 Geolocated Photon Data. Remote Sensing, 12(19), 3168. https://doi.org/10.3390/rs12193168

---
## License & copyright

© Lonesome Malambo, LASERS Lab Texas A&M Univerisity
