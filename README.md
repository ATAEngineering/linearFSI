# Linear FSI Module
This module was developed by [ATA Engineering](http://www.ata-e.com) as an 
add-on to the Loci/CHEM computational fluid dynamics (CFD) solver. The module 
can be used to couple Loci/CHEM to a linear finite element model (FEM). The
user must supply the mass and stiffness matrices for the FEM. These can 
typically be exported from a FEM tool like NASTRAN or Abaqus. Mechanical 
coupling is supported between Loci/CHEM and the FEM. The FEM will provide
Loci/CHEM with a displacement on the interface boundary, which Loci/CHEM will
use to calculate aerodynamic loads to provide to the FEM. An internal mapping
algorithm is used to map data between the Loci/CHEM and FEM meshes.

# Dependencies
This module depends on both Loci and CHEM being installed. Loci is an open
source framework developed at Mississippi State University (MSU) by Dr. Ed 
Luke. The framework provides a rule-based programming model and can take 
advantage of massively parallel high performance computing systems. CHEM is a 
full featured open source CFD code with finite-rate chemistry built on the Loci 
framework. CHEM is export controlled under the International Traffic In Arms 
Regulations (ITAR). Both Loci and CHEM can be obtained from the 
[SimSys Software Forum](http://www.simcenter.msstate.edu) hosted by MSU.

# Obtaining The Module
The source code for the module is freely available to a restricted set of users.
For more information and to request a copy please contact mnucci@ata-e.com.