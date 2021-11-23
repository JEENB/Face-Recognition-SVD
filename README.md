# Facial Recognition System using Singular Value Decomposition (SVD)

Classifier Accuracy: 81%
--------------------------------------------------------------------------------------------------------------------

### Brief Summary:

1. A matrix of test images and training images were obtained.
![alt text](https://github.com/JEENB/IML_eigenfaces_assignment/blob/master/Results/unique_face.png "Random Testing and Training Images")

2. Both the matrices were normalized by subtracting the mean.   
![alt text](https://github.com/JEENB/IML_eigenfaces_assignment/blob/master/Results/meanface.png "Mean Face")

4. The training images were decomposed using the SVD into eigenfaces(eignevectors).  
![alt text](https://github.com/JEENB/IML_eigenfaces_assignment/blob/master/Results/eigenfaces.png "EigenFaces")


6. Adequate number of principle components(k) were determined amongst the largest eigenvalues.  
7. Each training image was then represented as a linear combination of the k-eigenfaces (eigenvectors).  
8. The testing images were then projected on the the eigenspace and the minimum distance of the testing image with a training image.   
9. The least distant image was recognized and compared with the correct label(f(x)).  
10. If h(x) = f(x), then a correct face was recognized.  
