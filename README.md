# Laboratory Activity: Cell-Cell-Communication
**Name:** Martinez, Jen Marie A.
**Section:** A

## Part A: Choose and Register Sender Cell

**Chosen Sender Cell:** Eosinophil

**Tisuue/Context:** Mainly found in blood and tissues, especially at sites involved in allergic inflammation and parasite infections

**Why it is a biologically meaningful sender:** Eosinophils release signaling molecules such as cytokines, chemokines, and inflammatory mediators that communicate with other immune cells and help coordinate immune and inflammatory responses.

**Biological Context:** Immune activation and inflammation during an allergic response.

**Biological Question:** How does an eosinophil communicate with other cells to promote inflammation during an allergic response?

## Part B: Candidate Signal Produced by the Sender Cell

**Official Gene Symbol:** PRSS33

**Official Protein Name:** Serine protease 33

**Evidence of Expression / Production**
According to The Human Protein Atlas (Granulocytes - Eosinophils table), PRSS33 exhibits very high enriched expression in human eosinophils, with a transcript abundance of 1353.2 nTPM. It encodes a secreted serine protease localized to immune granulocytes.

**Signaling Type:** Paracrine Signaling

**Justification:** PRSS33 is a locally secreted protease. Upon release by activated eosinophils into surrounding tissue, it acts locally on adjacent cells (such as epithelial cells and airway tissue) to regulate immune signaling and remodeling rather than acting as a systemic endocrine hormone.

## Part C: Receptor and Receiver Cell

The eosinophil produces and secretes PRSS33, which can signal through F2RL1 (PAR2) on airway fibroblasts in the context of inducing extracellular matrix synthesis and tissue remodeling during allergic inflammation. 

**Biological Justification & Pathway Context:** 
  In allergic airway inflammation, activated eosinophils release the trypsin-like serine protease PRSS33 into the extracellular matrix. F2RL1 (PAR2) is a well-characterized transmembrane G-protein coupled receptor (GPCR) abundantly expressed on the surface of human lung and airway fibroblasts (validated by the *Human Protein Atlas* and *UniProt* entry P55085). In airway fibroblasts, this cell-to-cell communication axis triggers cell proliferation, extracellular matrix (ECM) synthesis, and tissue remodeling associated with allergic conditions like chronic asthma.
  
## Part D: Explore the Receptor-Centered Network in STRING

**Proteins included in the STRING network:**

PRSS33, 
F2RL1 (PAR2),
GNAQ,
GNB1, 
GNG2, 

**STRING Network:**
![STRING Network Evidence](<img width="3253" height="773" alt="03_string_network" src="https://github.com/user-attachments/assets/f16107e0-5146-4137-b982-24f0636a072a" />)


### Functional Enrichment

**Enriched functional term:**  Heterotrimeric G-protein complex

**Count:** 3 of 35 proteins

**False Discovery Rate (FDR):** 0.00012

**Biological relevance:**  This term is relevant because F2RL1/PAR2 is a G-protein-coupled receptor, while GNAQ, GNB1, and GNG2 are components of heterotrimeric G-protein signaling.

**Enriched pathway:**  
Thrombin signalling through proteinase activated receptors (PARs)

**False Discovery Rate (FDR):** 5.68 × 10⁻⁵

**Biological relevance:**  This pathway is relevant because F2RL1 is PAR2, a member of the proteinase-activated receptor family.

**Proteins connecting receptor activation to the cellular response**

1. **GNAQ**
2. **GNB1**
3. **GNG2** 

**STRING Interpretation Note**

STRING edges represent functional associations and do not necessarily indicate direct physical interactions or prove the exact order of signaling events. GNAQ, GNB1, and GNG2 were selected based on their functional annotations and their association with F2RL1/PAR2.

## Part E: Validation of One Molecular Interaction in IntAct

**Featured Interacting Pair:** GNB1 — GNG2

**Interacting Molecules**
- **Molecule A:** GNB1 (UniProt AC: P62873)
- **Molecule B:** GNG2 (UniProt AC: P59768)

**Interaction Detection Method:** ion exchange chrom (Ion exchange chromatography)

**Interactor A Species:** *Homo sapiens* (TaxID: 9606)

**Interactor B Species:** *Homo sapiens* (TaxID: 9606)

**Host Organism:** *Trichoplusia ni* (Cabbage looper)

**Publication / Reference Information:**
[23739333](https://europepmc.org/article/MED/23739333)

**Interaction Type:** Physical association

## Part F: Final Cell-to-Cell Communication Model Interpretation 
The figure illustrates a proposed cell-to-cell communication pathway between an eosinophil and an airway fibroblast during allergic airway inflammation. The eosinophil acts as the sender cell, releasing the serine protease PRSS33 into the airway subepithelial extracellular space. PRSS33 then interacts with the F2RL1/PAR2 receptor located on the surface of the airway fibroblast. Because PAR2 is a protease-activated receptor, PRSS33 is proposed to cleave its extracellular N-terminal region, exposing the receptor’s tethered ligand and activating intracellular signaling.

Following PAR2 activation, the figure proposes a signaling cascade involving G-protein activation, PLC, Ca²⁺, PKC, and MAPK/ERK. These intracellular components transmit the signal from the cell membrane to the cellular response. The expected response of the receiver cell is increased fibroblast proliferation and extracellular matrix (ECM) synthesis. Increased production and deposition of ECM components can contribute to airway wall remodeling, which is associated with chronic allergic airway inflammation and asthma.

Overall, the figure represents how an eosinophil-derived signal may influence airway fibroblast behavior. The PRSS33–PAR2 interaction and resulting fibroblast/ECM response are supported by biological evidence, while the complete intracellular sequence shown is a proposed mechanistic pathway and should therefore be interpreted as a model rather than a fully established sequence.

## Reference Resources

* **OmniPath: intra- and intercellular signaling knowledge:** https://omnipathdb.org/ * **STRING: functional protein association networks:** https://string-db.org/
* **IntAct molecular interaction database:** https://www.ebi.ac.uk/intact/  Human Protein Atlas: https://www.proteinatlas.org/
* **UniProt:** https://www.un
* 
