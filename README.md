# Semantic-Search-on-a-Movie-DB

The way we query to search engine has changed
over few decades. We are at a moment in which
semantic search, the ability to put typed searches
into context, represents the most accurate option
for granting answers. We want to take this approach
of semantic search and apply it to the more
specific domain of the Movie search. There are
instances when a person wants to look up a movie
but cannot recall the exact movie name and can
only recall basic keywords related to the plot. The
person would impulsively look up and search for
the movie name based on the words he can recall.
Modern search engines will not be able to give out
exact results related to the movie and would rather
provide some out of context results for the input
search query. This is a very common problem
among the modern generation which only ends up
with meaningless results. By bringing it down to
the specific problem, we can learn about how natural
language queries can be put into the context
using semantic parsing for solving a specific problem.

Two approaches were used:
1. Semantic Graph Similarity (EventExtraction.py, indexKParser.py, KeywordExtraction.py)


2. Latent Semantic Indexing (genesim.py)


The model for predicting the movie name based on
an input query was successfully implemented. It
was implemented using two different approaches
namely, Semantic Graph Similarity and Latent
Semantic Indexing. The first approach used pre
existing K Parser to build semantic tree for the
input query and movie plot data. A word2vec
model was designed to calculate the similarity
scores between various words of a sentence. The
similarity scores between various sentences were
calculated using two algorithms described above
in the report. The second approach was based on
the concept of Latent Semantic Indexing using
the gensim library. The project allowed us to
implement various concepts in NLP with the help
of different libraries to make it easy. The second
approach, Latent Semantic Indexing gave us a
better accuracy of predicting the correct movie
plot. The first approach can be improved drastically
by learning from the errors and overcoming
them.
