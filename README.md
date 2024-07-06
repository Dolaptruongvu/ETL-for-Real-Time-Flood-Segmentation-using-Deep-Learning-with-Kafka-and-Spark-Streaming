Dataset: FloodNet-Challenge-EARTHVISION2021

Models using: FPN, DeeplabV3Plus, Unet

Main Technology: Spark Streaming, Apache Kafka

Folder Description : 
- no-raintraining : Folder containing the training code for predicting no-rain condition
- rain-model-predict : For running the main code with predicting under the rain condition
- raintraining :  Folder containing the training code for predicting under rain condition

Files Description: 
- getResult : for querying the masks from database and show the predicted mask
- producer : Using Apache Kafka for send the image
- spark_* : Using Apache Spark for streaming processing
- requirements : install package for running



Note: We need the Train, test from above dataset for running.

