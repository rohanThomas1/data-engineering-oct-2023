## Notebook running instructions
Research.ipynb is the file that needs to be executed. To run the below things need to be done before executing on your side:

* Install the libraries, pymongo and networkx using pip install <library_name>
* Assign mongo_url variable with the connection url to your MongoDB server. Since I created a local server, mine is set to "mongodb://localhost:27017/". If your server is on cloud, use the format mongodb+srv://\<username>:\<password>@<cluster_name>.mongodb.net/\<dbname>?retryWrites=true&w=majority
* In the line, db = client["sample"], "sample" is my database name. Hence, change it accordingly with your database name.
* In the line, collection = db["research"], "research" is my collection name. Hence, change it accordingly with your collection name.

## Task 1
1.1 - Export the JSON file to a database including MongoDB, or SQL, or Neo4j

1.2 - Write a Jupyter Notebook that uses the file in the database to calculate the following
* Number of Articles
* Number of Organisations (Deduplicated Affiliations)
* Number of Researchers

## Task 2
2.1 - Calculate the following measures in this data
* Top 10 organisations with the highest degree of centrality
* Top 10 researchers with the highest degree of centrality

## Task 3
3.1 - Visualise the graph in such a way that shows the overall scale of all the graph nodes and relationships, and highlights the major clusters.
