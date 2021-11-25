# Individual Speech Classification

# Question
Can you we supervised machine learning algorithms to tell the difference between the two speakers? Two female speakers? One male speaker and the other a female speaker?

# Data
The first dataset is obtained from two female individuals speaking in a natural environment. The recording is about 623 seconds for one individual and 594 seconds for the other individual. Once the recordings are converted to waveforms, they are cut off into different rows at 10000 hz per row. I will only use 5241 rows from each individual to balance the data.

The second data set is obtained from one male individual and one female individual. The recording is about 59 seconds for the male individual and 101 seconds for the female individual. Rows are cut off at 10000 hz. I will only use 528 rows from each individual to blance the data.

# Conclusion
After using different machine learning algorithms, Gradient Boosting Classifier performed that best. With hypertuning, the best accuracy scored around 77%.

For the second dataset, Gradient Boosting Classifier still outperformed the other machine learning algorithms. With hypertuning, the best accuracy scored around 97%.

Even with less data, the difference between the male and female speech was enough to build a higher accuracy model than the dataset with only female speeches although that dataset was larger.
