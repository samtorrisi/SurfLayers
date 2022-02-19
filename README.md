# SurfLayers
released in AFNI for laminar fMRI visualizations

These are scripts for a novel form of fMRI visualization. I wrote the core sections and then the project gradually became a collaboration with myself and most of the AFNI software development team as it was revised, improved, and expanded. AFNI is a still-popular, free, and open-source software suite and ecosystem for MRI and fMRI analysis that has existed for > 25 years. 

The scripts **SurfLayers** and **quickspecSL**, along with **clipping plane** functionality, allow for a novel form of data visualization within AFNI and its sister program SUMA, primarily for the subfield of "layer" or "laminar" fMRI. Interestingly, results can blur the line between traditional surface and voxel-level visualizations. The primary motivation was for interactive and flexible exploration of fMRI activations in areas of the cortex that have not been functionally well-characterized at the laminar level. The scripts build on already-existing AFNI, SUMA and FreeSurfer tools, but creates a novel link between them for layer fMRI data, which is currently mostly collected on the ~100 Ultra-High Field (>= 7 Tesla) MRI systems across the globe.

The open-source scripts were released within AFNI in 2021, but I include them separately here to not link to a forked repository of the entire AFNI suite. Use of them should be used within an updated AFNI download and pull-requests, comments, citations, etc should go through the standard AFNI open-source license channels described here https://github.com/afni/afni and here https://afni.nimh.nih.gov/pub/dist/doc/htmldoc/published/citations.html. General information about AFNI + SUMA can also be found at https://afni.nimh.nih.gov/ and about FreeSurfer at https://surfer.nmr.mgh.harvard.edu/. 

The publication for SurfLayers is currently an abstract for the 2021 Organization of Human Brain Mapping (OHBM) conference: 
**Creating Layered Surfaces to Visualize with AFNI + SUMA, with applications to laminar fMRI**
Salvatore Torrisi, Peter Lauren, Paul A Taylor, Suhyung Park, David Feinberg, Daniel Glen

This poster submission also included my **video demonstrations**:
https://www.youtube.com/watch?v=-lDOVDCuji0

This AFNI webpage links to the poster and also takes one through those demonstrations:
https://afni.nimh.nih.gov/pub/dist/doc/htmldoc/tutorials/surflayers/surflayers.html

That page also includes instructions to download my (1,109 lines of) demo "driving" scripts and associated example data via @Install_SURFLAYERS_DEMO1 so you can run them yourself.

Further features and refinements to this visualization process are described in the 2022 OHBM abstract:
**Using Clipping Planes to Analyze Brain Data in SUMA**
Peter Lauren, Daniel Glen, Richard Reynolds, Salvatore Torrisi, Paul Taylor
