## TO pull this data -
do a get request to
```
https://www.leafly.com/explore/sort-alpha
```

with the following headers

key      | value
--------- | -----:
accept  | application/json, text/plain, */*
cookie     |   ```optimizelyEndUserId=oeu1530400890761r0.6520403735539941; optimizelySegments=%7B%221380873998%22%3A%22false%22%2C%221381853736%22%3A%22search%22%2C%221382723995%22%3A%22ff%22%7D; optimizelyBuckets=%7B%7D; .ASPXANONYMOUS=RlBNfFdj20SMkr8mTqvcLRdFjTPh7x3IoO2-LtNrNuPOOl_M4jvrQYtJWLl_QbYfFiXrbyezj8Ph19fvZdR5LYr4VlmAQ2NRJ2-NSvG2C1ywiFlf0; leafly-locations=%5B%7B%22lat%22%3A40.0496%2C%22lon%22%3A-105.2769%2C%22city%22%3A%22Boulder%22%2C%22locationtext%22%3A%22Boulder%2C%20CO%22%2C%22locationslug%22%3A%22boulder-co%22%2C%22countrycode%22%3A%22US%22%2C%22statecode%22%3A%22CO%22%2C%22locationType%22%3A%22City%22%7D%5D; _ceg.s=pb5t1f; _ceg.u=pb5t1f; _biz_uid=161c9db97e474c30bc3b39d4f08adb30; _biz_sid=807697; _biz_nA=10; _biz_pendingA=%5B%5D; roost-notes-read=%7B%22data%22%3A%5B%5D%7D; roost-isopen=false; roost-flyout=false; _ga=GA1.2.1700493477.1530400894; _gid=GA1.2.126304104.1530400894; __gads=ID=d333e67093648377:T=1530400893:S=ALNI_MYCN43ptfJEggdEjPzW7ZehvyI4kA; __qca=P0-2008363471-1530400893755; spid=B4E0AC96-2247-4D5A-BE26-BD32BB431CFC; sp_ssid=1530400895178; sp_sync_ssid=1530401093320; sp_apnxid=1125869751479249583; __hstc=9292970.e95d00b40c32c11f6f7bb26fcadb28b2.1530400896302.1530400896302.1530400896302.1; __hssrc=1; __hssc=9292970.9.1530400896302; hubspotutk=e95d00b40c32c11f6f7bb26fcadb28b2; _cb_ls=1; _cb=BJ7p_mCW_dztDIA6xu; _chartbeat2=.1530400896621.1530401095459.1.BCF9uuDR448yBn-uxIBswDIMC5OKtO.5; _cb_svref=null; mp_74ed528b406df79c0072817961e52d0c_mixpanel=%7B%22distinct_id%22%3A%20%22164530066b51e1-02b12ec68731e1-4a5268-1aeaa0-164530066b616%22%2C%22%24search_engine%22%3A%20%22google%22%2C%22%24initial_referrer%22%3A%20%22https%3A%2F%2Fwww.google.com%2F%22%2C%22%24initial_referring_domain%22%3A%20%22www.google.com%22%7D; _gat_UA-319135-8=1```
connection     |   keep-alive
host     |   www.leafly.com
 
 This will return the json response instead of the HTML response
 
 ## To load this data into mongo
 Since I am using mlab's hosted free tier for this demo, go [here](!https://docs.mlab.com/migrating/#import)
