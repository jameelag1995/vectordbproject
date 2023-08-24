**Vector db**

Some information is unstructured — like text documents, media and audio — and some is structured — like application logs, tables, and graphs. Innovations in artificial intelligence and machine learning have allowed us to create a type of ML model — embedding models. Embeddings encode all types of data into vectors that capture the meaning and context of an asset. This allows us to find similar assets by searching for neighboring data points. Vector search methods allow taking a photograph with your smartphone and searching for similar images. 

Vector databases provide the ability to store and retrieve vectors as high-dimensional points. They add additional capabilities for efficient and fast lookup of nearest-neighbors in the N-dimensional space. They are typically powered by k-nearest neighbor indexes and built with algorithms like the Hierarchical Navigable Small World (HNSW) and Inverted File Index (IVF) algorithms. Vector databases provide additional capabilities like data management, fault tolerance, authentication and access control. 

Vector databases have the capabilities of a traditional database that are absent in standalone vector indexes and the specialization of dealing with vector embeddings, which traditional scalar-based databases lack.

Stores and manages unstructured data, such as text, images, or audio, in vector embeddings to make it easy to find and retrieve similar objects quickly.

The main advantage of a vector database is that it allows for fast and accurate similarity search and retrieval of data based on their vector distance or similarity. This means that instead of using traditional methods of querying databases based on exact matches or predefined criteria, you can use a vector database to find the most similar or relevant data based on their semantic or contextual meaning.

For example, you can use a vector database to:

find images that are similar to a given image based on their visual content and style
find documents that are similar to a given document based on their topic and sentiment
find products that are similar to a given product based on their features and ratings
To perform similarity search and retrieval in a vector database, you need to use a query vector that represents your desired information or criteria. The query vector can be either derived from the same type of data as the stored vectors (e.g., using an image as a query for an image database), or from different types of data (e.g., using text as a query for an image database). Then, you need to use a similarity measure that calculates how close or distant two vectors are in the vector space. The similarity measure can be based on various metrics, such as cosine similarity, euclidean distance, hamming distance, jaccard index.

The result of the similarity search and retrieval is usually a ranked list of vectors that have the highest similarity scores with the query vector. You can then access the corresponding raw data associated with each vector from the original source or index.

Vector databases provide a method to operationalize embedding models. Application development is more productive with database capabilities like resource management, security controls, scalability, fault tolerance, and efficient information retrieval through sophisticated query languages.

Vector databases ultimately empower developers to create unique application experiences. For example, your users could snap photographs on their smartphones to search for similar images. 

Developers can use other types of machine learning models to automate metadata extraction from content like images and scanned documents. They can index metadata alongside vectors to enable hybrid search on both keywords and vectors. They can also fuse semantic understanding into relevancy ranking to improve search results.

How are vector databases used?
Vector databases are typically used to power vector search use cases like visual, semantic, and multimodal search. More recently, they’re paired with generative artificial intelligence (AI) text models to create intelligent agents that provide conversational search experiences.

Who uses vector databases?
Vector databases are for developers who want to create vector search powered experiences. An application developer can use open-source models, automated machine learning tools, and foundational model services to generate embeddings and hydrate a vector database. This requires minimal ML expertise.

A team of data scientists and engineers can build expertly tuned embeddings and operationalize them through a vector database. This can help them deliver artificial intelligence (AI) solution faster.

Operations teams benefit from managing solutions as familiar database workloads. They can use existing tools and playbooks.

What are the benefits of vector databases?

Vector databases allow developers to innovate and create unique experiences powered by vector search. They can accelerate artificial intelligence (AI) application development and simplify the operationalization of AI-powered application workloads.

Vector databases provide an alternative to building on top of bare k-nearest neighbor (k-NN) indexes. That kind of index requires a great deal of additional expertise and engineering to use, tune and operationalize.

A good vector database provides applications with a foundation through features like data management, fault tolerance, critical security features, and a query engine. These capabilities allow users to operationalize their workloads to simplify scaling, maintain high scalability, and support security requirements.

Capabilities like the query engine and SDKs simplify application development. They also allow developers to perform more advanced queries (like searching and filtering) on metadata as part of a k-NN search. They also have the option to use hybrid relevancy scoring models that blend traditional term frequency models like BM25 with vector scores to enhance information retrieval.