# Workshop: Analyzing 3D PDB structures.

## Description
- Complex analysis of PDB structures
- Duration: 90 minutes
- Objectives: be able to 
    - use Pymol and UCSF Chimera programs for analysis
    - do analysis in Python using MDanalysis and Prody libraries
    - select, extract and analyze atom coordinates and dihedral angles.
    - add hydrogens to the structure
    - identify hydrogen bonds
    - identify protonation states
    - assign charges to the atoms
    - compute and analyze electrostatic surface
    - build contact maps
    - identify domains
    - find homologous structures
    - make structural alignment, compute RMSD
    - generate sequence alignment from structural alignment
    - identify residue conservation
    - analyze dynamics using elastic networks models

## Jupyter notebook
- [3Dstruct_analysis.ipynb](3Dstruct_analysis.ipynb)
## Required software and resources
- Pymol, [installation instructions](https://github.com/intbio/mol_model_course/blob/main/workshops/pymol/installation.md)
- UCSF Chimera (optional)
- VMD [installation link](https://www.ks.uiuc.edu/Development/Download/download.cgi?PackageName=VMD) 
- Access to a Jupyter notebook evironment with Python 3
- 3-button mouse

**List of Conda packages:**
- MDanalysis 
- nglview  
- prody 
- propka or use https://www.ddl.unimi.it/vegaol/propka.htm 
- pdb2pqr or use https://server.poissonboltzmann.org/pdb2pqr 

**Channels list (if you use Anaconda Navigator):**
- conda-forge
- schrodinger 

## Learning resources
- MDanalysis tutorial [https://www.mdanalysis.org/MDAnalysisTutorial/](https://www.mdanalysis.org/MDAnalysisTutorial/)
- Prody tutorial [http://prody.csb.pitt.edu/tutorials/prody_tutorial/](http://prody.csb.pitt.edu/tutorials/prody_tutorial/)
- APBS documentation [https://apbs.readthedocs.io/en/latest/](https://apbs.readthedocs.io/en/latest/)


## Assignments

A  PDB structure of a protein with at least two domains  will be suggested for analysis.
The assignment report should include section detailing the following:

1. Protein dihedral angle analysis
2. Contact maps
3. Identify domains
4. Find homologous structural domains, compute RMSD
5. Identify protonation states of ionizable residues 
6. Surface analysis
    - identify polar, charge, hydrophopic residues on the surface
    - visualize electorstatic potential at the surface using PDB2PQR and APBS
7. Dynamics analysis
8. Conservation analysis

### Suggested problem sets
Each student should take a unique PDB structure with at least two domains from the PDB web-site at his/her own discretion.

### Troubleshooting
- Consult with the seminar protocol/recording
- Try to Google, and see Pymol Wiki
- Ask questions in TG
