## Word Prediction
An Embedded Deep Learning based Word Prediction 

## Description
We have proposed an embedded deep learning based word prediction method that optimizes for run-time, and memory to render a smooth performance. Our model size is 7.40MB and has average prediction time of 6.47 ms.

## Data
The data set which is used for training and evaluating the model proposed in "An Embedded Deep Learning based Word Prediction"

Training data is extracted from resources on the Internet, in a raw form with 8 billion words. We uniformly sample 10% (196 million) from the data. It consists of 60% for training, 10% for validation and 30% for test.

We preprocess raw data to remove noise and filter phrases. We also replace number in the dataset with a special symbol, \<NUM\> and out-of-vocabulary (OOV) words with \<UNK\>. We append start of sentence token \<s\> and end of sentece token \</s\> to every sentence. We convert our dataset to lower-case to increase vocabulary coverage and use top 15K words as the vocabulary.

Evaluating data is manually curated to compare our performance with existing word prediction methods. The dataset is consist of 102 sentences (926 words, 3,746 characters) which are collection of formal and informal utterances from various sources which covers general keyboard scenarios. 


## Download

You can download the data set directly from the comman line:
```
git clone https://github.com/Meinwerk/WordPrediction.git
```

You can also download the data set as a zip file using the following URL:
```
https://github.com/Meinwerk/WordPrediction/master.zip 
```

## Extraction
```
cat en-sents-shuf00.data.tar.gz* | tar xvzf -
```

## Contact

Contact: Seunghak Yu, Nilesh Satish Kulkarni <br> Email: <full_name>@gmail.com

