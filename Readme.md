1 - cross-subject transfer learning in HAR, assuming different data scarcity scenarios on the target user (e.g., 1%, 5%, 10%, 15% of the training set) and also a different activities set of activities (e.g., the target user has an additional activity)

2 - Hybrid CNN-LSTM as a deep learning model. Fine-tuning as a transfer learning technique. 
Leave one out for validating transfer learning on each subject of the dataset.  

3 - For each participant, the study had been commenced by collecting their demographic (age and gender) and physically-related (height and weight) information. Then, we provided them with a dedicated smartphone (iPhone 6) and asked them to store it in their trousers' front pocket during the experiment. All the participant were asked to wear flat shoes. We then asked them to perform 6 different activities (walk downstairs, walk upstairs, sit, stand and jogging) around the Queen Mary University of London's Mile End campus. For each trial, the researcher set up the phone and gave it to the current participants, then the researcher stood in a corner. Then, the participant pressed the start button of Crowdsense app and put it in their trousers' front pocket and performed the specified activity. We asked them to do it as natural as possible, like their everyday life. At the end of each trial, they took the phone out of their pocket and pressed the stop button.

Motionsense

5 - Fully supervised learning only using data from the target user (no transfer).
Hence, in each fold of the leave-one-out, the baseline consists in training a model only with data from the target user.
This baseline is useful to understand the recognition rate of the model while only using data from the target user, without transfer.
 
6 - R1: Transfer learning should reach better results than simply training a model for the target user with its limited fine-tuning data. 
R2: Transfer learning should reach similar results compared to using 100% of the training data of the target user.