## Description

This contains the "GPT-4 USMLE Error Dataset" (G4UE) that is accepted as a full paper to the SIGIR 2024 "Resource and Reproducibility Track". The paper is titled "Beyond Accuracy: Investigating Error Types in GPT-4's Responses to USMLE Questions".

The resources are present under the "data" directory.

The semrep annotations consisting of UMLS concepts and semantic predications are present under "semrep" directory.

The codebase for setting up the Potato annotation platform to replicate our span-labeling annotation setup in present under "prolific-potato-annotation" directory

## Resources Overview

![Overview of resources created in the paper](resources-overview1.png)

## MedQA Dataset

The MedQA dataset is not a contribution of this work. It is obtained from the [Google Drive link](https://drive.google.com/file/d/1ImYUSLk9JbgHXOemfvyiDiirluZHPeQw/view) mentioned on the MedQA "Papers with Code" [homepage](https://paperswithcode.com/dataset/medqa-usmle).

In this work, we contribute only the error taxonomy, error type annotations to the MedQA dataset as well as the long form GPT-4 responses to a large portion of the MedQA training dataset.


