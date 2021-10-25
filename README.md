The goal is to classify a boat picture between the following categories:
coastguard, containership, corvette, cruiser, cv, destroyer, ferry, methanier, sailing, smallfish, submarine, tug  and vsmallfish.
The dataset was currated by our teacher.

Results from scratch: 

               precision    recall  f1-score   support

   coastguard       0.62      0.90      0.74       322
containership       0.97      0.94      0.96       646
     corvette       0.88      0.74      0.80       279
      cruiser       0.96      0.96      0.96       639
           cv       0.91      0.78      0.84       193
    destroyer       0.91      0.88      0.90       612
        ferry       0.73      0.94      0.82       343
    methanier       0.95      0.89      0.92       330
      sailing       0.93      0.84      0.88       177
    smallfish       0.78      0.85      0.81       311
    submarine       0.96      0.83      0.89       271
          tug       0.92      0.80      0.86       326
   vsmallfish       0.89      0.76      0.82       318

     accuracy                           0.87      4767
    macro avg       0.88      0.85      0.86      4767
 weighted avg       0.89      0.87      0.88      4767

Results with transfer learning (using EfficientNet):

               precision    recall  f1-score   support

   coastguard       0.94      0.92      0.93       331
containership       0.99      0.99      0.99       675
     corvette       0.91      0.91      0.91       295
      cruiser       0.99      1.00      0.99       675
           cv       0.96      0.96      0.96       196
    destroyer       0.96      0.97      0.97       682
        ferry       0.97      0.95      0.96       343
    methanier       0.97      0.99      0.98       337
      sailing       0.97      0.96      0.96       167
    smallfish       0.73      0.75      0.74       319
    submarine       0.98      0.97      0.97       287
          tug       0.96      0.96      0.96       331
   vsmallfish       0.72      0.71      0.72       325

     accuracy                           0.94      4963
    macro avg       0.93      0.93      0.93      4963
 weighted avg       0.94      0.94      0.94      4963
