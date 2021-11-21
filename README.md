# individual_speech_classification

# Introduction

This dataset is obtained from two individuals speaking in a natural environment.

# Question
Can you we supervised machine learning algorithms to tell the difference between the two speakers?

The recording is about 146 seconds for one individual and 101 seconds for the other individual. Once the recordings are converted to waveforms, they are cut off into different rows at 10000 hz per row. I will be only using 895 rows from each individual to balance the data.

# Conclusion
After using different machine learning algorithms, Gradient Boosting Classifier performed that best. With hypertuning, the best accuracy scored above 90%.
