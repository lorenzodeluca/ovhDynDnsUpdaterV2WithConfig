# dyndnsUpdaterJava
A script to connect and auth in the ovh api and update a dynamic dns every time the public ip of the host change 

to get ovh api key token(POST /\* and PUT /\*): [https://api.ovh.com/createToken/index.cgi?PUT=/\*&POST=/\*](https://api.ovh.com/createToken/index.cgi?PUT=/*&POST=/*)

ovh api info: https://api.ovh.com/console/#/domain

the ip.txt file will be updated automatically(You can delete it before running the script to force a domain update)

to get the record id go to https://api.ovh.com/console/#/domain and use the GET /domain/zone/{zoneName}/dynHost/record

<img src="/demo.png">
