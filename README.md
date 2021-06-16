Multiclass classification fact-checking using huggingface's PUBHEALTH
BERT model used for transfer learning: bert-base-cased

Final Model Performance:

              precision    recall  f1-score   support

           0       0.00      0.00      0.00       388
           1       0.18      0.51      0.27       201
           2       0.54      0.56      0.55       599
           3       0.02      0.02      0.02        45

    accuracy                           0.35      1233
   macro avg       0.19      0.27      0.21      1233
weighted avg       0.29      0.35      0.31      1233

Future steps to improve model performance:

Longer sequences of input text
Trying other different BERT models
Generating data using GANs for under-represented classes instead of introducing class weights
Partial tuning of BERT weights instead of completely fixing them
More number of epochs
