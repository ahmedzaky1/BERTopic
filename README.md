## Intro in Topic
1. I have data that does not have any classification (row data)
and I need a way to classify this data so that every group of documents similar to each other comes together.

2.Use transformers and c-TF-IDF to create a dense clusters

3. BERTopic supports all kinds of topic modeling techniques.

## Libs
1. datasets to load data from huggingface
2. pandas
3. re
4. random
5. nltk
6. matplotlib
7. seaborn
8. datetime
9. sentence_transformers ( Sentence Embeding )
10. umap ( Dim Reduction )
11. hdbscan ( clustering )
12. sklearn

## Processing 
1. clean text with nltk and re ( Remove urls, replace any digit with رقم, set space before and after any punctuation and Remove any words that len = 1 )
2. Remove any doc <= 10_000.
3. Remove duplicated text.

## Processing Steps of Topic

1. convert doc to Embeddings with transformers
2. Reduce dimensionality.
3. clustering.
4. Tokenization of topic.
5. Topic Representer

## Train
Spilit data to topics and return ( topic, prob )

## Visualition Topic Model
