# Viral Dose-Dependent Inflammation and Capillary Stalling Following Bioluminescent Oxygen Reporter Expression in Mouse Cortex

Overview

This project investigates whether viral-vector-mediated expression of a bioluminescent oxygen reporter induces inflammation-associated vascular dysfunction and capillary stalling in the mouse cortex.

The primary objective is to determine whether the expression of the oxygen reporter is associated with localized tissue hypoxia and changes in cortical microvascular function, and whether these effects depend on viral vector type or viral dose.

Two complementary imaging approaches are used:

Bioluminescence imaging (BLI) to monitor cortical oxygen-dependent reporter activity.
Optical coherence tomography angiography (OCTA) to characterize cortical vascular structure and microvascular function, including capillary stalling.

The BLI data provided in this repository are processed data derived from the original BLI image recordings. The raw BLI image sequences are not included because of their large file size. For each experiment, the BLI recording consisted of approximately 1,200 consecutive image frames acquired during the oxygen challenge protocol. For each frame, the BLI signal was quantified by calculating the mean pixel intensity within the analyzed cranial imaging region. This produced one mean BLI intensity value for each frame and generated a time series of approximately 1,200 values for each recording. 
Relationship between raw and deposited data

Raw BLI image sequence
→ approximately 1,200 image frames per recording
→ mean BLI intensity calculated across the analyzed cranial imaging region for each frame
→ approximately 1,200 frame-by-frame values
→ stored as pixelVals in results.mat
→ subsequent analysis of oxygen-dependent BLI responses
