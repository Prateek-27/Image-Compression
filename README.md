# K-Means Clustering for Image Compression

## Introduction
This project demonstrates the implementation of the K-Means Clustering algorithm from scratch and its application in image compression. K-Means Clustering is a widely used technique in unsupervised learning, and here, I leverage it to reduce the number of colors in an image, effectively compressing the image size without significantly compromising the visual integrity of the image.

## Implementation Details
- **Language & Libraries**: The entire algorithm is implemented in Python using numpy without the use of high-level libraries such as scikit-learn for the K-Means part, ensuring a deeper understanding of the inner workings of the algorithm.
- **Algorithm**: The custom implementation of the K-Means Clustering algorithm iteratively assigns pixels to the nearest cluster and updates the centroids until convergence.

## Results & Discussion
I applied the K-Means Clustering implementation for image compression on a sample image. The results demonstrate the effectiveness of the algorithm in significantly reducing the image size while maintaining an acceptable level of visual quality.

### Original vs Compressed Image Comparison
Below is a comparison between the original and the compressed image along with the details of the size change and compression ratio.

#### Original Image:
- **File Name**: `Original.png`
- **Size**: `819` KB

![Original Image](img1.png)

#### Compressed Image:
- **File Name**: `Compressed.png`
- **Size**: `160` KB
- **Compression Ratio**: `80.46%`

![Compressed Image](res.png)

### Observations
- **Color Reduction**: The compressed image retains the essential color profiles and visual content with a significantly reduced color palette.
- **Size Reduction**: There's a notable reduction in image size, showcasing the efficiency of K-Means Clustering in image compression.
- **Quality**: While there is some loss in detail due to color reduction, the overall visual quality remains satisfactory for many applications.

## Conclusion
This project showcases a practical application of K-Means Clustering in the domain of image compression. By implementing the algorithm from scratch, I gain valuable insights into its mechanics and potential for various applications. The results affirm that K-Means can be an effective tool for image compression, balancing size reduction with visual quality.

## References
Unsupervised Learning, Recommenders, Reinforcement Learning by DeepLearning.AI
