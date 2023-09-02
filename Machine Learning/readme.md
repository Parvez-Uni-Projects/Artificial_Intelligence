# Machine Learning Notes


## Areas of machine Learning

Machine learning is a subset of AI. Deep learning is a subset of machine learning.
Biology Inspired Algorithms is a subset of Ai which needs some part from both Deep learning and Machine learning.
Search Algorithms is a subset of Ai which isb't strictly related to machine learning.

In machine learning, we have three main areas:

Machine Learning 
- Supervised Learning
    - Classification
        - Naive Bayes Classifier
        - Decision Tree
        - Support vector machine
        - K-Nearest Neighbors
        - Random Forest

    - Regression
        - Linear Regression
        - Neural Network Regression
        - Support Vector Regression
        - Decision Tree Regression
        - Laso Regression
        - Ridge Regression


- Unsupervised Learning
    - K-Means Clustering
    - Mean Shift Clustering
    - DBSCAN Clustering
    - Agglomerative  hierarchical Clustering
    - Gaussian Mixture 
- Reinforcement Learning
    - Q-Learning
    - R Learning
    - TD Learning

Draw a ven diagram of the above 

```mermaid
graph LR
A[Machine Learning] --> B[Supervised Learning]
A --> C[Unsupervised Learning]
A --> D[Reinforcement Learning]

B --> E[Classification]
B --> F[Regression]

E --> G[Naive Bayes Classifier]
E --> H[Decision Tree]
E --> I[Support vector machine]
E --> J[K-Nearest Neighbors]
E --> K[Random Forest]

F --> L[Linear Regression]
F --> M[Neural Network Regression]
F --> N[Support Vector Regression]
F --> O[Decision Tree Regression]
F --> P[Laso Regression]
F --> Q[Ridge Regression]

C --> R[K-Means Clustering]
C --> S[Mean Shift Clustering]
C --> T[DBSCAN Clustering]
C --> U[Agglomerative  hierarchical Clustering]
C --> V[Gaussian Mixture]

D --> W[Q-Learning]
D --> X[R Learning]
D --> Y[TD Learning]


```