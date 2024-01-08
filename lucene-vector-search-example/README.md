# Lucene Wikipedia Example

In this example, OpenAI's Wikipedia corpus (25k documents) are indexed along with title and content vectors. A sample query (query.txt) is executed after the indexing.

## Steps

    wget https://cdn.openai.com/API/examples/data/vector_database_wikipedia_articles_embedded.zip
    mvn package
    java -jar target/lucene-vector-search-example-0.0.1-SNAPSHOT.jar

