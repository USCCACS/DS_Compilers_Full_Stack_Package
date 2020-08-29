# DS_Compilers_Full_Stack_Package
Domain-specific compilers for IBM and Rigetti wrapped into a full-stack quantum simulation software package

To aid future researchers in benefiting from our domain-specific (DS) compilers, we have integrated them into the full stack quantum simulation software package provided in this repo.  This package provides the capability to i) generate circuits for the transverse-field Ising model (TFIM) simulations of interest in this article; ii) apply the DS compilers to these high-level circuits to generate hardware-executable circuits on either the Rigetti or IBM quantum processors; iii) execute the circuits on the Rigetti or IBM quantum processors; and iv) provide limited post-processing and plotting of results.  

If the user is solely interested in studying the performance of our DS compilers on their own TFIM circuits, they may also elect to bypass circuit generation and execution and have the software simply return the DS-compiled circuit.   The two provided tutorials provide demonstrations of how to carry out each use case within this software packge.
