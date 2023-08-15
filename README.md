# Network Analysis and Prediction for Terrorism Dataset
The following project involves Network Analysis and Prediction on the Terrorism Dataset. The focus of the project is to apply various Network Analysis Tools including Centrality Analysis, Degree Distirbutions, Density Analysis and Link Prediction to the Terrorism Dataset. The steps are as follows:

1. **Data Preprocessing and Visaulisation in Gephi**
    - The raw data collected was very dirty and not in the correct format for visualisations to be conductd using networkx and Gephi.
    - Thus, many preprocessing steps were applied in Python, the code for which has also been attached.
    - Once, data was prepared, it was visualised in Gephi, 2 seperate visualisations were created, one which is on the international terrorism network and one which operates in Afghanistan.

2. **Metrics Calculations as follows:**
    - Various Metrics were utilised to figure out additional details about the dataset, some of which are as follows:
    - Frequency and Degree Analysis - To figure out organizations attacking more ocuntries and countries being attacked the most.
    - Degree Distribution Analysis - to check whether any probability distirbution is able to fit the data.
    - Weighted Degree analysis to further investigate terrorist organizations and frequency with which they attack countries.
    - Graph density analysis - to check if the graph is sparse or not and if small world property exists in it or not.

3. **Centrality Analysis**
    - Once initial metrics were calculated, centrality of the graph was calculated using various metrics to find out most influential nodes in the graph.
    - The algorithms utilised for this include, Betweenness Centrality, Eigenvector cnetrality and Closeness centrality.
    - These algorithms helped to understand most important nodes in both the graphs.

4. **Link Prediction**
    - Link prediction was also conducted using Node2Vec embeddings for our data.
    - However, due to limited computing resources, we were unable to train many models and could only apply Node2Vec and Random Forests.
