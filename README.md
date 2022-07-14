# LogicMonitor-Groovy-Script
Hi Everyone, I am trying to add curl statements into this groovy script, but am not familiar with it.

I'd need the following curl statement syntaxed into groovy:

curl --cookie-jar /tmp/cookie.txt -i\
 -X POST https://vco124-usca1.velocloud.net/portal/rest/login/enterpriseLogin \
 --data '{"username":"myuser","password":"'password'"}'

curl --cookie /tmp/cookie.txt -i\
 -X POST https://vco124-usca1.velocloud.net/portal/rest/enterpriseProxy/getEnterpriseProxyEnterprises \
 --data '{"enterpriseProxyId": 5}'
