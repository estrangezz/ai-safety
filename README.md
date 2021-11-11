# ai-safety
# Train CIFAR10 with PyTorch

# Start training with: 
python main.py

# model
I used a model which has three cnn layers and each has a batchnorm layer,RELU layer and maxpooling layer.
after that,there are two fc layers and each has a RELU layer.finally I used a fc layer to get a 10-dim vector.

# parameters
epoch  100
optimizer  SGD
learning rate  0.01
momentum  0.9
weight decay  5e-4

# performance
accuracy  87.66%

# analyse
after 55 epoches,the validation accuracy has reached 87%.So the model trained so slowly in almost half of the epoches.
I think if I make the model a little deeper or just increase the learning rate will make the training better. 
