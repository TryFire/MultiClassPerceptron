# MultiClassPerceptron
This is a custom mutil-class perceptron for predicting the Part-of-Speech (PoS) of a sentence where PoS, in traditional grammar,   is a category of words which have similar grammatical properties.

## Background
Words that are assigned to the same part of speech generally display similar behavior in terms of syntax (they play similar role
within the grammatical structure of sentences. Commonly listed English PoS are: noun,
verb, determiner, adjective, adverb, pronoun, preposition, conjunction, interjection.

PoS tagging can be considered as a multi-class classification problem in which each
word of a sentence is associated with a label describing its PoS. Each example can therefore be seen as triplet: word, context (the sentence the word is used in) and its PoS.

## Vue on a raw of data
**words:** ['Les', 'commotions', 'cérébrales', 'sont', 'devenu', 'si', 'courantes', 'dans', 'ce', 'sport', "qu'", 'on', 'les', 'considére', 'presque', 'comme', 'la', 'routine', '.']

**Labels:** ['DET', 'NOUN', 'ADJ', 'VERB', 'VERB', 'ADV', 'ADJ', 'ADP', 'DET', 'NOUN', 'SCONJ', 'PRON', 'PRON', 'VERB', 'ADV', 'ADP', 'DET', 'NOUN', 'PUNCT']

**The object** is to predict the PoS given one word and the context (the sentence having the word)

## TODO:// Describe the notation of build the model(Perceptron)

## TODO:// Describe the notation of Out-of-Domain PoS tagging
