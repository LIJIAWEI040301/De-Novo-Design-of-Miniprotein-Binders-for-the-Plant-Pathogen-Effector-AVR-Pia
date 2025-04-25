
---

# De novo Design of Miniprotein Binders Targeting the Plant Pathogen Effector

Rice, as one of the world’s most important staple crops, continuously faces threats from a variety of pathogens and pests throughout its growth cycle. Among these, rice blast disease, caused by *Magnaporthe oryzae*, is a major disease affecting both yield and quality of rice[^1][^2]. For a long time, resistance breeding in rice has mainly relied on resistance genes (R genes), especially those encoding NLR (Nucleotide-binding Leucine-rich Repeat) receptors[^3][^4][^5]. NLR-mediated effector-triggered immunity (ETI) is the core mechanism for rice resistance to blast disease, which recognizes pathogen-secreted effector proteins (such as AVR-Pia) and activates a series of immune responses, including reactive oxygen species (ROS) burst, programmed cell death, and the expression of downstream defense genes[^6][^3][^7][^8]. Recognition patterns between NLR receptors and effectors are diverse, including direct interaction, indirect guarding, decoy, and integrated decoy mechanisms[^9][^10][^4]. For example, the LRR domain of Pikp-1 can directly recognize and bind AVR-Pia[^3].

However, there is an inherent trade-off between disease resistance and high yield in rice. Studies have shown that activation of the immune system to resist pathogens often requires substantial resource allocation, leading to the downregulation of growth-related gene expression and more energy being diverted to defense, thus suppressing crop growth and yield[^11]. Especially when the peak period of blast disease coincides with the critical period of yield formation, persistent or excessive immune responses can exacerbate energy consumption and tissue damage, ultimately affecting yield and quality. Therefore, how to scientifically regulate immune intensity while maintaining disease resistance, and avoid yield loss caused by excessive immunity, is a key issue that needs to be addressed in current rice resistance breeding.

## Targeted Innovative Strategy

To address this contradiction, this study proposes an innovative immune regulation strategy: de novo design of artificial miniproteins capable of competitively binding the AVR-Pia effector protein, with their conditional expression achieved through specific inducible expression systems. Upon expression, these miniproteins bind AVR-Pia with high affinity, competitively blocking its interaction with the NLR receptor (Pikp-1), thereby suppressing the activation of the ETI pathway. In theory, this strategy can precisely regulate immune intensity during periods of high rice blast incidence and key yield formation stages, reducing yield loss caused by excessive immunity and achieving a dynamic balance between disease resistance and high yield.

## Near-term Plan

### Dry (Computational Design)

- Utilize state-of-the-art protein design tools such as Rosetta, AlphaFold, and ProteinMPNN, based on the crystal structure of the 6Q76 Pikp-1-AvrPia complex, to de novo design a series of candidate miniproteins and predict and optimize their affinity for AVR-Pia.

**Expected Outcome:**  
Obtain a batch of structurally stable miniprotein candidates with theoretically high affinity, capable of binding AVR-Pia, laying a solid foundation for subsequent experimental screening.

### Wet (In vitro, Yeast Three-Hybrid)

- Under existing experimental conditions, use the yeast three-hybrid (Y3H) system to screen and validate the binding ability of candidate miniproteins to AVR-Pia.
- Construct a ternary expression system with Pikp-1, AVR-Pia, and the miniprotein, and test the competitive inhibition of Pikp-1/AVR-Pia interaction by the miniprotein.

**Expected Outcome:**  
Successfully screen miniproteins that efficiently bind AVR-Pia and significantly inhibit Pikp-1/AVR-Pia interaction in the yeast three-hybrid system, providing a basis for in vivo functional validation.

## Innovations

### Deep Integration of Protein Engineering and Crop Genetic Improvement

- Deeply integrate advanced protein design tools such as Rosetta and AlphaFold with rice molecular breeding, promoting the application of artificial protein design technology in plant disease resistance.

### Novel Molecular Competitive Immune Regulation Strategy

- For the first time, propose the use of de novo designed miniproteins to competitively bind pathogen effectors (AVR-Pia), blocking their interaction with NLR receptors, thereby precisely regulating ETI immune response intensity at the molecular level, offering new ideas to break the growth-defense trade-off in rice.

## Challenges

- **Limited Structural Basis for Protein Design:** The currently known Pikp-1-AvrPia complex crystal structure only covers the interacting fragments and lacks complete structural information. Fragment fixation and spatial constraints may be needed for further research.
- **Efficient Expression and Functional Realization of Miniproteins:** Designed miniproteins must have both high affinity and structural stability, and be able to fold and localize correctly in plant cells. Effectively predicting and validating these characteristics during design and screening is a key challenge for functional realization.

