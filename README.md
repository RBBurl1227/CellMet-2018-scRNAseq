# CellMet-2018-scRNAseq
Analysis of single-cell RNA-sequencing data described in the paper titled, "Deconstructing adipogenesis induced by beta3-adrenergic receptor activation with single cell expression profiling", published by Burl et al. in Cell Metabolism, 2018.
Data can be found at the Sequence Read Archive, https://www.ncbi.nlm.nih.gov/sra/, Accession Number: SRP145475. 

For this set of experiments, we created single-cell RNA-seq libraries from two mouse adipose tissue depots (epididymal white adipose tissue [eWAT; also denoted gWAT in the code] and inguinal white adipose tissue [iWAT]), with or without a 3 day treatment with the beta3 adrenergic receptor agonist CL 316,243 (CL; treatment type designated by "sham control" or "CL treatmnet"). Cells from these two depots and treatment types were also separated into two cell fractions by magnetic cell separation using Miltenyi Biotec columns and beads. 

(6) single-cell RNA-seq libraries were made from libraries as follows:

(6) C57BL/6j mice ->         sham surgery for control 		 -> after (3) days, collect eWAT and iWAT from all animals; pool tissues by type and create a single cell suspension -> fraction cells into immune (Lineage positive) and non-immune (Lineage negative) cell types using magnetic bead cell separation -> create single-cell libraries using the 10X Genomics system from each fraction and tissue type, ending with (3) libraries: eWAT Lineage positive, eWAT Lineage negitive; and iWAT Lineage negative
(6) C57BL/6j mice -> CL micropump implanted subcutaneously -> after (3) days, collect eWAT and iWAT from all animals; pool tissues by type and create a single cell suspension -> fraction cells into immune (Lineage positive) and non-immune (Lineage negative) cell types using magnetic bead cell separation -> create single-cell libraries using the 10X Genomics system from each fraction and tissue type, ending with (3) libraries: eWAT Lineage positive, eWAT Lineage negitive; and iWAT Lineage negative

The (6) single-cell libraries were multiplexed as indicated below and sequenced on the Illumina NextSeq500 usign high output 75-cycle kits with the following read length configuration: 26 bp read1, 14bp I7index, 8bp I5 index and 58 bp read2. 

