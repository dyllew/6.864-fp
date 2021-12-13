# 6.864-fp

## 6.864 Adv. NLP Final Project: 
## Information Extraction and Unsupervised Methods for Streamlining Evidence Synthesis in International Development Grey Literature
#### Authors: Kristen Edwards, Jack Gammack, Luis Kumanduri,  Dylan Lewis

###### Please find the Final Report and Final Presentation of our findings in this [folder.](https://github.com/dyllew/6.864-fp/tree/main/docs)

###### The code for Country of Study Extraction can be found [here.](https://github.com/dyllew/6.864-fp/blob/main/country_NER/country_NER.ipynb)

###### The code for K-Means Clustering and Multidimensional Scaling of the documents in our corpus can be found [here.](https://github.com/dyllew/6.864-fp/blob/main/clustering_MDS/USE%20Embeddings_Heat%20Map.ipynb)

#### Project Description: 
In fields like international development, decision-makers prioritize making evidence-based decisions for funding and implementing future projects. This aim is made difficult because of the plethora of information being published each year, and the nature of the research corpus as unstructured text or grey literature. To make informed decisions and understand the growing corpus of research available, researchers have turned to evidence synthesis - the process of compiling information and knowledge from many sources and disciplines to inform decisions. However, the manual evidence synthesis process takes extensive time (often 18 months to 3 years) and effort, and may soon be impossible at the world’s increasing rate of research output. To address these problems, we employ natural language processing techniques on a international development literature corpus of 244 documents to extract information from the title and abstract of international development documents, and to automatically cluster documents based on their content. We classify documents by Country of Study using a pretrained transformer Named Entity Recognition model and achieve an accuracy of 91.0\%. Using K-Means clustering, we uncover informative and distinctive groupings of the documents which share similar semantic content. These methods reduce the time it takes for manual evidence synthesis for international development grey literature by enabling country of study filtering and clustering documents by semantic similarity.
