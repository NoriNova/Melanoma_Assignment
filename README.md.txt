# Project Name
> Melanoma Detection.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information
- Problem Statement: To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. 
  It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential 
  to reduce a lot of manual effort needed in diagnosis.

## Conclusions
- With basic CNN model, High training accuracy (89%), but poor validation accuracy (54%). Likely overfitting.
- With Data Augmentation & Dropout: Reduced training accuracy (55%) and lower validation accuracy (43%). Likely underfitting.
- Class Balance + Batch Normalization: High training accuracy (90%) but poor validation accuracy (70%).

## Technologies Used
- tensorflow - 2.18.0
- keras - 3.6.0
