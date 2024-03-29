**﻿ABOUT THE DATASET**

- The MAGIC gamma telescope dataset was created to simulate the registration of high energy gamma particles in a ground-based atmospheric Cherenkov gamma telescope using an imaging technique that allows for statistical discrimination of primary gamma information (signal) from images of hadronic showers initiated by cosmic rays in the upper atmosphere (background).
- The dataset consists of two classes:
  **gammas (signal)** and **hadrons (background)**.

**COLUMNS INFO**

The dataset consists of 10 **continuous** features and **1 binary class label**. The features are listed below:
- fLength: major axis of ellipse [mm]
- fWidth: minor axis of ellipse [mm]
- fSize: 10-log of sum of content of all pixels [in #phot]
- fConc: ratio of sum of two highest pixels over fSize [ratio]
- fConc1: ratio of highest pixel over fSize [ratio]
- fAsym: distance from highest pixel to center, projected onto major axis [mm]
- fM3Long: 3rd root of third moment along major axis [mm]
- fM3Trans: 3rd root of third moment along minor axis [mm]
- fAlpha: angle of major axis with vector to origin [deg]
- fDist: distance from origin to center of ellipse [mm]
- class: g (OR) h
