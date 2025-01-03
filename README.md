# SMS Spam Classifier  
- Perform object tracking.
- Generate a video containing the results of object tracking.


## SMS Spam Collection Dataset : [[Kaggle]](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset)
- Collection of SMS messages tagged as spam or legitimate.
The SMS Spam Collection is a set of SMS tagged messages that have been collected for SMS Spam research. It contains one set of SMS messages in English of 5,574 messages, tagged acording being ham (legitimate) or spam. 

## Run
```
Spam_Message_BERT_tokenize.ipynb
```

### Results

```
Result after training 100 epochs.
Training on Colab T4 GPU

Class     Images  Instances      Box(P          R      mAP50  mAP50-95)     Mask(P          R      mAP50  mAP50-95)
  all        133       6285      0.848      0.796      0.872      0.519      0.839      0.783      0.856      0.465
```
