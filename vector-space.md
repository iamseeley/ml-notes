## vector space

### what's a vector?
- a vector is an ordered list of numbers, where each number represents a feature or attribute of the data

- in a vector space, each data instance is represented as a point or a vector, with its position determined by the values of its features

- the number of features determines the dimensionality of the vector space. if each data instance has three features, the vector space would be a 3d space

- the vector space provides a structured way to represent and analyze data, enabling mathematical operations and comparisons between data points

### vector space purposes in ml
- **feature representation**: each feature of the data is represented as a dimension in the vector space, allowing the model to learn patterns and relationships based on the feature values

- **similarity and distance measures**: vector spaces allow the calculation of similarity or distance between data points using metrics such as euclidean distance, cosine similarity, or manhattan distance. this is useful for tasks like clustering, nearest neighbor search, or anomaly detection

- **model training and optimization**: many ml algorithms, such as support vector machines (svm) or neural networks, operate in vector spaces. they learn decision boundaries, optimize parameters, or transform the vector space to find the best representation for the given task 

- **dimensionality reduction**: vector spaces can be transformed or reduced to lower-dimensional spaces while preserving important properties of the data

- **embedding spaces**: in some cases, data that is not naturally represented as vectors, such as text or images, can be mapped to a vector space through embedding techniques. this allows the application of vector-based operations and analysis on non-vector data

**Vector spaces provide a foundation for representing and manipulating data in machine learning, enabling various algorithms and techniques to learn patterns, make predictions, and extract insights from the data.**
