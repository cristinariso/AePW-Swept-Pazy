# AePW Swept Pazy wing benchmark case

Models and properties for the Pazy wing benchmark case with 10-deg and 20-deg sweep.

## Content 

Folders:

  * `00_FEM`: Pazy wing MSC Nastran GFEM (original and with stiffened wingtip)
  * `01_ReferenceAxis`: Reference axis grid coordinates (MSC Nastran default reference frame)  
  * `02_BeamMassModel`: Beam mass model for selected reference axis (MSC Nastran default reference frame)
  
Notes:

  * The inertia tensors for the beam nodes list the xx, yy, and zz diagonal elements first, followed by the xy, xz, and yz off-diagonal elements (with sign embedded, hence the listed numbers are directly the inertia tensor entries)

## Contact

Cristina Riso (criso@gatech.edu)
