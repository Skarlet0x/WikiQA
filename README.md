# Wiki_QA
A simple ElasticSearch Pipeline utilizing Wikipedia's API for interactive Question Answering.

## ARCHITECTURE

- BERT-based Retriever-Reader model 
- Wikipedia API - fetches a wiki page which serves as a source of information for the ES model

## USAGE
- the user is prompted to input a topic and a question related to that topic
- if Wikipedia contains a page corresponding to the chosen topic, it is passed on to the QA model and the user is presented with the most probable answer based on the information written on that page

