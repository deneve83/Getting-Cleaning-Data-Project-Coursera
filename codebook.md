---
title: "Codebook"
output: html_document
---

```{r setup, include=FALSE}
knitr::opts_chunk$set(echo = TRUE)
```

## R Markdown
# Code Book

#This book summarizes the resulting data fields in `tidy.txt`.

## Identifiers

* `subject` - The ID of the test subject
* `activity` - The type of activity performed when the corresponding measurements were taken

## Measurements

* `tBodyAccMeanX`
* `tBodyAccMeanY`
* `tBodyAccMeanZ`
* `tBodyAccStdX`
* `tBodyAccStdY`
* `tBodyAccStdZ`
* `tGravityAccMeanX`
* `tGravityAccMeanY`
* `tGravityAccMeanZ`
* `tGravityAccStdX`
* `tGravityAccStdY`
* `tGravityAccStdZ`
* `tBodyAccJerkMeanX`
* `tBodyAccJerkMeanY`
* `tBodyAccJerkMeanZ`
* `tBodyAccJerkStdX`
* `tBodyAccJerkStdY`
* `tBodyAccJerkStdZ`
* `tBodyGyroMeanX`
* `tBodyGyroMeanY`
* `tBodyGyroMeanZ`
* `tBodyGyroStdX`
* `tBodyGyroStdY`
* `tBodyGyroStdZ`
* `tBodyGyroJerkMeanX`
* `tBodyGyroJerkMeanY`
* `tBodyGyroJerkMeanZ`
* `tBodyGyroJerkStdX`
* `tBodyGyroJerkStdY`
* `tBodyGyroJerkStdZ`
* `tBodyAccMagMean`
* `tBodyAccMagStd`
* `tGravityAccMagMean`
* `tGravityAccMagStd`
* `tBodyAccJerkMagMean`
* `tBodyAccJerkMagStd`
* `tBodyGyroMagMean`
* `tBodyGyroMagStd`
* `tBodyGyroJerkMagMean`
* `tBodyGyroJerkMagStd`
* `fBodyAccMeanX`
* `fBodyAccMeanY`
* `fBodyAccMeanZ`
* `fBodyAccStdX`
* `fBodyAccStdY`
* `fBodyAccStdZ`
* `fBodyAccMeanFreqX`
* `fBodyAccMeanFreqY`
* `fBodyAccMeanFreqZ`
* `fBodyAccJerkMeanX`
* `fBodyAccJerkMeanY`
* `fBodyAccJerkMeanZ`
* `fBodyAccJerkStdX`
* `fBodyAccJerkStdY`
* `fBodyAccJerkStdZ`
* `fBodyAccJerkMeanFreqX`
* `fBodyAccJerkMeanFreqY`
* `fBodyAccJerkMeanFreqZ`
* `fBodyGyroMeanX`
* `fBodyGyroMeanY`
* `fBodyGyroMeanZ`
* `fBodyGyroStdX`
* `fBodyGyroStdY`
* `fBodyGyroStdZ`
* `fBodyGyroMeanFreqX`
* `fBodyGyroMeanFreqY`
* `fBodyGyroMeanFreqZ`
* `fBodyAccMagMean`
* `fBodyAccMagStd`
* `fBodyAccMagMeanFreq`
* `fBodyBodyAccJerkMagMean`
* `fBodyBodyAccJerkMagStd`
* `fBodyBodyAccJerkMagMeanFreq`
* `fBodyBodyGyroMagMean`
* `fBodyBodyGyroMagStd`
* `fBodyBodyGyroMagMeanFreq`
* `fBodyBodyGyroJerkMagMean`
* `fBodyBodyGyroJerkMagStd`
* `fBodyBodyGyroJerkMagMeanFreq`

## Activity Labels

* `WALKING` (value `1`): The subject was walking during the test
* `WALKING_UPSTAIRS` (value `2`): The subject was walking up a staircase during the test
* `WALKING_DOWNSTAIRS` (value `3`): The subject was walking down a staircase during the test
* `SITTING` (value `4`): The subject was sitting during the test
* `STANDING` (value `5`): The subject was standing during the test
* `LAYING` (value `6`): The subject was laying down during the test