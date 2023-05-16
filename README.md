# itsfamilyguy
Doing data analysis on a dataset from the popular show "Family Guy" which contains characters, season and dialogues 

1. First data is preprocessed removing any null values and then grouping the data by season or characters or both
2. grouping is done is calculate all statistical measures regarding dialogues spoken by the characters
3. After pre-processing the data visualisations in the form of bar plot, line plot, bar plot for unique characters each season and word cloud, heat map to find character occurence is done
4. After all of this, dialogues per season are aggregated first
5. Then, using regex,nltk and gensim libraries stop words are removed, lemmitization is done and then tokinization to form dictionary
6. Then, in order to do Topic classificiation or LDA analysis we use pyLDAvis to get Intertopic Distance Map and get top most frequent and/or “relevant” terms, using different values of the λ parameter. This can help when you’re trying to assign a human interpretable name or “meaning” to each topic.

![image](https://github.com/pranoy01/itsfamilyguy/assets/80458532/96776289-0afe-49d0-81d2-e172e277a82e)
