![gridion](pictures/gridionx5.png)
# GridION_yeast_cDNA-seq
## Aim

Produce full-length cDNA reads from a common yeast (S288c) sample and sequence them using a GridION flow-cell. Perform standard QC on the obtained reads and use them to perform a transcriptome analysis using popular tools. This work aims at evaluating wether ONT transcriptome data is sufficient (quantity and quality) to perform transcript analysis and potentially differential expression analysis.

## Sample prep & RNA QC

TBD

## Library prep & QC

Due to the high demand in purified polyA+ input material not being compatible with our yeast sample size, we decided to use the **'TeloPrime Full-Length cDNA Amplification Kit V2'** ([link](https://www.lexogen.com/wp-content/uploads/2018/12/013UG022V0200_TeloPrime-V2.pdf)) starting from total RNA. This kit processes total RNA by first creating a first stand cDNA primed with an oligo-dT containing custom primer followed by CAP-specific second strand synthesis and limited PCR amplification of the obtained 'full-length' cDNA ([full workflow](https://www.lexogen.com/teloprime-workflow/)).

The PCR primers included in all TeloPrime Kits V2 (Cat. No. 013, 018) have the following sequence:
* FP: 5’ – TGGATTGATATGTAATACGACTCACTATAG – 3‘
* RP: 5’ – TCTCAGGCGTTTTTTTTTTTTTTTTTT – 3‘

