# Individual Speech Classification

# Question
Can you we supervised machine learning algorithms to tell the difference between the two speakers?

# Data
This dataset is obtained from two female individuals speaking in a natural environment. The recording is about 623 seconds for one individual and 594 seconds for the other individual. Once the recordings are converted to waveforms, they are cut off into different rows at 10000 hz per row. I will only use 5241 rows from each individual to balance the data.

# Conclusion
After using different machine learning algorithms, Gradient Boosting Classifier performed that best. With hypertuning, the best accuracy scored around 77%.
