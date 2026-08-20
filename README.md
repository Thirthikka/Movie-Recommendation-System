# Movie-Recommendation-System
The analysis develops a personalized **movie recommendation system** by representing movie
content through **textual embeddings**. The objective is to recommend movies similar to those
recently watched by a user and compare the effectiveness of **Word2Vec and Sentence
Transformer approaches**. The analysis uses **4,803 movies and 2,000 evaluation records**
containing user viewing information. Movie titles, genres and overviews are processed to
generate embeddings. **Word2Vec learns word-level representations** from the movie corpus, while
the pre-trained **all-MiniLM-L6-v2 Sentence Transformer captures contextual semantic
information**. Recommendations are generated using **average user-profile embeddings and cosine
similarity**. The Word2Vec approach achieves **22.7% recommendation success**, whereas
Sentence Transformer reaches **64.75%, with monthly performance remaining relatively
consistent**. The substantial improvement demonstrates the effectiveness of contextual
embeddings in capturing movie similarity and viewing preferences. The Sentence Transformer
model is therefore selected as the preferred recommendation approach and is further
demonstrated through a Gradio interface.
