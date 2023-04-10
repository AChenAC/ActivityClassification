# Human Activity Recognition using Wearable Sensor Technology

## Set up
- The entire classification tasks were performed using R version 4.2.2.
- The following three libraries have been used to perform the essential task: `tidyverse`, `glmnet`, and `caret`.
- You may use the following to install or load necessary libraries:
```
if(!require(tidyverse)){
    install.packages("tidyverse")
    library(tidyverse)
}
if(!require(glmnet)){
    install.packages("glmnet")
    library(glmnet)
}
if(!require(caret)){
    install.packages("caret")
    library(caret)
}
```

## Data Source
The data folder of this repository includes the following files:
- Training data: "training_data.txt"
- Text data: "text_data.txt"
- Data dictionary: "data_dictionary.txt"
- Information on how features are selected: "features_info.txt".

## Replicate Result
To replicate the same classification results, please use set.seed(2023) before any random sampling processing code.