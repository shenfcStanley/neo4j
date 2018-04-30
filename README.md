# neo4j
Neo4j

1. Connect to server:

a. http://localhost:7474/browser/
b. host name: bolt://localhost:7687
c. username, password

2. retrieve the whole graph

START n=node(*) RETURN n;

3. delete nodes

START n=node(*), r=rel(*) DELETE r, n
