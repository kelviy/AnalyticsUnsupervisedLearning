# Analytics Unsupervised Learning Assignment

Assignment submission for the Analytics Honours Course at UCT. The write-up report can be viewed as a PDF document in this repository. The code is contained in the RMarkdown document.

# Summary
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


# Authors:
- Kelvin Wei (Exploratory Data Analysis and SOM Clustering)
- Chidiebere Umah (Hierarchical and Non-Hierarchical Clustering)
