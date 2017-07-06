## Word Prediction

Recent developments in deep learning with application to language modeling have led to success in tasks of text processing, summarizing and machine translation. 
However, deploying huge language models for mobile device such as on-device keyboards poses computation as a bottle-neck due to their puny computation capacities. 
In this work we propose an embedded deep learning based word prediction method that optimizes run-time memory and also provides a real time prediction environment. Our model size is 7.40MB and has average prediction time of 6.47 ms. We improve over the existing methods for word prediction in terms of key stroke savings and word prediction rate.

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
cd unked-clean-dict-15k
cat en-sents-shuf.00.data.tar.gz* | tar xvzf -
```

## Traning Data
```
./unked-clean-dict-15k/en-sents-shuf.00.test.txt
./unked-clean-dict-15k/en-sents-shuf.00.valid.txt
./unked-clean-dict-15k/en-sents-shuf.00.train.txt
```

## Evaluation Data
```
./eval_kss_en.txt
```

## Contact

Contact: Seunghak Yu, Nilesh Satish Kulkarni <br> Email: <full_name>@gmail.com

