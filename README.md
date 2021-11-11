# AISAFE_HOMEWORK
this is my AISAFE homework repository
<br>
LENET about CIFAR10

## Tuning a hyper-parameter

+ batch_size: tun batch_size from 4 to 128 ,the iteration speed of the model becomes faster and the GPU utilization is improved
+ lr(learning rate):   
   + when use 0.1，the gradient drops too fast and the accuracy fluctuates
   + when use 0.001,gradient and accuracy decreased steadily
