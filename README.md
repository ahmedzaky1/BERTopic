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


![Screenshot (112)](https://github.com/ahmedzaky1/BERTopic/assets/103897664/be307a5c-81bb-4721-bc7a-2884d8111784)
![Screenshot (111)](https://github.com/ahmedzaky1/BERTopic/assets/103897664/9d5873e6-d73a-4f76-bdb4-eb39d5afe4d9)
![Screenshot (110)](https://github.com/ahmedzaky1/BERTopic/assets/103897664/12bd3aa2-c908-4a44-8779-5cccab8536e9)
![Screenshot (113)](https://github.com/ahmedzaky1/BERTopic/assets/103897664/f88edb17-f17c-4161-b500-842f76ce1657)
