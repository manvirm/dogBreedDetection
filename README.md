# Dog Breed Detection
1. Correctly identify which pet images are of dogs (even if the breed is misclassified) and which pet images aren't of dogs.  
2. Correctly classify the breed of dog, for the images that are of dogs.  
3. Determine which CNN model architecture (ResNet, AlexNet, or VGG), "best" achieve objectives 1 and 2.  
4. Consider the time resources required to best achieve objectives 1 and 2, and determine if an alternative solution would have given a "good enough" result, given the amount of time each of the algorithms takes to run.

Results:
The "best" model architecture is VGG. 
It outperformed both of the other architectures when considering both objectives 1 and 2.
ResNet did classify dog breeds better than AlexNet, but only VGG and AlexNet were able to classify "dogs" and "not-a-dog" at 100% accuracy. 
The model VGG was the one that was able to classify "dogs" and "not-a-dog" with 100% accuracy and had the best performance regarding breed classification with 93.3% accuracy.
