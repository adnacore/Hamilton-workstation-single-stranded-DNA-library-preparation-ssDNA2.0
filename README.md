\# Hamilton-workstation-single-stranded-DNA-library-preparation-ssDNA2.0


Electronic protocol files (Hamilton NGS STAR worrkstation) for ssDNA2.0 library preparation method (Gansauge et al. 2020).


\## About



This repository contains the electronic protocol files for the ssDNA2.0 single-stranded library preparation method (Gansauge et al. 2017, Gansauge et al. 2020) for automated liquid handling on the Hamilton STAR system with a custom deck layout. The method was developed primarily for ancient DNA research but is also suitable for library preparation from other sources of degraded or single-stranded DNA, such as cell-free DNA, formalin-fixed samples or synthetic oligonucleotides. 


It provides the following 2 electronic protocols:


&#x20;\* library preparation, with or without Uracil-DNA-glycosylase treatment 

&#x20;\* library quantification by quantitative real-time PCR. 


\## Requirements


To use the protocol, a Hamilton NGS STAR system with a custom deck layout is required. Calibration of the instrument for this protocol has to be performed by the user and requires significant expertise in using the platform. 


\## Implementation and Documentation

&#x20;\* Use Hamilton Method Editor to import package file: method, device file, sub-methods, files and liquid classes.
(Import Mode: Recovery.)
&#x20;\* Supplementary protocols for qPCR setup (MPI_EVA_qPCRSetup.pkg) can be imported the same way as MPI_ssDNA_LibraryPreparation.pkg.
&#x20;\* Lid for Trough_V1.0.zip needs to be installed prior to application. It is recommended to use trough lids but they are optional by setting a specific boolean in the methods.
&#x20;\* MailAlert.zip can be installed to enable the system to send Mails for errors or other notifications.
&#x20;\* NGSStarInputFiles and NGSStarOutputFiles folders has to be save directly in C:\ Directory. 
&#x20;\* CyotmatFile need to be installed prior to application. It is recommended to use Cytomat as Tips storage, but it is optional by user selection.


\## References

>Sarah Nagel, Anna Schmidt, Ayinuer Aximu Petri, Anya Patova, Merlin Szymanski, Elena Essel, Matthias Meyer 2026. Bravo workstation: automated single-stranded DNA library preparation (ssDNA2.0). protocols.io
https://dx.doi.org/10.17504/protocols.io.kqdg32bdpv25/v2
Version created by Ancient DNA Core Unit


>Gansauge, Marie-Theres, Tobias Gerber, Isabelle Glocke, \*et al.\*, \*\*Single-stranded DNA library preparation from highly degraded DNA using T4 DNA ligase\*\*, \_Nucleic Acids Research\_, Volume 45, (2017). \[https://doi.org/10.1093/nar/gkx033](https://doi.org/10.1093/nar/gkx033)


>Gansauge, Marie-Theres, Ayinuer Aximu-Petri, Sarah Nagel \*et al.\* \*\*Manual and automated preparation of single-stranded DNA libraries for the sequencing of DNA from ancient biological remains and other sources of highly degraded DNA.\*\* \*Nature Protocols\*, Volume 15, (2020). \[https://doi.org/10.1038/s41596-020-0338-0](https://doi.org/10.1038/s41596-020-0338-0)

