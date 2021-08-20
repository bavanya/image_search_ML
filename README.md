# image_search_ML

**Objective**
The objective of the project is to build a prototype of the image search feature.

**Dataset Overview**

In the dataset, each image is named with it's id as jpg extension, and description and other important tags of the image are provided in a csv file. 
Due to the size restriction, only selective images are uploaded to the respository.

**Version-1**:

Work done in the Version-1 of the prototype in model.ipynb notebook is:
1. Sentence embeddings are obtained for the descriptions to the images.
2. A search query is taken as an input and sentence embeeding of the query is obtained.
3. Cosine distance is obtained between the query_embeeding and the embeedings of the image descriptions.
4. Number of Results to display is asked.
5. The images with the descriptions closest to the requested query are displayed. The similarity is measured using cosine distance.

***Future Work***

**Version-2:**

Plan is to generate an entry to the annotations.csv file when a new image is added to the dataset.
For this, a model should be built using the existing data which can be used to generate tags and description to a new image.

**Version-3:**

Plan is to add a new feature where similar image results will be displayed whenever an image is provided for search.
This can be done by generating description and tags of the query image and checking the similarity with the descriptions and tags of the images in the database. 
