# EMHDD
Enhanced Motorcycle Helmet Detection Dataset

[toc]

## Contact

If you have any questions or communication, please contact us:

* Zhiqiang Liu: 2023211273@student.cup.edu.cn

## Update logs

**We are gradually opening up.**

1. From June 2023 to December 2023, this more comprehensive dataset was finally constructed through collection, screening, annotation, and other work.
2. On April 18, 2024, we created this warehouse to publicly disclose our work and presented relevant introductions and examples.



## Abstract

Compared to daytime, nighttime or other challenging scenarios present lower visibility and larger blind spots. Detection tasks in more challenging scenarios, such as nighttime, still suffer from problems such as low accuracy, which are problems that researchers need to break through. In order to push the field further in the future, we constructed a more comprehensive dataset.

Over six months, we collected urban road videos covering various scenarios such as daytime, nighttime, cloudy, and rainy conditions. We reasonably positioned several camera sampling points in both Beijing and Jinan, Shandong Province. These cameras are designed to rotate at scheduled intervals, capturing motorcycles from different angles and directions. Then, we conduct preliminary processing on the collected videos by trimming segments with prolonged absences of motorcycles and removing segments where motorcycles are only present at the edges of the camera lenses. This processing ensures the effectiveness of the data used for model training, mitigating any potential adverse impact on our model. Ultimately, we obtained 265 valid videos. From these videos, we extracted 52,800 images at a rate of 2 frames per second and further annotated these images, creating a more comprehensive dataset, which was named EMHDD (Enhanced Motorcycle Helmet Detection Dataset).

## Introduction

### example:

<img src="README\Example.png" alt="Example" style="zoom:20%;" />

### quantization:

<img src="README/Quantization.png" alt="Quantization" style="zoom:50%;" />

