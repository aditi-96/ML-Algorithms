# KMeans
- Used `Fashion-MNIST` dataset
- Split data into train and validation sets
- Implemented Kmeans algorithm
- Found optimal clusters using elbow and silhouette method
- Defined initial cluster centers using 2 methods:
> i) Forgy</br>
> ii) Random Partition
- Experimented with different distance measures (Euclidean and manhattan)
- Visualised dataset using TSNE
- Implemented Kmeans++
- Perform operations on `[latentFashionMNIST.csv](https://drive.google.com/file/d/188OjH7rR6cacr3qFeSwhBikV8Asqbhp4/view?usp=sharing)`, which is a latent space representation of Fashion-MNIST


# Logistic Regression
- Used `[Sign Language Dataset](https://drive.google.com/file/d/1s4VwGTmzwRqeu5jZSf5AsYkNFzrgkbFv/view?usp=sharing)`
- Implemented one-vs-one and one-vs-rest logistic regression to classify the sign language numbers in 0-9
- The accuracies of all the models is as below:
    - Self-implemented ovo: 0.78
    - Self-implemented ovr: 0.68
    - Sklearn ovo: 0.82
    - Sklearn ovr: 0.78