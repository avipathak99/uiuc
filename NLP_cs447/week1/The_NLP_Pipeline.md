One issue with natural language is that as native speakers of a language, when you see some text in your language, you just understand it automatically. You can't not understand it.

You need to be able to identify basically, sentence boundaries, words.

In order to understand what these words are, the next step in the traditional NLP pipeline is what's called part-of-speech-tagging. That means if you have a sentence like say, back in English, ''Open the pod door, Hal.'' You want to be able to identify open as a verb, the as a determiner, pod and door as common nouns and Hal as a name.

Especially in a language like English, open can actually be a verb, it can be an adjective, it can be a noun. Like the Open isn't the tennis tournament? The open door, it's an adjective. In the open, is a noun.

1. Tokenization to identify word boundaries, sentence boundaries

2. Part of speech tagger and or morphological analyzer to identify the parts of speech, labels for words, as well as possibly the structure of words. 

3. Word sense disambiguation - to identify the particular sense of a word or the meaning of a word.

4. Then we want to translate sentences or sequences of words into their structures.Syntactic parser

5. Meaning representation, that would be a semantic parser.

6. Discourse model.

Those are at a very high-level, the steps involved in this traditional NLP pipeline
 
 ![Syntactic Parsing](https://github.com/avipathak99/uiuc/blob/main/NLP_cs447/week1/NLP_cs447/week1/images/syntactic_parsing.png)
