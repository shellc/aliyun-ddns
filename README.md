# aliyun-ddns
A DDNS tool for domain hosted on Aliyun.com/Net.CN

#### Mechanisms
* The domain must be hosted on Aliyun.com/Net.CN
* Query the public IP address through name servers provided by OpenDNS
* Create/Update DNS record by Aliyun open apis.
* Use the crontab to run this script ever minutes.

#### Configuration
* Change access key id/secure you got from https://ak-console.aliyun.com/#/accesskey
* Change domain and record you want to create/update.
