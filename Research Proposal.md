---

# De novo Design of Miniprotein Binders Targeting the Plant Pathogen Effector

水稻作为全球最重要的粮食作物之一，在其生长周期中持续面临多种病原体和害虫的威胁。其中，稻瘟病由稻瘟病菌（*Magnaporthe oryzae*）引发，是影响水稻产量与品质的主要病害之一[^1][^2]。长期以来，水稻抗病育种主要依赖抗病基因（R基因），尤其是编码NLR（Nucleotide-binding Leucine-rich Repeat）受体的基因[^3][^4][^5]。NLR介导的效应物触发免疫（ETI）是水稻抵抗稻瘟病的核心机制，其通过识别病原体分泌的效应蛋白（如AVR-Pia），激活一系列免疫反应，包括活性氧（ROS）爆发、细胞程序性死亡以及下游防御基因的表达[^6][^3][^7][^8]。NLR受体与效应物的识别模式多样，涵盖直接互作、间接保护、诱饵及协同诱饵等机制[^9][^10][^4]。以Pikp-1-AvrPia为例，Pikp-1的LRR结构域能够直接识别并结合AVR-Pia[^3]。

然而，水稻抗病性与高产性之间存在天然的权衡。已有研究表明，植物在激活免疫系统抵御病原体时，常常需要消耗大量资源，导致生长相关基因表达下调，能量更多分配于防御反应，从而抑制作物生长与产量[^11]。尤其是在稻瘟病高发期与水稻产量形成关键期重叠时，持续或过度的免疫反应会加剧能量消耗和组织损伤，最终影响产量和品质。因此，如何在维持抗病性的同时，科学调控免疫反应强度，避免因过度免疫导致的产量损失，是当前水稻抗病育种亟需解决的核心问题之一。

## 针对性创新策略

针对这一矛盾，本研究提出了一种创新性的免疫调控策略：从头设计能够竞争性结合AVR-Pia效应蛋白的人工miniprotein，并通过特定诱导型表达系统实现其条件性表达。该miniprotein通过高亲和力结合AVR-Pia，竞争性阻断其与NLR受体（Pikp-1）的互作，从而抑制ETI通路的激活。理论上，该策略可在稻瘟病高发且产量形成关键期，精准调控免疫强度，减少因过度免疫引起的产量损失，实现抗病性与高产性的动态平衡。

## 近期计划

### Dry（计算设计）

- 利用Rosetta、AlphaFold、ProteinMPNN等前沿蛋白设计工具，基于6Q76 Pikp-1-AvrPia复合物的晶体结构，采用de novo策略设计一系列候选miniprotein，并预测及优化其与AVR-Pia的亲和力。

**预期结果：**  
获得一批结构稳定、理论亲和力高的miniprotein候选分子，具备与AVR-Pia结合的潜力，为后续实验筛选奠定坚实基础。

### Wet（体外，酵母三杂交）

- 结合现有实验条件，采用酵母三杂交（yeast three-hybrid, Y3H）体系，对候选miniprotein与AVR-Pia的结合能力进行筛选和验证。
- 通过构建含有Pikp-1、AVR-Pia和miniprotein的三元表达系统，检测miniprotein对Pikp-1与AVR-Pia互作的竞争抑制效果。

**预期结果：**  
成功筛选出能够在酵母三杂交体系中高效结合AVR-Pia，并显著抑制Pikp-1与AVR-Pia互作的miniprotein，为体内功能验证提供基础。

## 创新点

### 蛋白工程与作物遗传改良的深度融合

- 将Rosetta、AlphaFold等前沿蛋白设计工具与水稻分子育种深度结合，推动人工蛋白设计技术在植物抗病领域的应用转化。

### 分子竞争性免疫调控新策略

- 首创性提出通过de novo设计的miniprotein竞争性结合病原效应蛋白（AVR-Pia），阻断其与NLR受体互作，从分子水平精准调控ETI免疫反应强度，为突破水稻生长-防御权衡提供新思路。

## 难点与挑战

- **蛋白设计的结构基础有限：** 目前已知的Pikp-1-AvrPia复合物晶体结构仅涵盖互作片段，缺乏完整结构信息，可能需借助片段固定和空间约束等手段，以便顺利开展后续研究。
- **miniprotein的高效表达与功能实现：** 设计的miniprotein需兼具高亲和力和结构稳定性，并能在植物细胞内正确折叠和定位。如何在设计和筛选过程中有效预测并验证这些特性，是实现其功能的关键难题。

## 远期规划

### Wet（体内，水稻转基因）

- 将筛选到的高效miniprotein基因分别置于多种诱导型启动子下，转入水稻，获得一系列不同诱导表达模式和表达水平的转基因材料。
- 通过分组和分梯度设置，系统评价不同诱导型启动子及表达水平对稻瘟病抗性、免疫反应强度和产量等农艺性状的影响。
- 进一步，选择具有代表性的材料在大田条件下开展多点、多季田间试验，全面评估其实际应用效果。

**预期结果：**  
获得在不同病原诱导型启动子调控下表达miniprotein的多种转基因水稻材料，明确不同诱导表达模式和表达水平对免疫调控及产量的影响规律。田间实验验证该策略在实际生产环境中的有效性，实现抗病与高产的动态平衡，为分子育种和推广应用提供理论依据和种质资源。

## 难点与挑战

- **诱导型启动子的选择与表达调控：** 不同病原诱导型启动子的响应强度及其组织、时空特异性存在显著差异，如何筛选和优化合适的启动子以实现理想表达模式与调控效果，需大量实验验证与系统优化。
- **体外与体内功能一致性及非靶效应：** 体外筛选获得的miniprotein在植物体内能否保持高效功能，是否会对水稻自身生理过程产生非预期影响，均存在不确定性，需通过多层次实验系统进行评估。

---

## 参考文献

[^1]: Savary, S., Willocquet, L., Pethybridge, S.J., et al. (2019) The Global Burden of Pathogens and Pests on Major Food Crops. *Nature Ecology & Evolution*, 3, 430-439. https://doi.org/10.1038/s41559-018-0793-y

[^2]: 杨婕, 杨长登, 曾宇翔, 等. 水稻稻瘟病抗性基因挖掘与利用研究进展[J]. 中国水稻科学, 2024: 1-17.

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
