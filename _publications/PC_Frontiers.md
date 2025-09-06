---
title: "Automated Measurement of Penile Curvature using Deep Learning based Novel Quantification Method."
collection: publications
category: manuscripts
permalink: "https://www.frontiersin.org/journals/pediatrics/articles/10.3389/fped.2023.1149318/full"
excerpt: '**S. B. Baray**, M. Abdelmoniem, S. Mahmud, S. Kabir, M. A. A. Faisal, M. E. H. Chowdhury, and T. O. Abbas, "Automated Measurement of Penile Curvature Using Deep Learning-Based Novel Quantification Method," Front. Pediatr., vol. 11, Art. no. 1149318, 2023, doi: 10.3389/fped.2023.1149318.'
date: 2023-04-16
venue: 'Frontiers in Pediatrics'
# slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
paperurl: 'https://www.frontiersin.org/journals/pediatrics/articles/10.3389/fped.2023.1149318/full'
# citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---

**Objective:** Develop a reliable, automated deep learning-based method for accurate measurement of penile curvature (PC) using 2-dimensional images.

**Materials and methods:** A set of nine 3D-printed models was used to generate a batch of 913 images of penile curvature (PC) with varying configurations (curvature range 18° to 86°). The penile region was initially localized and cropped using a YOLOv5 model, after which the shaft area was extracted using a UNet-based segmentation model. The penile shaft was then divided into three distinct predefined regions: the distal zone, curvature zone, and proximal zone. To measure PC, we identified four distinct locations on the shaft that reflected the mid-axes of proximal and distal segments, then trained an HRNet model to predict these landmarks and calculate curvature angle in both the 3D-printed models and masked segmented images derived from these. Finally, the optimized HRNet model was applied to quantify PC in medical images of real human patients and the accuracy of this novel method was determined.

**Results:** We obtained a mean absolute error (MAE) of angle measurement <5° for both penile model images and their derivative masks. For real patient images, AI prediction varied between 1.7° (for cases of ∼30° PC) and approximately 6° (for cases of 70° PC) compared with assessment by a clinical expert.

**Discussion:** This study demonstrates a novel approach to the automated, accurate measurement of PC that could significantly improve patient assessment by surgeons and hypospadiology researchers. This method may overcome current limitations encountered when applying conventional methods of measuring arc-type PC.

Read the full paper at: [Automated Measurement of Penile Curvature using Deep Learning based Novel Quantification Method.](https://www.frontiersin.org/journals/pediatrics/articles/10.3389/fped.2023.1149318/full)