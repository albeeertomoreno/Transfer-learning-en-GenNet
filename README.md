# Transfer-learning-en-GenNet
This repository is a brief summary of my master's thesis 'Predicting Alzheimer's disease conversion in Mild Cognitive Impairment patients: A transfer learning approach with explainable AI'.  It is not the whole work but a part of it that may be useful for future research that my thesis director may carry out.

The train file is a copy of the original GenNet repository file with the following changes:
- Allow to work on CPU
- Allow to do transfer learning without the train_log.csv file
-Allow transferring layer by layer

The function file is used to extend, among other things, the subject file required for GenNet to work, where the data partition must be indicated. Its use is visible in the example file get_subject_all_cohorts.

The transfer learning file is the main purpose of this repository which serves as a starting point for future transfer learning of the weight file of any trained prior model.
