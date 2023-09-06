# GSP1054
>🚨 [PLEASE SUBSCRIBE OUR CHANNEL CLOUDHUSTLER](https://www.youtube.com/@cloudhustlers) **&** [JOIN OUR COMMUNITY](https://chat.whatsapp.com/KBfUcSleGGEFf2Xvvm8FW3)
## Run in cloudshell
```cmd
export ZONE=
```
```cmd
gcloud services disable dataflow.googleapis.com
gcloud services enable dataflow.googleapis.com
export REGION=${ZONE%-*}
gcloud bigtable instances create personalized-sales \
            --display-name="Personalized Sales" \
            --cluster-config=id=personalized-sales-c1,zone=$ZONE
cbt -instance personalized-sales createtable UserSessions
cbt -instance personalized-sales createfamily UserSessions Interactions
cbt -instance personalized-sales createfamily UserSessions Sales
cbt -instance personalized-sales lookup UserSessions
gsutil mb gs://$DEVSHELL_PROJECT_ID/
```
## Wait for 5 min you will get the tick without completeing the 3rd and 5th task
## Go to the level 3 page you will see this tick
![image](https://github.com/CloudHustlers/Private-LEVEL-2-SEP/assets/88576711/4eb78959-b73d-4dca-accb-a0bb1056b6f7)
