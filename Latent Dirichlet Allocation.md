# Latent Dirichlet Allocation (LDA)
Source: http://blog.echen.me/2011/08/22/introduction-to-latent-dirichlet-allocation/

LDA assumes that as an author, you would:
1. Decide how many words the corpus/text would contain.
2. Decide what topics/topic mixture you want to write about. The topic mixture contains multiple topics with varying probabilities that sum up to 1.
3. Pick a topic and write a word that belongs to that topic.

So, while determinig the topic, LDA would trace back from text to the topics that would have generated the text.
