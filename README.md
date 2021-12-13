# Ontology based Literature Mining and Indexing of Leukemia

# Introduction

The development of most types of leukemia increases with age, also different types of leukemia have different types of risk factors involved. In this project we have discussed the problem of finding the right research paper for a particular topic. Our topic is Leukemia and its subtypes(AML,ALL,CML,CLL). When we were trying to find articles related to leukemia there were many other papers being displayed in the search result. For the dataset we have downloaded abstracts for each type of leukemia and converted the TXT format files into XML format with help of Mendeley and structured our own dataset. Our aim here is to develop a model that automatically classifies the abstracts of the literature into one of the leukemia related categories using machine learning method when they are entered. Such a model would allow people to search the literature more efficiently and improve the accuracy of the search.

# Authors
Ziyuan Xu, Shijie Zhou, Minakshi

# Dataset

We’ve downloaded 50 abstracts of literature on each subtype of leukemia(AML, ALL, CML, CLL) from PubMed respectively and acquired a total of 200 TXT format files. These texts are unstructured natural language texts, so we need to structure and classify them. In this project, we are using Mendeley to convert these texts into XML format files. Then, in order to build our own dataset, we extracted some important attributes from these XML files: authors, title, year, electronic-resource-num, periodical, abstract. These attributes will be used as column names. Additionally, we added an attribute to the column name, namely paper_id. 

# Screenshot 

![Capture](https://user-images.githubusercontent.com/96027933/145858538-d39d3006-c4b1-461e-829f-8a5b0d1f4c46.PNG)

  
# Steps to run code

First download Python

Go to your browser-> type python-> Download latest version from www.python.org/downloads/ -> Install it on your machine

To check if python is installed on machine-> type cmd on window search-> type py and enter-> it will show the result

Again go to your browser-> type anaconda-> Download anaconda individual edition from www.anaconda.com/products/individual -> Install it on your machine

To check if anaconda is installed on machine-> type anaconda on window search-> open anaconda navigator

pip install tensorflow and jupyter notebook in Anoconda prompt 

Activate tensorflow then open jupyter notebook -> upload the project file and run


