# Multi-task-deep-learning-based-failure-diagnosis-for-tubular-joints

## **The all datasets will be uploaded here once the journal article is online.**<br />

## **The website of the paper will be uploaded here once the journal article is online.**
****

### **Paper**: <br />Multi-task deep learning-based failure diagnosis for tubular joints: Automated identification and description generation<br />

**Abstract**: <br />Tubular joints are critical yet vulnerable components in offshore platforms and bridges, where complex stress states frequently lead to concurrent failure modes such as weld cracking, brace buckling, and chord plastification. Traditional failure inspection approaches are labor-intensive and time-consuming, while emerging intelligent methods generally rely on single-task or single-modal designs that provide only failure labels or isolated descriptive information. Such methods often struggle to fully exploit the richness of multi-modal data and fail to effectively capture coexisting failure patterns, resulting in limited interpretability and incomplete diagnostic results. To overcome these limitations, this study proposes a multi-task deep learning model for simultaneous failure identification and description generation of tubular joints. A multi-modal database is compiled from 141 experimental programs, including 409 failed joints with images, textual descriptions, and component-level labels, which is further augmented to 1,227 images and 3,681 sentences. The devised model employs a pretrained encoder for image features extraction, a multi-label classification decoder for failure identification, and an attention-based image captioning decoder for failure description generation. A consistency loss enforces semantic alignment between classification labels and textual outputs. The developed model achieves a BLEU-4 of 76.70 and an mAP of 0.9529, outperforming single-task baselines. Validation on real engineering images also demonstrates preliminary transferability, highlighting the potential of the proposed multi-task learning framework for automated failure diagnosis.<br />

**Database establishment**<br />
The workflow for constructing the image and text databases is illustrated in Fig. 1, containing four key steps. Specifically, following a systematic search of common literature databases, 409 failed tubular joints are collected from 141 independent experimental programs reported in theses and journal papers. <br />
<div align=center>
<img src="https://github.com/ZHANGWenhao00/Multi-task-deep-learning-based-failure-diagnosis-for-tubular-joints/blob/main/1.png" >
</div>

<div align="center">
  Fig. 1. Construction of image/text databases for failure identification and description generation of tubular joints.
</div> 
