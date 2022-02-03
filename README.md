# CORDFigureSearch
* The aim of the project was to build a specialized search engine to retrieve tables and figures from ETDs in the CORD domain.
* We used AllenAI pdf2figures tool to extract tables and figures and used the generated JSON data to bulk index over Elastic Search. The final Django based UI had various marker driven search functionalities to cover all possible use cases.

