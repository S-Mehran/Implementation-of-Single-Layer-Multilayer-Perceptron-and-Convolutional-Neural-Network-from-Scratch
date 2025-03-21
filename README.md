# Implementation-of-Single-Layer-Multilayer-Perceptron-and-Convolutional-Neural-Network-from-Scratch

This study evaluates the performance of three neural network architectures—Single-Layer Perceptron, Multilayer Perceptron (MLP), and Convolutional Neural Network (CNN)—on three benchmark image classification datasets: MNIST, Fashion-MNIST, and CIFAR-10. The objective is to analyze the impact of network complexity on classification accuracy, F1 score, and training time. Experimental results reveal that single-layer perceptrons perform at chance levels across all datasets, demonstrating their inability to learn complex patterns. MLPs significantly improve classification performance for grayscale datasets (MNIST and Fashion-MNIST) but fail to generalize on CIFAR-10 due to the lack of spatial feature extraction. CNNs achieve the highest accuracy and F1 scores across all datasets, leveraging convolutional filters for hierarchical feature learning. However, their training time is significantly higher, particularly when implemented with-out GPU acceleration. Despite its superior performance, the shallow CNN used in this study struggles with CIFAR-10, emphasizing the need for deeper architectures for complex datasets. These findings highlight the trade-offs between model complexity, computational cost, and classification performance, providing insights into selecting appropriate architectures for different image classification tasks.

<figure>
    <img src="https://github.com/S-Mehran/Implementation-of-Single-Layer-Multilayer-Perceptron-and-Convolutional-Neural-Network-from-Scratch/blob/5166a1d50a2727e342cc33c545f09e490a85cbec/Multilayer%20Perceptron%20Architecture.png">
    <figcaption>Figure 1: Multilayer Perceptron Architecture</figcaption>
</figure>

<figure>
    <img src="https://github.com/S-Mehran/Implementation-of-Single-Layer-Multilayer-Perceptron-and-Convolutional-Neural-Network-from-Scratch/blob/c742d58d14016d1b74cfb0d615627de2bd9924df/CNN%20simple%20architecture.png">
    <figcaption>Figure 2: Simple Convolutional Neural Network Architecture</figcaption>
</figure>


<figure>
    <img src="https://github.com/S-Mehran/Implementation-of-Single-Layer-Multilayer-Perceptron-and-Convolutional-Neural-Network-from-Scratch/blob/d74e97cfc75796831b090b2eac38e402dfb994b2/Results.png">
    <figcaption>Figure 3: Results on Different Datasets</figcaption>
</figure>
