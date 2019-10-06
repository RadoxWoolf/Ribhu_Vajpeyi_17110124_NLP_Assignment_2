# Ribhu_Vajpeyi_17110124_NLP_Assignment_2

Q: How many N-Grams are possible and how many actually exist?
A: Consider a vocabulary size of |vocabulary|. For unigram, |vocabulary| unigrams are possible (from the notebook we have- 17637 distinct unigrams). For bigram, |vocabulary|^2 bigrams are possible (from the notebook we have- 198760 distinct bigrams). For trigram, |vocabulary|^3 trigrams are possible (from the notebook we have- 459448 distinct trigrams). For quadgram, |vocabulary|^4 quadgrams are possible (from the notebook we have- 572919 distinct quadgrams). The mismatch in the expected and actual numbers is because not all combinations are possible within a n-gram and hence in reality only a fraction of expected exist.

Q: Generate random text of 5 sentences, then comment on the readability
A: 5 Random sentences genrerated using Unigram:
    1. Would what will thought of pain he thoughts was to you you with and is or and ladies thought have
    2. Down haughtiness of not of to
    3. School in should pastures almost dirt of accordingly
    4. Made Mr to I the with be expedient takes of
    5. A at care and not means

   5 Random sentences genrerated using Bigram:
    1. She said Emma and it at it had attended to come in the case is no doing it proved again
    2. It stood up her to give a word
    3. He seemed to call another we may be drawing and cheerful look perfectly amiable action of Catherine in an apology and he could not it
    4. Of course of the object she was at hand and disposed to walk
    5. He said so dull for a fair the day to return that he entered this kind
    
    5 Random sentences genrerated using Trigram:
    1. You had the book where all the time at the bakery
    2. We all cared about that what was it in the box
    3. He would have made a bag full of apples
    4. Where was the city which who had
    5. Countryside was a beautiful flower blooming in the dark night of the winter cold christmas where the cakes were nice
    ....
    
   We see that as the order of n-grams increases, the readability increases. This is expected since more the order of the n-gram, more the context (before it) of the word is taken into consideration thus increasing a probability of selection of better words

Q: Compare perplexity of these models on the test dataset
A: (can be done using the python notebook provided)

Q: Does Neural performs better than Classical, if so, why? If not, why not? 
A: Yes. This is because classical takes into consideration the context of only the previous words to predict the probability of the next word, however neural methods predict the probabiltiy of the next words by training using the entire context words.
