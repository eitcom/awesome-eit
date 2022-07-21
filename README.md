# Awesome EIT (Electrical Impedance Tomography)

This repository tracks some awesome EIT (Electrical Impedance Tomography) libraries and applications.

If you find some links that may be interesting or related to EIT, please **fork this project and commit a PR!**

## Contents

  - [EIT simulation libraries](#eit-simulation-libraries)
  - [EIT Hardwares](#eit-hardwares)
  - [EIT Imaging Algorithms](#eit-imaging-algorithms)
  - [Modeling and Meshes](#modeling-and-meshes)
  - [Visualization](#visualization)
  - [Fantastic Applications](#fantastic-applications)
  - [Community](#community)

## EIT simulation libraries

The simulation library means that a standalone toolkit for EIT simulation, algorithm, and data pre- and post- processing. This section includes both EIT and MIT.

  - [pyEIT](https://github.com/liubenyuan/pyEIT). pyEIT is a python-based, open-source framework for Electrical Impedance Tomography (EIT). From **pyeit**.
  - [CEIT](https://github.com/zehao99/CEIT). Python Package for EIT(Electric Impedance Tomography)-like method on detecting capacitance Density Distribution.
  - [EITPipelineExample](https://github.com/EIT-team/EITPipelineExample). Making EIT images. How to go from Geometry -> Mesh -> Forward -> Inverse -> EIT image. From **EIT-team**.
  - [MIT_Forward](https://github.com/rosskynch/MIT_Forward). An MIT Forward Solver. This code is provided to solve the eddy current approximation of the time-harmonic Maxwell equations. *Note: This is by far the only open sourced MIT forward simulation toolkit on github.*

Not actively developed,
  - [rahul-sb/EIT](https://github.com/rahul-sb/EIT). *Note: last update 2019.*
  - [Forgotten/EIT](https://github.com/Forgotten/EIT). Solving EIT via PDE constrained optimization. *Note: unkown status, need tracking.*

## EIT Hardwares

Some open source (or partial OSS) EIT hardwares:
  - [ScouseTom](https://github.com/EIT-team/ScouseTom). From **EIT-team**.
  - [OpenEIT/EIT_EE](https://github.com/OpenEIT/EIT_EE). From **OpenEIT**.
  - [aorbe/eit](https://github.com/aorbe/eit). *Note: last update 2020.*
  - [EIT-kit_open-source](https://github.com/HCIELab/EIT-kit_open-source).

## EIT Imaging Algorithms

  - [pydbar](https://github.com/NablaIP/pydbar). A dbar based algorithm for Electrical Impedance Tomography.
  - [DeepDbar](https://github.com/asHauptmann/DeepDbar). This repository will collect codes accompanying the publication: Hamilton & Hauptmann (2018). Deep D-bar: Real time Electrical Impedance Tomography Imaging with Deep Neural Networks. IEEE Transactions on Medical Imaging. *Note: last update 2019.*

## Modeling and Meshes

There are variaty of meshing utilities, you may refer to the [community](#community) section for more details. This section, adds only the meshes related to EIT imaging, that has or will be using in this community.

  - [eitmesh](https://github.com/liubenyuan/eitmesh). Models and Meshes for pyEIT. From **pyeit**.
  - [openSAHE](https://github.com/fsmMLK/openSAHE). Open Source Statistical Anatomical Atlas of the Human head for Electrophysiology Applications. *Note: a great library for head EIT simulation! Tracking and reproduce it.*
  - [nyhead](https://www.parralab.org/nyhead/). The New York Head. *Note: This is not hosted on github, though it might be important to brain EIT researches.*
  - [Mesher](https://github.com/EIT-team/Mesher). EIT-MESHER is C++ software, based on the CGAL library, which generates high quality Finite Element Model tetrahedral meshes from binary masks of 3D volume segmentations. From **EIT-team**.
  - [tetrahedralizer](https://github.com/ABI-EIT/tetrahedralizer). Tetrahedralizer is an app and python library for automating the process of converting surface meshes to volumetric meshes.

Generalized Mesh libraries,
  - [pygalmesh](https://github.com/meshpro/pygalmesh). pygalmesh is a Python frontend to CGAL's 2D and 3D mesh generation capabilities. From **meshpro**.
  - [pygmsh](https://github.com/meshpro/pygmsh). pygmsh combines the power of Gmsh with the versatility of Python. From **meshpro**.
  - [polyfem](https://github.com/polyfem/polyfem). A polyvalent C++ FEM library.
  - [polyscope](https://github.com/nmwsharp/polyscope). Polyscope is a C++/Python viewer and user interface for 3D data such as meshes and point clouds.

Forward (FEM) simulation,
  - [scikit-fem](https://github.com/kinnala/scikit-fem). scikit-fem is a pure Python 3.7+ library for performing finite element assembly. Its main purpose is the transformation of bilinear forms into sparse matrices and linear forms into vectors.
  - [ngsolve](https://github.com/NGSolve/ngsolve). see ngsolve.org.

## Visualization

  - [Datoviz](https://github.com/datoviz/datoviz). GPU interactive scientific data visualization with Vulkan
  - [vedo](https://github.com/marcomusy/vedo). A lightweight and powerful python module for scientific analysis and visualization of 3d objects.

## Fantastic Applications

EIT/MIT applications, and datasets.

  - [pyeit-apps](https://github.com/liubenyuan/pyeit-apps). pyeit-apps hosts the reproducible codes and data (small sized, for illustration purpose only). From **pyeit**.
  - [EIT-MPhys-Project](https://github.com/ivo53/EIT-MPhys-Project). This project presents a novel Electrode Selection Algorithm (ESA) for use in Electrical Impedance Tomography (EIT) on 2-dimensional samples.
  - [Stroke_EIT_Dataset](https://github.com/EIT-team/Stroke_EIT_Dataset). This Multifrequency Electrical Impedance Tomography (EIT) data was collected as part of clinical trial in collaboration with the Hyper Acute Stroke unit (HASU) at University College London Hospital (UCLH). From **EIT-team**.
  - [OpenEIT](https://github.com/OpenEIT/OpenEIT). Python based dashboard for real-time Electrical Impedance Tomography including image reconstruction using Back Projection, Graz Consensus and Gauss Newton methods.
  - [ML-EIT-Graphene](https://github.com/AdamCoxson/ML-EIT-Graphene).
  - [EIT-kit](https://dl.acm.org/doi/fullHtml/10.1145/3472749.3474758). An Electrical Impedance Tomography Toolkit for Health and Motion Sensing.

## Community

  - [awesome-geometry-processing](https://github.com/zishun/awesome-geometry-processing): Libraries for Geometry Processing
  - [awesome-medical-imaging](https://github.com/fepegar/awesome-medical-imaging): Awesome medical imaging
  - [awesome-scientific-computing](https://github.com/nschloe/awesome-scientific-computing): Awesome Scientific Computing, Useful resources for scientific computing and numerical analysis.
