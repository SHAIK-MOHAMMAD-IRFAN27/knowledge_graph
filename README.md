# Knowledge Graph-Powered Movie Recommendation System with LLM Integration
"Developed and implemented a Knowledge Graph-powered platform for movie data, transforming raw tabular information into a semantically rich network using Neo4j. Designed and populated a graph schema connecting Movies, Persons (Actors/Directors), Characters, Genres, and Keywords, enabling complex relationship-based insights. Integrated an OpenAI Large Language Model (LLM) via LangChain's GraphCypherQAChain to facilitate natural language querying, allowing users to ask intricate questions (e.g., 'What comedy movies star Tom Hanks?') which are converted to Cypher, executed on the graph, and returned as human-readable answers. Deployed functionality as a scalable FastAPI web service, enhancing content recommendation capabilities through deep contextual understanding and intuitive access to interconnected data."

### HOW TO LOGIN TO THE NEO4J:
- Search for neo4j auradb in goole and click on it.
- Signup and create a free instance . U will be automaticlly saving a file with credentials and URI.


## Key Achievements to Highlight :

- Designed and implemented a comprehensive Neo4j Knowledge Graph schema for movie entities and their relationships.
- Developed robust Python ingestion scripts (using Pandas and parameterized Cypher queries) to transform and load unstructured/semi-structured movie metadata into the graph.
-Integrated an OpenAI LLM with LangChain to enable natural language-to-Cypher query translation for intuitive data exploration.
- Created a scalable FastAPI service to expose the natural language querying capabilities as a web API for potential recommendation applications.
- Improved data understanding and query complexity compared to traditional tabular methods, laying the groundwork for advanced content recommendation

## THIS WAS MY KNOWLEDGE GRAPH AT THE BEGINNING STAGE:

![visualisation (4)](https://github.com/user-attachments/assets/b8543833-ee5b-45e3-b757-4dd0294bd56c)
 

![visualisation (6)](https://github.com/user-attachments/assets/62486b86-a542-461d-bbe3-16d455a7cec0)