## Long-term Plan

### Wet (In vivo, Transgenic Rice)

- Place the selected high-efficiency miniprotein genes under various inducible promoters and transform them into rice to obtain a series of transgenic materials with different inducible expression patterns and levels.
- Through grouping and gradient settings, systematically evaluate the effects of different inducible promoters and expression levels on blast resistance, immune response intensity, and agronomic traits such as yield.
- Further, select representative materials for multi-location and multi-season field trials to comprehensively assess their practical application.

**Expected Outcome:**  
Obtain various transgenic rice lines expressing miniproteins under different pathogen-inducible promoters, clarify the effects of different expression patterns and levels on immune regulation and yield, and verify the effectiveness of this strategy in actual production environments through field experiments. This will provide theoretical support and germplasm resources for molecular breeding and application.

## Challenges

- **Selection and Regulation of Inducible Promoters:** The response strength and tissue/spatiotemporal specificity of different pathogen-inducible promoters vary significantly. Screening and optimizing suitable promoters to achieve the desired expression pattern and regulatory effect require extensive experimental validation and systematic optimization.
- **Consistency of in vitro and in vivo Function and Off-target Effects:** Whether miniproteins screened in vitro can maintain high efficiency in plants, and whether they will have unintended effects on rice physiology, are uncertain and require multi-level experimental evaluation.

---

## References

[^1]: Savary, S., Willocquet, L., Pethybridge, S.J., et al. (2019) The Global Burden of Pathogens and Pests on Major Food Crops. *Nature Ecology & Evolution*, 3, 430-439. https://doi.org/10.1038/s41559-018-0793-y

[^2]: Yang, J., Yang, C., Zeng, Y., et al. (2024) Progress in the Mining and Utilization of Rice Blast Resistance Genes. *Chinese Rice Science*, 2024: 1-17.

[^3]: Wang, L., Zhao, L., Zhang, X., et al. (2019) Large-Scale Identification and Functional Analysis of NLR Genes in Blast Resistance in the Tetep Rice Genome Sequence. *Proceedings of the National Academy of Sciences*, 116, 18479-18487. https://doi.org/10.1073/pnas.1910229116

[^4]: Chen, R., Deng, Y., Ding, Y., et al. (2021) Rice Functional Genomics: Decades’ Efforts and Roads Ahead. *Science China Life Sciences*, 65, 33-92. https://doi.org/10.1007/s11427-021-2024-0

[^5]: Zhang, M., Wang, S. and Yuan, M. (2019) An Update on Molecular Mechanism of Disease Resistance Genes and Their Application for Genetic Improvement of Rice. *Molecular Breeding*, 39, Article No. 154. https://doi.org/10.1007/s11032-019-1056-6

[^6]: Zhou, J.M. and Zhang, Y.L. (2020) Plant Immunity: Danger Perception and Signaling. *Cell*, 181, 978-989. https://doi.org/10.1016/j.cell.2020.04.028

[^7]: Wang, J., Wang, R., Fang, H., et al. (2020) Two VOZ Transcription Factors Link an E Ligase and an NLR Immune Receptor to Modulate Immunity in Rice. *Molecular Plant*, 14, 253-266.

[^8]: Leach, J.E., Leung, H. and Tisserat, N. (2014) Plant Disease and Resistance. In: Van Alfen, N.K., Ed., *Encyclopedia of Agriculture and Food Systems*, Elsevier, Amsterdam, 360-374. https://doi.org/10.1016/B978-0-444-52512-3.00165-0

[^9]: Jones, J.D.G., Vance, R.E. and Dangl, J.L. (2016) Intracellular Innate Immune Surveillance Devices in Plants and Animals. *Science*, 354, aaf6395. https://doi.org/10.1126/science.aaf6395

[^10]: Cesari, S., Thilliez, G., Ribot, C.C., et al. (2013) The Rice Resistance Protein Pair RGA4/RGA5 Recognizes the Magnaporthe oryzae Effectors Avr-Pia and Avr1-Co39 by Direct Binding. *Plant Cell*, 25, 1463-1481. https://doi.org/10.1105/tpc.112.107201

[^11]: He, Z., Webster, S., He, S.Y. (2022) Growth–defense trade-offs in plants. *Current Biology*, 32(12), R541-R545. https://doi.org/10.1016/j.cub.2022.04.070

---
