## Technical Skills
- Programming Languages
  - Python, 
  - R,
- Database Management 
  - SQL, 
- Data Visualization:
  - Tableau 

## Professional Experience

- Scientific assistant at Ruhr University Bochum, (_2019 - 2024_)
    - Department of Anatomy and Molecular Embryology
    - Department of Human Genetics

- Scientific assistant at Max Delbrück Center for Molecular Medicine, Helmholtz Institute Berlin (_2017 - 2019_)
    - Research Group of Cellular Neurosciences


## Education

- Data Analytics Bootcamp, ROGM Masterschool GmbH (_2024/2025_)

- Dr. rer. nat., Graduate School of Chemistry and Biochemistry, Ruhr University Bochum (_2023_)

- M.Sc., International Master for Molecular and Developmental Stem Cell Biology, Ruhr University Bochum (_2016_)

- B.Sc., Biology, Ruhr University Bochum (_2014_)

## Projects

- [Academic Research Projects](#Academic Research Projects)
  - [Generation of Skeletal Muscle Organoids from Human Pluripotent Stem Cells](#Generation of Skeletal Muscle Organoids from Human Pluripotent Stem Cells)
  - [Myogenic deveolopment in in vitro cell culture models](#Myogenic deveolopment in in vitro cell culture models)
- [Data Science Projects](#Data Science Projects)
  - [Vehicle Category Prediction Using Machine Learning](#Vehicle Category Prediction Using Machine Learning)
  - [Data Visualization for Sales Analysis of an Emerging E-Commerce Business](#Data Visualization for Sales Analysis of an Emerging E-Commerce Business)

### Academic Research Projects

#### Generation of Skeletal Muscle Organoids from Human Pluripotent Stem Cells
[Publication](https://bio-protocol.org/en/bpdetail?id=4984&type=0)

Various protocols have been proven effective in the directed differentiation of mouse and human pluripotent stem cells into skeletal muscles and used to study myogenesis. Current 2D myogenic differentiation protocols can mimic muscle development and its alteration under pathological conditions such as muscular dystrophies. 3D skeletal muscle differentiation approaches can, in addition, model the interaction between the various cell types within the developing organoid. Our protocol ensures the differentiation of human embryonic/induced pluripotent stem cells (hESC/hiPSC) into skeletal muscle organoids (SMO) via cells with paraxial mesoderm and neuromesodermal progenitors’ identity and further production of organized structures of the neural plate margin and the dermomyotome. Continuous culturing omits neural lineage differentiation and promotes fetal myogenesis, including the maturation of fibroadipogenic progenitors and PAX7-positive myogenic progenitors. The PAX7 progenitors resemble the late fetal stages of human development and, based on single-cell transcriptomic profiling, cluster close to adult satellite cells of primary muscles. To overcome the limited availability of muscle biopsies from patients with muscular dystrophy during disease progression, we propose to use the SMO system, which delivers a stable population of skeletal muscle progenitors from patient-specific iPSCs to investigate human myogenesis in healthy and diseased conditions.

![Skeletal muscle organoid induction and timeline of differentiation media applications and growth factor compositions](/images/grafical_abstract_Kindler_et_al_2024.png)

#### Myogenic deveolopment in in vitro cell culture models 
[Publication](https://elifesciences.org/reviewed-preprints/87081)

Myogenesis starts from early embryonic development until postnatal maturation. Until recently, little was known about the myogenic development in humans. Single cell analyses become more and more popular for the study of the heterogeneity of cell populations within one type of tissue. Upcoming scRNA-seq studies along different time points of muscle development start to clarify these ranges ([Xi et al., 2020](https://www.sciencedirect.com/science/article/pii/S1934590920301569)). Reconstruction of a developmental roadmap to investigate the maturation grade of myogenic progenitors along myogenic development gave an exact picture of in vitro differentiated cells as described by ([Xi et al., 2020](https://www.sciencedirect.com/science/article/pii/S1934590920301569)). Technically, to align the raw data to the human genome the Cell Ranger version 5 software was applied. To analyze organoid scRNA seq datasets, “Seurat” version 4.3 is used ([Hao et al., 2021](https://www.cell.com/cell/fulltext/S0092-8674(21)00583-3?_returnURL=https%3A%2F%2Flinkinghub.elsevier.com%2Fretrieve%2Fpii%2FS0092867421005833%3Fshowall%3Dtrue); [Satija et al., 2015](https://www.nature.com/articles/nbt.3192)). The developmental score was calculated as described in ([Xi et al., 2020](https://www.sciencedirect.com/science/article/pii/S1934590920301569)). The ‘‘AddModuleScore’’ function was used to calculate the embryonic and adult score, using a list of differentially expressed genes (DEGs) between adult and embryonic myogenic progenitor clusters. The analysis were carried out using RStudio. A detailed description of the analysis and the 3D skeletal muscle organoid model can be found here ([Kindler et al., 2024](https://bio-protocol.org/en/bpdetail?id=4984&type=0); [Mavrommatis et al., 2023](https://elifesciences.org/reviewed-preprints/87081)) 

![developmental score](/images/developmental_score_elife.png)

### Data Science Projects:

#### Vehicle Category Prediction Using Machine Learning
**Goal:** Develop a machine learning model to predict unknown vehicle market categories and conduct comprehensive data analysis.

**Description:**
This project involved analyzing a complex vehicle dataset and implementing a K-Nearest Neighbors (KNN) classification model to predict market categories. The focus was on data preprocessing, exploratory data analysis (EDA), and optimizing the model for better performance.

#### Data Visualization for Sales Analysis of an Emerging E-Commerce Business

This project involved creating an interactive Tableau dashboard to analyze sales data for Unicorn, a fictitious e-commerce company. The dataset simulated real-world business challenges faced by online retailers, offering insights into sales trends, regional performance, and product category dynamics. The dashboard served as a powerful tool for stakeholders to identify growth opportunities, address weak areas, and make data-driven decisions.

**Goal:**
Develop a user-friendly Tableau dashboard to visualize key sales metrics, including revenue, profit, and product performance, and provide actionable recommendations for business growth.

**Description:**
The project focused on building a dynamic and interactive Tableau dashboard that allowed stakeholders to explore sales data from 2015-2018.
[Tableau dashboard](https://public.tableau.com/app/profile/urs.kindler/viz/Kindler_Unicorn_Project_Masterschool/UnicornCompanyPerformance)


#### Publication

Kindler, U., Zaehres, H., & Mavrommatis, L. (2024). Generation of Skeletal Muscle Organoids from Human Pluripotent Stem Cells. BIO-PROTOCOL, 14(1344). https://doi.org/10.21769/BIOPROTOC.4984 

Mavrommatis, L., Zaben, A., Kindler, U., Kienitz, M.-C., Dietz, J., Jeong, H.-W., Böhme, P., Brand-Saberi, B., Vorgerd, M., & Zaehres, H. (2023). CRISPR/Cas9 genome editing in LGMD2A/R1 patient-derived induced pluripotent stem and skeletal muscle progenitor cells. Stem Cells International. https://doi.org/10.1155/2023/9246825 

Mavrommatis L., Jeong H-W, Kindler U., Gomez-Giro G., Kienitz M-C., Stehling M., Psathaki OE., Zeuschner D., Bixel MG., Han D., Morosan-Puopolo G., Gerovska D., Yang JH., Kim JB, Araúzo-Bravo MJ, Schwamborn JC, Hahn SA, Adams RH, Schöler HR, Vorgerd M., Brand-Saberi B., Zaehres H. (2023). Human skeletal muscle organoids model fetal myogenesis and sustain uncommitted PAX7 myogenic progenitors. ELife, 12. https://doi.org/10.7554/ELIFE.87081 

Brendel, M., Scharf, M., Kindler, U., Srirama, S., Divvela, K., & Brand-Saberi, B. (2023). Detection of Math6-Expressing Cell Types in Murine Placenta. Biology 2023, Vol. 12, Page 1252, 12(9), 1252. https://doi.org/10.3390/BIOLOGY12091252 

Pan, Y., Xiong, M., Chen, R., Ma, Y., Corman, C., Maricos, M., Kindler, U., Semtner, M., Chen, Y.-H., Dahiya, S., & Gutmann, D. H. (2018). Athymic mice reveal a requirement for T-cell-microglia interactions in establishing a microenvironment supportive of Nf1 low-grade glioma growth. Genes and Development, 32(7–8). https://doi.org/10.1101/gad.310797.117
