> **Implement AV-Hubert unit pretraining task and UTUT pretraining/finetuning pipelines with associated data and configurations.**
---

### ▶️ Download Large Files
This project requires several large binary files that cannot be stored in this GitHub repository due to the 100MB file limit.

<br>
Please download them from Google Drive using gdown:

<br>
<b>

1. Install gdown: </b>
`pip install gdown`
<b>
2. Download files: </b>
```
gdown --id 1VRKEn_Kjw1TYzaPNi0dhcaLWaOxbd0Eg -O data/train.en-es.en.bin
gdown --id 1kIkYd0zkC-nt8VCL3Mfw3k7UZRQdjux6 -O data/train.en-es.es.bin
```


After downloading, ensure the directory structure is:
```
AV2AV_granted_resources/utut_finetune/data/dataset_mbart_ft_bin_data/
  ├── (existing files...)
  ├── train.en-es.en.bin
  └── train.en-es.es.bin
```
These files are limited to 100MB by Gitand must be manually downloaded before running the code.