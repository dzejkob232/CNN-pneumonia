a convolutional neural network for detecting pneumonia in patients' lungs from X-ray photos.
dataset sizes: test: 624, train: 4900, val: 532
It achieved a 72% test accuracy.
of that, 3 are false negatoves and 173 are false positives.
I intentionally biased against false negatives for practical reasons - leaving a sick patient untreated is worse than redundantly treating a healthy one

.jpeg rentgens are converted into 128x128 grayscale images, and into tensors

training data from https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia/data
