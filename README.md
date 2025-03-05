This code demonstrates the use of Active Learning (DeepAL) strategies (Uncertainty, Margin, and Entropy Sampling) for training machine learning models on different datasets. Specifically, the code applies these strategies to three datasets: MNIST, CIFAR-10, and IMDB. The goal is to improve model performance by selectively querying which samples to label based on the model's uncertainty.

The models are evaluated and retrained multiple times (iterations) with a growing labeled dataset.

Three active learning strategies (Uncertainty, Margin, Entropy) are compared.

Results for MNIST, CIFAR-10, and IMDB datasets are stored and printed.
