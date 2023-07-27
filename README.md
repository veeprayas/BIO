# DATA SCIENCE PROJECT

The main objective is to look into Text Summarization techniques and its application with-in medical domain. The PubMed database contains more than 34 million citations
and abstracts of biomedical literature, presenting its own set of challenges in cataloguing, distribution, standardising, and qualifying of medical text data. The need for research on biomedical text summarization is twofold. (1) With the increasing volume and variety of data (Medical texts are usually accompanied by
images), along with growing regulation, it becomes important to interpret and summarise data in a fast, secure, and error freeway (2) The medical domain has its own distinct language models, jargon, vocabulary, and abbreviations compared to other domains or general English models. In this project BERT is pretrained and from biomedical summaries data BERT embeddings are extracted and compared with BIO-BERT embeddings and the difference in embeddings for a test data is reported.

# RUN CODE

In the BERT FOLDER:

Loading_the_Dataset_from_Hugging_Faces.ipynb = Code to extract and clean the dataset.
Extract_data_from_Hugging_Faces_BERT_PRETRAINED.ipynb = BERT pretrained code is leveraged to extract embeddings from article summaries.

These two codes can directly run on Google Colab. The code can directly be opened on colab and then "run all" will automatically run the code.

In biobert_summ FOLDER:

Bio Bert Summarizer Test_updated.ipynb = Code which specifies BIOBERT embedding extraction as well as cosine similarity in the end which compares both BERT and BIOBERT embeddings on a custom input file.

This code is sligtly time-consuming to excecute, The code should be run on the local system and paths to the dataset (Data.zip) must be specified based on location  of dataset in the working directory of the local system. All the required packages must installed using the pip command. I have also attached a .zip folder on canvas having all the weight files generated for biobert_sum.

****For ease of use all the .py codes mentioned above if opened through this git repo already have results for each and every step of excecution. These results can be analysed to understand the code and to draw appropriate insights.

# RESULTS

I observed for summarization of biomedical articles BIOBERT embeddings are much better that generic BERT embeddings. The cosiesimilarty based differences can be observed in the Bio Bert Summarizer Test_updated.ipynb. To obtain cosine distance use the formula (Cosine_distance = 1 - cosine_similarity).

# NOTE
I have also attached a word document specifying my research work for this project completion.

