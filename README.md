                                                        Netflix Movies And Tv Shows Clustering

                                                            Prject Type-Unsupervised ML

 *Project Summary -

 The aim of this project is to analyze the Netflix Dataset of movies and TV shows until 2019, sourced from the third-party search engine Flixable. The goal is to group the content into relevant clusters using NLP techniques to improve the user experience through a recommendation system. This will help prevent subscriber churn for Netflix, which currently has over 220 million subscribers.

 Additionally, the dataset will be analyzed to uncover insights and trends in the streaming entertainment industry.

**The project followed a step-by-step process:**

1. **Handling null values** in the dataset.
2. Managing nested columns **(director, cast, listed_in, country)** for better visualization.
3. Binning the rating attribute into categories **(adult, children's, family-friendly, not rated).**
4. Performing **Exploratory Data Analysis (EDA)** to gain insights for preventing subscriber churn.
5. Creating clusters using attributes like **director, cast, country, genre, rating, and description.** These attributes were **tokenized, preprocessed, and vectorized** using **TF-IDF vectorizer.**
6. Reducing the dimensionality of the dataset using **PCA** to improve performance.
7. Employing **K-Means Clustering and Agglomerative Hierarchical Clustering** algorithms, determining optimal cluster numbers (4 for K-Means, 2 for hierarchical clustering) through various evaluation methods.
8. Developing a **content-based recommender system** using cosine similarity matrix to provide personalized recommendations to users and reduce subscriber churn for Netflix. \

**This comprehensive analysis and recommendation system are expected to enhance user satisfaction, leading to improved retention rates for Netflix.**




