# Speaker-and-Gender-Recognition

Using audio files of sample of people, trained a machine learning model from scract to predict two outcome variables:
1. Who is the speaker of this audio?
2. What is the gender of this speaker?

Following functions were used:
1. MFCC library to get MFCC features (Mel Frequency Cepstral Coefficients)
2. One hot encoding
3. Softmax
4. Grdaient Descent
5. Evaluation (Accuracy and F1 scores)


Accuracy for Gender Recognition is =  84.70588235294117
                precision    recall  f1-score   support

           0       0.97      0.82      0.89       130
           1       0.62      0.93      0.74        40

    accuracy                           0.85       170
   macro avg       0.79      0.87      0.82       170
weighted avg       0.89      0.85      0.86       170

Accuracy for Speaker Recognition is =  92.25352112676056
F1 Score for Speaker Recongnition Validation is =  91.55264922870556


