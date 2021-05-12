###Initial experiment - Table 1
```
experiment1(model, dataset, images_per_class,  iterations, network_steps):
#--model: CNN
#--dataset: MNIST, FashionMNIST, SVHN, CIFAR10
#--images_per_class: 1, 10
#--iterations: 1000
#--network_steps: 1 (for 1 ipc), 50 (for 10 ipc)
```

###Cross-architecture experiment - Table 2
```
experiment2(model, dataset, images_per_class,  iterations, network_steps):
#--model: MLP, LeNet, CNN, AlexNet
#--dataset: MNIST
#--images_per_class: 1
#--iterations: 1000
#--network_steps: 1
```
