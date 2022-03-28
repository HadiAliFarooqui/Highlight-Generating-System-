# Highlight-Generating-System-
This project has 3 main features: 1. Automatic Video highlights generator, 2. Document summarization, and 3. Multiple document comparison. 


## Overview of each feature: 
### 1. Video Summarization:
Imagine you don't have access to the highlights of the recent IPL cricket match and you don't have enough time to watch the full match, nor you have a habit of reading 
the scores from the newspaper (which is kinda boring). Or imagine you are creating your own Premium League and you don't have enough expertize of generating highlights of the full length recorded match. That's where our feature comes in, it's a simple U.I (user interface) application wherein all you need to do is, simply upload your full length match video and within few minutes, your highlights will be generated (i.e. 1-2 hrs length of video will be converted to short clip of around 10 - 15 minutes). 


#### **Technologies used:** 
* Python
* OpenCV
* Librosa 
* MoviePi


#### **Flow Chart _(for better understanding)_:** 
![image](https://user-images.githubusercontent.com/52156264/160380363-907c99b1-3662-4531-b585-1dde041e741e.png)



___

### 2. Document Summarization:
This feature allows the users to create an abstract of any document. Let's consider a document having 5000 words. If you're an average reader, it will take around 16 - 18  minutes to read the entire document. With the help of our feature, one can easily produce an authentic abstract just by uploading their document and then by one click, your abstract will be displayed on the screen (5000 words will be compressed to 500 to 800 words approx). __Booyah! it's time saviour__. 


#### **Technologies used:** 
* Python
* NLP
* NLTK 


#### **Here is a Flow Chart which gives us crystal clear understanding of how our algorithm works _(for better understanding)_:** 
![image](https://user-images.githubusercontent.com/52156264/160382692-8ba7c3f1-20ce-4741-b2a7-038fa3f7cea6.png)



#### **Overview of NLP:**
![image](https://user-images.githubusercontent.com/52156264/160382896-6937924c-4cdd-49b8-8c58-9f7845e22a10.png)


___

### 3. Document Comparision:
This is the most interesting feature of our project (kinda rare to find). This feature allows users to compare multiple documents and it will display how similar each document is when compared to other documents. (The output will be in the form of matrix).
Suppose if we have 3 documents to compare, lets name these documents for better understanding (Names =  doc1, doc2 doc3).
Our algorithm compares doc1 to doc2 and doc3, and doc2 will be compared with doc3 (as it has already been compared with doc1), and doc3 is already being compared with all the remaining documents.


#### **Technologies used:** 
* Python
* NLTK
* Cosine Similarity


#### **Example of Cosine Similarity:**
![image](https://user-images.githubusercontent.com/52156264/160384488-9a6c35cb-d558-473e-86af-91646d60af1e.png)

