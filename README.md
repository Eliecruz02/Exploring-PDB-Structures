# PDB Structure Explorer

## Overview

This project uses Python and Biopython to explore how an experimentally determined protein structure is organized inside a Protein Data Bank coordinate file.

The structure examined is **3HS4**, human carbonic anhydrase II in complex with the inhibitor acetazolamide.

The project focuses on identifying and distinguishing:

- Standard protein residues
- Water molecules
- Small-molecule ligands
- Metal ions
- Crystallization additives
- Individual atoms and their three-dimensional coordinates

## Question

How can Python distinguish the protein, ligand, catalytic metal ion, water molecules, additives, residues, and atoms present in a PDB structure?

## Structure analyzed

- **PDB ID:** 3HS4
- **Protein:** Human carbonic anhydrase II
- **Inhibitor:** Acetazolamide
- **Acetazolamide PDB identifier:** `AZM`
- **Catalytic metal:** Zinc
- **Experimental method:** X-ray diffraction
- **Resolution:** 1.10 Å
- **Main protein chain:** Chain A

## Objectives

This project was designed to:

1. Download a real experimental structure from the RCSB Protein Data Bank.
2. Verify the identity and integrity of the downloaded coordinate file.
3. Parse the structure using Biopython.
4. Navigate the Structure, Model, Chain, Residue, and Atom hierarchy.
5. Separate standard protein residues from waters and nonstandard components.
6. Identify acetazolamide, zinc, glycerol, and other modeled components.
7. Inspect atom names, chemical elements, parent residues, and coordinates.
8. Calculate simple atom-to-atom distances.
9. Compare each acetazolamide copy with the catalytic zinc atom.
10. Identify the acetazolamide copy most closely associated with the
    zinc-containing active site.
11. Create structure-composition tables and figures.
12. Save and validate the generated outputs.

## Data Source and reference

Structure 3HS4 was obtained from the RCSB Protein Data Bank.

Primary structural study:

Sippel KH, Robbins AH, Domsic J, Genis C, Agbandje-McKenna M, McKenna R. High-resolution structure of human carbonic anhydrase II complexed with acetazolamide reveals insights into inhibitor drug design. Acta Crystallographica Section F. 2009;65:992-995. DOI: 10.1107/S1744309109036665