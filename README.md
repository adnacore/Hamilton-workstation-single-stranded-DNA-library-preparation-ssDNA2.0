# Hamilton Workstation Single-Stranded DNA Library Preparation (ssDNA2.0)

Electronic protocol files for the Hamilton NGS STAR system (custom deck layout) implementing the ssDNA2.0 single-stranded library preparation method (Gansauge et al. 2020).

## About

This repository contains the electronic protocol files for the ssDNA2.0 single-stranded library preparation method (Gansauge et al. 2017; Gansauge et al. 2020) for automated liquid handling on the Hamilton STAR system with a custom deck layout. The method was developed primarily for ancient DNA research but is also suitable for library preparation from other sources of degraded or single-stranded DNA, such as cell-free DNA, formalin-fixed samples, or synthetic oligonucleotides.

It provides two electronic protocols:

- Library preparation, with or without Uracil-DNA-glycosylase (UDG) treatment
- Library quantification by quantitative real-time PCR (qPCR)

## Requirements

Use of this protocol requires a Hamilton NGS STAR system with a custom deck layout. Calibration of the instrument for this protocol must be performed by the user and requires significant expertise with the platform.

## Implementation and Documentation

- Use the Hamilton Method Editor to import the package file (method, device file, sub-methods, and associated files) and liquid classes. Import mode: **Recovery**.
- The supplementary qPCR setup protocol (`MPI_EVA_qPCRSetup.pkg`) can be imported the same way as `MPI_ssDNA_LibraryPreparation.pkg`.
- The trough lid (`Lid for Trough_V1.0.zip`) must be installed prior to use. Use of trough lids is recommended but optional, and can be enabled or disabled via a boolean setting in the methods.
- `MailAlert.zip` can optionally be installed to enable the system to send email notifications for errors or other events.
- The `NGSStarInputFiles` and `NGSStarOutputFiles` folders must be saved directly under the `C:\` directory.
- The Cytomat file must be installed prior to use. Use of the Cytomat as tip storage is recommended but optional, depending on user selection.

## References

Nagel, Sarah, Anna Schmidt, Ayinuer Aximu-Petri, Anya Patova, Merlin Szymanski, Elena Essel, Matthias Meyer. 2026. *Bravo workstation: automated single-stranded DNA library preparation (ssDNA2.0)*. protocols.io. https://dx.doi.org/10.17504/protocols.io.kqdg32bdpv25/v2 (version created by the Ancient DNA Core Unit)

Gansauge, Marie-Theres, Tobias Gerber, Isabelle Glocke, et al. 2017. **Single-stranded DNA library preparation from highly degraded DNA using T4 DNA ligase.** *Nucleic Acids Research*, Volume 45. https://doi.org/10.1093/nar/gkx033

Gansauge, Marie-Theres, Ayinuer Aximu-Petri, Sarah Nagel, et al. 2020. **Manual and automated preparation of single-stranded DNA libraries for the sequencing of DNA from ancient biological remains and other sources of highly degraded DNA.** *Nature Protocols*, Volume 15. https://doi.org/10.1038/s41596-020-0338-0
