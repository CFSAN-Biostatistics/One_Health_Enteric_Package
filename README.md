# One Health Enteric Package

## One Health-compatible metadata package for genomic surveillance of enteric microbial organisms

The Genomics for Food Safety (GenFS) Metadata Workgroup is a cross-agency collaboration comprising members from the United States Department of Agriculture, Centers for Disease Control and Prevention, National Center for Biotechnology Information, and Food and Drug Administration. The primary goal of this workgroup is to expand and standardize the contextual data associated with samples collected for enteric surveillance and research in the United States, moving from a mostly free-text space to one that is machine-readable.

The workgroup leveraged two existing metadata packages, the NCBI standard microbial metadata package<sup>**1**</sup> and the draft MIxS Food Environmental Metadata Standard package<sup>**2**</sup>, to develop a new metadata package for genomic surveillance of enteric microbes. The new One Health Enteric Package captures the full One Health sample space for enteric microbes. The package comprises a core suite of attributes describing general sample and isolate features plus four sections covering the major One Health sample spaces:
1. human/animal hosts
2. food samples
3. food facilities
4. environmental samples (farm, water, and the environment)

Each of these sections contain a set of attributes with detailed definitions, guidance, and requirements. Most attributes require standardized input selected from controlled vocabularies or existing ontologies. Curated picklists provide the user easy access to standard terminology for populating the package. Each collaborating agency provided example use cases that new users can follow for different sample types. 
 
This effort resulted in a metadata package that will better meet our One Health goals by providing machine-readable contextual data, enabling more sophisticated data science analyses for investigating links between genomic data and contextual metadata, e.g. machine learning or population-adapted genome wide-association studies (GWAS) to test hypotheses around evolution of virulence, stress tolerance, antimicrobial resistance, risk assessment, and source attribution, among others.<br><br>


**The latest versions of the One Health Enteric Package can be found under Releases on the panel to the right.**
<br><br>
**A generic version of the template is also available in the NCBI BioSample Submission Portal:** https://submit.ncbi.nlm.nih.gov/biosample/template/.
<br><br>
**Any questions, suggestions or comments should be submitted to the issue page of this repository.**
<br><br>

<sup>**1**</sup>NCBI Resource Coordinators. Database resources of the National Center for Biotechnology Information. Nucleic Acids Res. 2015. 43(Database issue):D6-17. doi: 10.1093/nar/gku1130.

<sup>**2**</sup>Yilmaz _et al_. Minimum information about a marker gene sequence (MIMARKS) and minimum information about any (x) sequence (MIxS) specifications. Nat Biotechnol. 2011. 29(5):415-20. doi: 10.1038/nbt.1823.
<br><br>


[![CC BY 4.0][cc-by-shield]][cc-by]

This work is licensed under a
[Creative Commons Attribution 4.0 International License][cc-by].

[![CC BY 4.0][cc-by-image]][cc-by]

[cc-by]: http://creativecommons.org/licenses/by/4.0/
[cc-by-image]: https://i.creativecommons.org/l/by/4.0/88x31.png
[cc-by-shield]: https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg
