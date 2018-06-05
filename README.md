# Albanian NLP

The purpose of this project is to build a group of corpus and library for NLP (Natural Language Processing) for Albanian language

## Stopwords

In computing, stop words are words which are filtered out before or after processing of natural language data. Read more here: https://en.wikipedia.org/wiki/Stop_words

## Stem

In linguistic morphology and information retrieval, stemming is the process of reducing inflected (or sometimes derived) words to their word stem, base or root form—generally a written word form. Read more here: https://en.wikipedia.org/wiki/Stemming

**How to use it**

    from stem import AlbStem

    stemmer = AlbStem('albanian')

    stemmer.stem("Përshëndetje")
