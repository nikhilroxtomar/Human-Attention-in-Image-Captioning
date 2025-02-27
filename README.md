# Human-Attention-in-Image-Captioning-Dataset-and-Analysis-ICCV-2019
## Introduction
This is the github page for my ICCV 2019 paper ([link](https://arxiv.org/pdf/1903.02499.pdf)).
We provide the the link of the data we collected in the paper:
![picture](/fg/data.png)
[capgaze1](https://drive.google.com/open?id=1qlOCr8TX6dmAxhlCob79X29riyQ_MRlq):contains 1000 images, and raw data (eye-fixations and verbal description) from 5 native English speakers. This part of data was used for the analysis. For data privacy reason, the voice of the verbal description was converted by a masking process (pitch modulation, the content was preserved).

[capgaze2](https://drive.google.com/drive/folders/1ghe3_7tdx2f3ejiKEnv6w_JJ39-9c9eB?usp=sharing): contains 3000 images, and processed data (we combined all the eye-fixations from different people for each image into a fixation map). This part of data was used for developing saliency prediction model under the image captioning task.

Also we give the code for extracting the information in the collected data in the demo folder (an example in the demo.ipynb).

# Contact
<senhe752@gmail.com>
