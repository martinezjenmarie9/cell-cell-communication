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

## Part D: Explore the Receptor-Centered Network in STRING

**Proteins included in the STRING network:**

PRSS33, 
F2RL1 (PAR2),
GNAQ,
GNB1, 
GNG2, 

**STRING Network**


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

**Featured Protein Pair:** GNB1 — GNAQ

**Interacting Molecules**

Molecule A: GNB1 (UniProt AC: P62873)

Molecule B: GNAQ (UniProt AC: P50148)

**Interaction Detection Method:** anti tag coip (Anti-tag coimmunoprecipitation)

**Interactor A Species:** *Homo sapiens* (TaxID: 9606)

**Interactor B Species:** *Homo sapiens* (TaxID: 9606)

**Host Organism:** *Homo sapiens HEK293T embryonic kidney cell*

**Publication / Reference Information:** [https://www.cell.com/cell/fulltext/S0092-8674(21)00446-3?]_returnURL=https%3A%2F%2Flinkinghub.elsevier.com%2Fretrieve%2Fpii%2FS0092867421004463%3Fshowall%3Dtrue

**Interaction Type:** Physical association







