# pulp_soc

The `pulp_soc` repository contains the structure of the SoC microcontroller
subsystem used in PULPissimo (single-core) and PULP (multi-core) chips.
For more details on the internal architecture, see the README.md in the
`pulpissimo` repository.

This version instantiates the CV32E40P core instead of RI5CY, and should replace
the version that is installed with pulpissimo by copying to:
    $PULPISSIMO/ips/pulp_soc
    
The source file that instantiates CV32E40P is:
    $PULPISSIMO/ips/pulp_soc/rtl/fc/fc_subsystem.sv
    
(all other source files in this project are unchanged)
