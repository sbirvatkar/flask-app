1- Configure AWSCLI 



2- CREATE DYNAMODB TABLE WITH THE CONTENT

aws dynamodb create-table --cli-input-json file://create-table.json 
aws dynamodb batch-write-item --request-items file://batch-write.json

3- 
INSTALL DEPENDENCY-
pip install flask pip install boto3
SET FLASK_APP=app.py

4- 
Run the application with the below command
python app.py

5- 
Browse the application with the below link-
http://127.0.0.1:5000/get-items