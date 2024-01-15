# JavaScript-AI-Course-no-Python-MongooseJS-Astra-DB

https://www.youtube.com/watch?v=5ZLmcDi30YI&t=68s 

https://raw.githubusercontent.com/RodrigoMvs123/JavaScript-AI-Course-no-Python-MongooseJS-Astra-DB/main/README.md

https://github.com/RodrigoMvs123/JavaScript-AI-Course-no-Python-MongooseJS-Astra-DB/blame/main/README.md

Introduction
Course Outline
The Vector Search Database
What is a Vector Embedding ?
MongooseJS
The AstraDB API
Let´s build an AI Chatbot !
Astra DB API via HTTP
Recap

The Vector Search Database
https://www.datastax.com/ 
Databases
Create Database
Database Name
movie_db
Keyspace Name
movies
Provider
Google Cloud
Region
us-east-1
Create Database

Vector Embeddings
Vector Embedding is a popular technique used to represent information like text, images, videos and even sound into a format that algorithms can understand especially those used by deep learning models.
World/Text Embeddings
Document Embeddings
Sentence Embeddings
Graph Embeddings
Image Embeddings

Embeddings
https://platform.openai.com/docs/guides/embeddings 

MongooseJS
MongooseJS essentially provides us a schema-based solution to model our data 

Astra DB API

Github Repository 
https://github.com/datastax/create-astradb-mongoose-app 

Datastax API Token 
Databases
Connect
Generate Database Token 
Application Token Detail
{
  "clientId": "KGwAluvcbZsscIJZphpZalFb",
  "secret": "I-kl4vC3KjvL.FvZnoxRfIoQhwc85.SYoNL-LIWbzBKbcvjrc6YAxZbi-AeyRm7.U.AsS.lx_I8wn7E3oCQGke048XC13Dl,6Za-9c,unAbjJcD-4WDGBjmbklZevd9L",
  "token": "AstraCS:KGwAluvcbZsscIJZphpZalFb:2973eb0f67e56108b9427e02f5ed651d708c8e59e72f5414e65869562d755462"
} 
Connect with the JSON API 
Terminal
npm install -g npx
Generate Configuration 
Configuration Details
export ASTRA_DB_ID=93bc59c6-bea6-49e9-9127-6318c35d6769
export ASTRA_DB_REGION=us-east1
export ASTRA_DB_KEYSPACE=movies
export ASTRA_DB_APPLICATION_TOKEN=AstraCS:GgAwPxQbvOmILULEIQZSAzpe:6d7445de220e891e8a43e77c594f06646170f8806ee6e09f48cdd97dc8718d63
Download and install a current Node.js LTS version with npm
Run the “npx” command to install
Terminal
npx create-astradb-mongoose-app@latest
Ok to proceed ? (y) y 
What is  your Data API endpoint ? 
https://93bc59c6-bea6-49e9-9127-6318c35d6769-us-east1.apps.astra.datastax.com
https://$ASTRA_DB_ID-$ASTRA_DB_REGION.apps.astra.datastax.com/api/rest/v2/namespaces/$ASTRA_DB_KEYSPACE/collections/products/botblaster \ 
What is your Astra DB application Token ? 
AstraCS:GgAwPxQbvOmILULEIQZSAzpe:6d7445de220e891e8a43e77c594f06646170f8806ee6e09f48cdd97dc8718d63
Where is your downloaded JSON API application configuration file located ?
Do you wanto to enable vector search functionality ? yes
Awesome ! What is your Open AI API Key ? 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
cd astradb-mongoose-app
npm start

Astras DB API via HTTP
https://93bc59c6-bea6-49e9-9127-6318c35d6769-us-east1.apps.astra.datastax.com







