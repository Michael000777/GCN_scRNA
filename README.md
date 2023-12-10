# Breast Tissue Metastaticity Prediction using Spatial Transcriptomic and Gene Expression
**Michael Akpabey**, Monica Bonilla, Douglas Maldonado-Torres, Sarah Kang, Jenni Liu, and Jan Rosa

**Abstract**
This research project aims to address the challenges associated with predicting breast cancer metastatic potential
by proposing an innovative approach that utilizes the spatial location and gene expression components of spatial
transcriptomic data through a Graph Convolutional Network (GCN) model. The study utilizes datasets from the 10x
Visium Spatial Transcriptomics dataset, including breast cancer and normal tissue samples, which were preprocessed and
annotated. The GCN model is designed to classify metastatic potential based on an extracellular matrix (ECM) signature
derived from previous literature comprising ESR1, TP53, NF1, AKT1, KMT2C, and PTEN genes. The methodology
involves creating a graph from the spatial data, generating an adjacency matrix, and converting the graph into an
interpretable model input. The GCN architecture consists of three convolutional layers, and the model undergoes training
and testing with an Adam optimizer. Initial results show promising accuracy after adjusting for data imbalance with an
area under receiver operating characteristic curve (AUC) of 0.91. The study concludes by acknowledging limitations,
such as the sparse availability of breast cancer transcriptomic datasets, and suggests future steps, including validation on
external datasets and exploring pooling modalities for improved generalizability.

Key words: Graph Convolution Networks (GCN), Spatial Transcriptomics, Metastasis, Breast Cancer


