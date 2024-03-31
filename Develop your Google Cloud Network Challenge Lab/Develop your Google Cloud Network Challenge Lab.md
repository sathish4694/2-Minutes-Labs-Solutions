# Develop your Google Cloud Network: Challenge Lab || [GSP321](https://www.cloudskillsboost.google/focuses/10603?parent=catalog) ||

## Solution [here]()

### Run the following Commands in CloudShell

```
export ZONE=
```
```
curl -LO raw.githubusercontent.com/QUICK-GCP-LAB/2-Minutes-Labs-Solutions/main/Develop%20your%20Google%20Cloud%20Network%20Challenge%20Lab/gsp321.sh

sudo chmod +x gsp321.sh

./gsp321.sh
```
### Task 8. Enable monitoring

1. In Google Cloud Console, go to `Kubernetes Engine` -> `Services and Ingress` -> 
2. Copy `endpoint`'s (`wordpress`) `IP address`.
3. In Google Cloud Console, go to `Monitoring` -> `Uptime Checks` -> `+ CREATE UPTIME CHECK`. 
4. Fill in the details as provided below:

* Target: 

* Hostname : `endpoint's IP address` (without http and port number)

* Path : `/`

* Title: `Wordpress Uptime`

5. Leave everything as default. Click `Next` -> `Next` -> `Create`

### Congratulations 🎉 for completing the Challenge Lab !

##### *You Have Successfully Demonstrated Your Skills And Determination.*

#### *Well done!*

#### Don't Forget to Join the [Telegram Channel](https://t.me/QuickGcpLab) & [Discussion group](https://t.me/QuickGcpLabChats)

# [QUICK GCP LAB](https://www.youtube.com/@quickgcplab)