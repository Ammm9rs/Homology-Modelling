# Homology-Modelling
This project provides a comprehensive computational analysis of the Human  β β 2-Adrenergic Receptor (ADRB2), a critical G protein-coupled receptor (GPCR). The study utilizes homology modeling to predict the 3D structure of the wild-type protein and evaluates the structural and energetic impacts of specific point mutations.

🧬 Project Overview
Target Protein: Human 
β2-Adrenergic Receptor (UniProt: P07550).
Methodology: Homology (Comparative) Modeling via MODELLER.
Primary Template: PDB ID 9L8L (Resolution: 3.22 Å, 100% Query Coverage).
Mutations Analyzed: P288S (CWxP motif) and P323T (NPxxY motif) — transitioning from rigid cyclic Prolines to flexible polar residues.

🛠️ Workflow & Tools
Template Identification: Sequence alignment and similarity search using NCBI BLASTp against the Protein Data Bank (PDB).
Structural Modeling: Generation of multiple 3D models for both Wild-Type (WT) and Mutant (MT) sequences using MODELLER logic.
Model Evaluation: Thermodynamic stability assessment using DOPE (Discrete Optimized Protein Energy) and MOLPDF scores.
Visualization: Structural analysis using UCSF Chimera, including hydrophobicity surface mapping and orthosteric binding pocket representation.
Comparative Analysis: Superimposition of models to calculate RMSD (Root Mean Square Deviation) and per-residue energy profiles.

📊 Key Results
Structural Stability: The Wild-Type model exhibited higher thermodynamic stability (lower DOPE scores) compared to the Mutant.
RMSD Analysis: A calculated RMSD of 0.564 Å indicates that the overall 7-transmembrane architecture remains intact, though local perturbations occur at the mutation sites.
Biochemical Insight: Replacing conserved Proline "helix-breakers" with polar residues likely disrupts functional kinks in TM6 and TM7, potentially destabilizing the receptor's active signaling state.

💻 Tech Stack
NCBI BLASTp (Sequence Alignment)
MODELLER (Homology Modeling)
UCSF Chimera (Molecular Visualization & Superimposition)
Gnuplot/Matplotlib (Energy Profile Plotting)
