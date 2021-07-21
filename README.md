Install node exporter with bash script
Execute the following:

sudo su

wget -O - https://raw.githubusercontent.com/shivamgrover/install-node-exporter-bash/main/install-node-expoter.sh | bash

You can see all the server metrics by visiting your server URL on /metrics as shown below.

http://<server-IP>:9100/metrics
