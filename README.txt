======================================
POPULATION COUNTER GENERATOR FOR FPGAS 
======================================

Release date: June 27th, 2011


Description
-----------

FPGA_MaxPars_Gen is part of a package called FPGA_MaxPars that provides an 
open-source VHDL implementation of a reconfigurable architecture for the 
phylogenetic parsimony kernel.
The software tool FPGA_MaxPars_Gen allows for easy expansion of the size of the architecture in terms of parallel processing
units. 
Furthermore, it can also generate a population counter with user-defined size and latency in VHDL.

Additional infromation for the FGA_MaxPars_Gen software and the population counter component can be found in:

N. Alachiotis, A. Stamatakis: "FPGA Acceleration of the Phylogenetic Parsimony Kernel?", FPL 2011, Chania, Greece, September 2011.



Verification Details
--------------------

The development board HTG-V5-PCIE by HiTech Global populated with a V5SX95T-1 FPGA was used to verify the correct behavior of the population counter. 



Authors and Contact Details 
---------------------------

Nikos Alachiotis			n.alachiotis@gmail.com
Alexandros Stamatakis			alexandros.stamatakis@h-its.org


Scientific Computing Group (Exelixis Lab)
Heidelberg Institute for Theoretical Studies (HITS gGmbH)

Schloss-Wolfsbrunnenweg 35
D-69118 Heidelberg
Germany


Copyright 
---------

This component is free. In case you use it for any purpose, particularly 
when publishing work relying on this component you must cite it as: 

N. Alachiotis, A. Stamatakis: "FPGA Acceleration of the Phylogenetic Parsimony Kernel?", FPL 2011, Chania, Greece, September 2011.

You can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation; either version 2 of the License, or
(at your option) any later version.

This component is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.


The population counter (POPCOUNT.vhd) generated by FPGA_MaxPars_Gen can be used under the GNU LGPL license.


Release Notes
-------------

Release date: June 27th, 2011
