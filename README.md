# Simple Search Engine Project  
In this project, we want to create a search engine for retrieving text documents in such a way that the user enters his query and the system displays the related documents. For a more complete description of the project in Farsi, refer to [Project explanation](https://github.com/Mahdi-Rahmani/Search-Engine/tree/main/Project%20explanation).

## Phase 1  
In this phase of the project, in order to create a simple information retrieval model, it is necessary to index the documents so that when the query is received, the positional index can be used to retrieve related documents. In short, the things to be done in this phase are as follows:  
- Data preprocessing 
- Creating a positional index 
- Answering the user's queries 

The jupyter notebook file is located at [Phase 1](https://github.com/Mahdi-Rahmani/Search-Engine/blob/main/Phase%201/IR_Phase1.ipynb) 
 
## Phase 2 
At this stage, we want to expand the information retrieval model and represent the documents in vector form so that we can rank the search results based on their relationship with the user's query. In this way, a numerical vector is extracted for each document, which is the representation of that document in the vector space, and these vectors are stored. At the time of receiving a query, first the vector corresponding to that query is created in the same vector space and then using a suitable similarity criterion, the similarity of the numerical vector of the query with the vector of all documents in the vector space is calculated and finally the output results are sorted based on the amount similarity.  
To increase the response speed of the information retrieval model, various methods can be used, which are described in details in project explanation file. 
 
The jupyter notebook file is located at [Phase 2](https://github.com/Mahdi-Rahmani/Search-Engine/blob/main/Phase%202/IR_Phase2.ipynb) 

## Notes 
- We use two important libraries in this porject. you can click on them for more information: 
  - [parsivar](https://github.com/ICTRC/Parsivar) 
  - [hazm](https://github.com/roshan-research/hazm) 
- If you want to read more about the topics discussed in this course, you can refer to [Course slides](https://github.com/Mahdi-Rahmani/Search-Engine/tree/main/Course%20slides).
