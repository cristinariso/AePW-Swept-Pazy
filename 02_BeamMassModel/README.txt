Format of output files for masses:

node number, mass value (kg)


Format of output files for mass offsets:

node number, x coordinate (m), y coordinate (m), z coordinate (m)

Coordinates are in the MSC Nastran default reference frame and relative to the beam node coordinates


Format of output files for inertia tensors:

node number, xx component (kg m2), yy component (kg m2), zz component (kg m2), xy component (kg m2), xz component (kg m2), yz component (kg m2)

Components are in the MSC Nastran default reference frame and related to the centers of mass for each beam node 

Components are taken straight from the inertia tensors and so any sign is embedded (note to self: double check this)