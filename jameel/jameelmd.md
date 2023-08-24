# What is a vector database?

<p>A vector database is a type of database that stores data as high-dimensional vectors, which are mathematical representations of features or attributes. Each vector has a certain number of dimensions, which can range from tens to thousands, depending on the complexity and granularity of the data. The vectors are usually generated by applying some kind of transformation or embedding function to the raw data, such as text, images, audio, video, and others. The embedding function can be based on various methods, such as machine learning models, word embeddings, feature extraction algorithms.

The main advantage of a vector database is that it allows for fast and accurate similarity search and retrieval of data based on their vector distance or similarity. This means that instead of using traditional methods of querying databases based on exact matches or predefined criteria, you can use a vector database to find the most similar or relevant data based on their semantic or contextual meaning.

For example, you can use a vector database to:

    find images that are similar to a given image based on their visual content and style
    find documents that are similar to a given document based on their topic and sentiment
    find products that are similar to a given product based on their features and ratings

To perform similarity search and retrieval in a vector database, you need to use a query vector that represents your desired information or criteria. The query vector can be either derived from the same type of data as the stored vectors (e.g., using an image as a query for an image database), or from different types of data (e.g., using text as a query for an image database). Then, you need to use a similarity measure that calculates how close or distant two vectors are in the vector space. The similarity measure can be based on various metrics, such as cosine similarity, euclidean distance, hamming distance, jaccard index.

The result of the similarity search and retrieval is usually a ranked list of vectors that have the highest similarity scores with the query vector. You can then access the corresponding raw data associated with each vector from the original source or index.


Use Cases for Vector Databases

Vector databases have many use cases across different domains and applications that involve natural language processing (NLP), computer vision (CV), recommendation systems (RS), and other areas that require semantic understanding and matching of data.

One use case for storing information in a vector database is to enable large language models (LLMs) to generate more relevant and coherent text based on an AI plugin.

However, large language models often face challenges such as generating inaccurate or irrelevant information; lacking factual consistency or common sense; repeating or contradicting themselves; being biased or offensive. To overcome these challenges, you can use a vector database to store information about different topics, keywords, facts, opinions, and/or sources related to your desired domain or genre. Then, you can use a large language model and pass information from the vector database with your AI plugin to generate more informative and engaging content that matches your intent and style.

For example, if you want to write a blog post about the latest trends in AI, you can use a vector database to store the latest information about that topic and pass the information along with the ask to a LLM in order to generate a blog post that leverages the latest information.
 </p>
 
[article link](https://learn.microsoft.com/en-us/semantic-kernel/memories/vector-db)

## What is the difference between vector database and relational database? 
<p>
 Every table in a relational database is like a spreadsheet. To find a row of data, you match it on a set of criteria. For example: Lives in USA, surname Smith, drives a Nissan Leaf. They are excellent and extremely fast at this task. However what they are very poor at is finding stuff similar to stuff, especially when the similarity is more abstract.

A vector database has the data input as things known as vector embeddings. This is a higher dimensional interpretation of something, and the dimensions may be abstract and not meaningful to humans since they were produced by machine learning. In this higher dimensional vector space, the database would understand that:

Lives in USA, surname Smith, drives a Nissan Leaf

Is similar to

Lives in Canada, surname Johnson, drives a Tesla Model 3.

Therefore both of these people may be good targets for a particular advert.

Via a layer of abstraction its able to say Canada and USA are reasonably similar, Smith and Johnson are common names, and a Leaf and a Tesla are similar since they are electric cars. The database probably does not understand the concept of an electric car.

They are complex to set up and manage, but extremely powerful.

Another example that's human understandable, is colour. Colour can be imagined as a vector with a Red, Green and Blue component. A vector database could trivially match similar colours based on this vector, while a relational database would require the user to specifically develop rules to find similar colours. </p>

[article link](https://www.reddit.com/r/explainlikeimfive/comments/rfnq5x/eli5_what_is_the_difference_between_vector/?rdt=51263)

### Useful links
[Vector Databases in-depth](https://www.reddit.com/r/datascience/comments/14ieyfs/vector_databases_101/)

[Easy Explanation of Vector Databases](https://medium.com/geekculture/explain-like-im-5-vector-database-hype-bd936fd319ff)
