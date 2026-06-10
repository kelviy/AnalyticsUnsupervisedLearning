# Analytics Cape Town Airbnb Assignments

Supervised Learning and Unsupervised Learning assignments submission for the Analytics Honours Course at UCT. The respective write-up reports can be viewed as a PDF document in this repository. The code is contained in the RMarkdown / Qmd document.

# Unsupervised Learning

We applied unsupervised clustering techniques on Cape Town Airbnb data to gain insights into the guest experience across various property listings. We found that the guest experience is largely positive, except for a minority group of properties.

Findings from the SOM clustering results:
- **Cluster 1: Poor Reviewed Properties.**
The properties in this cluster are categorised by their low reviews. They are commonly low in price and physical
capacity. However, there is a node that indicates properties with high capacity and price with low reviews are
also grouped here.

- **Cluster 2: Affordable Properties.**
The properties in this cluster are categorised by their affordable prices and average physical capacity. They have
average review quality and volume. Most of the property listings are in this category. The properties in this
cluster tend to occur all over Cape Town.

- **Cluster 3: Luxury Properties.**
The properties in this cluster are categorised by their high prices, physical capacity and high reviews. The
high price results in not many people staying at the property and leaving a review, hence having a very
small volume of reviews. The properties in this cluster tend to be present near the mountains and the
coastline.

- **Cluster 4: Credible Properties.**
The properties in this cluster are categorised by their high volumes of high reviews. They are low in price and
physical capacity. However, it seems that guests enjoy their stay at the Airbnb. Properties in this cluster 
tend to be present in dense areas with other property listing clusters. This cluster appears to be properties
that are a good bargain for their price.



<img width="1192" height="1260" alt="som_geomap" src="https://github.com/user-attachments/assets/37ca2e6b-d38f-41bd-ad12-bf61ff723361" />


## Authors:
- Kelvin Wei (Exploratory Data Analysis and SOM Clustering)
- Chidiebere Umah (Hierarchical and Non-Hierarchical Clustering)

# Supervised Learning

We applied supervised learning algorithms (Elastic Net, Random Forest, Gradient Boosting Models and K-Nearest Neighbours) to predict if an Airbnb property listing would be expensive (HighPrice). The Gradient Boosting Model has been found to perform best at predicting expensive property listings. By analysing our Gradient Boosting Model, we found that influential features for our task to be features that relate to the location and physical capacity of the properties.

<img width="1604" height="1074" alt="image" src="https://github.com/user-attachments/assets/51d73f6a-ecbf-4357-be70-9d3e14b9aeee" />

<img width="1600" height="972" alt="image" src="https://github.com/user-attachments/assets/b0007a77-ca81-49f8-8e9c-2bf718ce7297" />

## Authors:
- Kelvin Wei 
- Unnati Shankar
