# Assignment Materials

This folder contains the materials required for the **URBAN5160 – Graph Modelling and Spatially Explicit GeoAI for Urban Analytics** assignment.

Please refer to **`Assignment Brief.pdf`** for the full description of the task, requirements, and submission guidelines.

## Dataset

The file **`AssignmentData-LondonPM25Prediction.geojson`** contains the spatial dataset used for the assignment. The dataset combines urban features derived from census statistics with environmental data for a **PM2.5 prediction task**.

The input features are derived from the **2011 London Output Area Classification (OAC)** dataset, provided through the Geographic Data Service:

https://data.geods.ac.uk/dataset/london-oac-2011

To help you understand the **semantic meaning of the input features**, the file **`Attribute_Overview_Report.pdf`** is included. This document is derived from the 2011 London Output Area Classification project's [final report](https://data.geods.ac.uk/dataset/london-oac-2011) and provides descriptions of the census-based variables.

The **PM2.5 data** used as the prediction target is obtained from the **Greater London Authority (GLA)** and can be accessed at:

https://data.london.gov.uk/dataset/pm25-map-and-exposure-data-29z1y/

Students should use this dataset to construct a **spatial graph and implement a Graph Neural Network model** as described in the assignment brief.
