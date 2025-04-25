# Interface Analysis

Through analysis with Rosetta interface analyzer, PDBePISA, and PDBsum, the hotspot regions on chain A were identified as shown below:

![Hotspot region](https://github.com/LIJIAWEI040301/De-Novo-Design-of-Miniprotein-Binders-for-the-Plant-Pathogen-Effector-AVR-Pia/blob/main/ia.png)

Structural analysis revealed that the hotspot residues are concentrated in an α-helix region and a loop region (203-226).

---

**Supplement:**

Pitfall: It was found that selecting based on the number and types of bonds is not rigorous enough.  
A new approach was considered: using the breakdown function of interfaceanalyzer to examine pairwise data, ignoring direction, and summarizing the scores located on chain A. For positions without interactions, mark them as 0. Then, use a sliding window (try window sizes of 10–20) to calculate the minimum sum of values within the window. Finally, combine this with clash and other data to select the optimal region.
