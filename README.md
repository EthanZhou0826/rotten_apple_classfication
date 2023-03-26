#The modified data set contains 5000 apple pictures, including 2000 rotten apples and 2000 fresh apples，Divide training set and test set by 4:1
#Choose ResNet18 for migration learning, and only fine-tune its fully connected layer (last layer), where batch_size is 4 and epoch is 6
#We get a model that is 97% accurate on the test set
