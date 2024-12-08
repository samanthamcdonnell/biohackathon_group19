# **Familial Adenomatous Polyposis (FAP): Analysis through Bioinformatics**

## **Team Members**
- **Samantha McDonnell** (mcdonn8@clemson.edu)
- **Jennifer Anasky** (janasky@clemson.edu)
- **Pranavi Mallipeddi** (pmallip@clemson.edu)
- **Tripti Paudyal** (tpaudya@clemson.edu)

---

## **Abstract**
Familial Adenomatous Polyposis (FAP) is an inherited autosomal dominant disorder caused by mutations in the APC gene. The goal of this study was to identify candidate genes as well as protein interactions causing the disease phenotype, investigate DNA polymorphisms associated with altered gene expression, and propose a hypothesis to identify the disease mechanism. Key findings include the creation of a PPI network centered around APC, polymorphisms that may disrupt gene expression, and hypotheses for non wild-type gene expression.

---

## **Introduction**
### **Background**
Familial Adenomatous Polyposis (FAP) is a genetic disorder characterized by the development of numerous adenomatous polyps in the colon and rectum. The disease is primarily caused by mutations in the **APC** (Adenomatous Polyposis Coli) gene, which plays a crucial role in tumor suppression. The condition mostly affects the gastrointestinal tract, but its physiological impact extends to multiple organ systems due to the crucial role of the APC gene in cellular regulation. If left untreated, FAP often progresses to colorectal cancer.

### **Objectives**
This project focused on:
1. Identifying seed genes associated with FAP.
2. Building a protein:protein interaction (PPI) network around APC.
3. Investigating DNA polymorphisms and their impact on APC expression.
4. Constructing a proposed mechanism for the disease phenotype.

---

## **Methods**

### **1. Disease Overview**
- **Symptoms**: adenomatous polyps in the colon and rectum, desmoid tumors, osteomas, dental abnormalities, CHRPE, epidermoid cysts, and thyroid and adrenal tumors.
- **Organs Involved**: Colon, rectum, small intestine, stomach, thyroid gland, adrenal glands, bones, teeth, connective tissue, skin, brain, retina, liver, ovaries, testes.
- **Frontline Treatments**: prophylactic surgery, endoscopic management, chemoprevention.

### **2. Gene Identification**
- **Primary Gene**: **APC** which plays a crucial role in tumor suppression and cellular regulation.
- **Data Sources**: GTEx to get tissue-specific expression information, PubMed for gene-disease associations.
- **Expression Patterns**: APC is typically expressed in the human colon in maintaining the normal structure and function of the colonic epithelium. The APC gene is misexpressed in FAP due to truncating mutations.

### **3. PPI Network Construction**
- **Tools Used**: Cytoscape, EBI IntAct database.
- **Procedure**:
  - Identified the seed protein to be APC.
  - Network expansion to include other proteins such as β-catenin (**CTNNB1**) in the Wnt signaling pathway.
  - ToppFun enrichment analysis led to the discovery of the involvement in cell cycle regulation and tumor suppression.

### **4. DNA Polymorphism Analysis**
- **eQTL Identification**:
  - **Tools Used**: GTEx database.
  - Example: Expression in colonic tissue is affected by a polymorphism in the APC promoter region.
  - Findings: eQTLs may alter the normal expression of APC leading to polyp formation.

### **5. Hypothesis Construction**
**Hypothesis**: Truncating mutations within the APC gene lead to the hyperactivation of the Wnt Signaling Pathway leading to excessive cell proliferation and polyp formation.

---

## **Results**

### **Gene Discovery**
- **Seed Gene**: APC.
- **Function**: Tumor suppressor; regulate β-catenin degradation.
- **Associated Genes**: **CTNNB1**, **AXIN1**, **AXIN2**.

### **PPI Network**

### **DNA Polymorphisms**

### **Hypothesis**
- FAP is caused by a disregulation of APC and its downstream effects on the accumulation of β-catenin, leading to excessive cell proliferation.

---

## **Discussion**

### **Interpretation of Results**
APC plays a central role in FAP and highlighted genetic variants that affect its expression. The PPI network highlights the importance of interactions in the Wnt signaling pathway.

