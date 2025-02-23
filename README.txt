##Paper
Window-Oriented Token Selection and Fusion for Multi-Modality Vehicle Re-Identification with Knowledge Consistency Constraint

##Abstract
Multi-modality vehicle re-identification, as a crucial task in intelligent transportation system, aims to retrieve specific vehicles across non-overlapping cameras by amalgamating visible and infrared images. The main challenge lies in mitigating inter-modality discrepancies and extracting modality-irrelevant vehicle information. Existing methods concentrate on the integration of distinct modalities, but less attention is paid to the modality-specific crucial information. To this end, we propose a novel depth-driven Window-oriented Token Selection and Fusion network, designated as WTSF-ReID. Specifically, WTSF-ReID is comprised of three distinct modules. The initial component is a Multi-modality General Feature Extraction (MGFE) module, which employs a weight-shared vision transformer to extract features from multi-modality images. The subsequent component is a depth-driven Window-oriented Token Selection and Fusion (WTSF) module, which implements local-to-global windows to select the significant tokens, followed by token fusion and feature aggregation to extract modality-specific crucial information while mitigating inter-modality discrepancies. Finally, to further reduce inter-modality heterogeneity and enhance feature discriminability, a Knowledge Consistency Constraint (KCC) loss simultaneously deploying inter-modality token selection constraint, modality center constraint, and modality triplet constraint is constructed. Extensive experiments on the popular datasets demonstrate the competitive performance against state-of-the-art methods.

##Datasets
MSVR310: https://pan.baidu.com/s/11k8_stRrjodj7797rZ0wRw, code: unic 
RGBNT100: https://pan.baidu.com/s/1SSuBKhBAOUPVlWKnr0OErw, code: unic

##Experimental Environment
PyTorch = 1.8
Python = 3.8
cuda = 11.1
torchaudio = 0.8.0
torchvision = 0.9.0

##Code will be released soon.