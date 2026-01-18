S10_Wing: original FEM provided by Technion for the Pazy wing with 10-deg sweep
S10_Wing_Stiffened: same as above but modified for rigid tip

S20_Wing: original FEM provided by Technion for the Pazy wing with 20-deg sweep
S20_Wing_Stiffened: same as above but modified for rigid tip

frequencies_S10_wing: comparison of frequencies with original and stiffened wingtip for 10-deg sweep
frequencies_S20_wing: comparison of frequencies with original and stiffened wingtip for 20-deg sweep

Note: the stiffening of the wingtip is required to comply with beam assumptions. Another way to do this
would be to detach the tip rod and do the stiffness condensation without that, and then add it back for
the mass condensation as a rigid-body with a moment of inertia, but this would be more tedious. The two
approaches probably give similar or the same results. Obviously, this modification alters the frequency
of the modes that involve significant tip rod deformations, but these cannot be captured by beam models
anyway. The impact is relatively small for bending-dominated modes. 