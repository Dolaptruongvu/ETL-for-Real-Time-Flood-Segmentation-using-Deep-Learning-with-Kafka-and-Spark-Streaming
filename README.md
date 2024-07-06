Dataset: FloodNet-Challenge-EARTHVISION2021

Models using: FPN, DeeplabV3Plus, Unet

Main Technology: Spark Streaming, Apache Kafka

Python: 3.9.19

Folder Description : 
- no-raintraining : Folder containing the training code for predicting no-rain conditions.
- rain-model-predict : Folder for running the main code with predictions under rain conditions.
- raintraining :  Folder containing the training code for predicting under rain conditions.

Files Description: 
- getResult : For querying the masks from the database and showing the predicted mask.
- producer : Using Apache Kafka to send the image.
- spark_* : Using Apache Spark for streaming processing.
- requirements : Install packages for running.

Install requirement command : conda install --name <existing_env_name> --file requirements.txt


Note: We need the Train, test from above dataset for running.

