# EchoFoundationModel-Survey
This is an updating literature review of the foundation models for echocardiogram. We will include the popular network backbones for video representation learning. Note that we current don't consider the multi-modality scenario such as the vision-language model. Moreover, I list the public datasets that are implemented in the papers.


### Echocardiogram

| | Paper Title | Year | Institution | Code | Modality | Backbone |
| :--: | :--------- | :-----: | :-----: | :-----: | :-----: | :-----: |
| 1 | EchoApex: A General-Purpose Vision Foundation Model for Echocardiography [pdf](https://arxiv.org/pdf/2410.11092) | 2024 | Siemens Healthineers | - | TTE, TEE, ICE | ViT-base |
| 2 | EchoFM: Foundation Model for Generalizable Echocardiogram Analysis [pdf](https://arxiv.org/pdf/2410.23413) | 2024 | MGH | [Github](https://github.com/SekeunKim/EchoFM) | TTE | - |
| 3 | Echo-Vision-FM: A Pre-training and Fine-tuning Framework for Echocardiogram Video Vision Foundation Model [pdf](https://www.medrxiv.org/content/10.1101/2024.10.09.24315195v3.full.pdf) | 2024 | Northwestern University |  | TTE | ViT-base |
| 4 | PanEcho: Complete AI-enabled echocardiography interpretation with multi-task deep learning [pdf](https://pmc.ncbi.nlm.nih.gov/articles/PMC12047937/) | 2025 | Yale University | [Github](https://github.com/CarDS-Yale/PanEcho) | TTE | - |
| 5 | EchoFlow: A Foundation Model for Cardiac Ultrasound Image and Video Generation [pdf](https://arxiv.org/pdf/2503.22357) | 2025 | Imperial College London | [huggingface](https://huggingface.co/spaces/HReynaud/EchoFlow) | TTE | A-VAE |


### Public datasets

| | Database | Modality | Format | Amount | Source |
| :--: | :--------- | :-----: | :-----: | :-----: | :-----: |
| 1 | MIMIC-IV-ECHO [link](https://physionet.org/content/mimic-iv-echo/0.1/) | TTE | video | 525,328 | Beth Israel Deaconess Medical Center |
| 2 | EchoNet-Dynamic [link](https://aimi.stanford.edu/datasets/echonet-dynamic-cardiac-ultrasound) | TTE(A4C) | video | 10,030 | Stanford University Hospital |
| 3 | CAMUS [link](https://www.creatis.insa-lyon.fr/Challenge/camus/) | TTE(A2C,A4C) | video | 500 | University Hospital of St. Etienne |
| 4 | TMED [link](https://tmed.cs.tufts.edu/) | TTE | video | 599 | Tufts Medical Center |

