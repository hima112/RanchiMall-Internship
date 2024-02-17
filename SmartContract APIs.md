# SmartcontractAPIs

## One-timeeventsmartcontracts-

## Externaltrigger-

## 1) GET/api/v2/smartContractInfo-

## Parameters :

## ● CompulsoryParameters:expirytime,userchoices

## ● OptionalParameters:minimumsubscriptionamout,maximumsubsciptionamount,

## contractamount

## Link(testnet) :

## https://ranchimallflo-testnet.ranchimall.net/api/v2/smartContractInfo?contractName=twitt

## er-survive&contractAddress=oVbebBNuERWbouDg65zLfdataWEMTnsL8r

## ResponseFormat :

## JSONResponse :

#### {

```
"contractAddress":"oVbebBNuERWbouDg65zLfdataWEMTnsL8r",
"contractInfo":{
"closeDate":"1681983849",
"contractAddress":"oVbebBNuERWbouDg65zLfdataWEMTnsL8r",
"contractAmount":0.02,
"contractName":"twitter-survive",
"contractSubtype":"external-trigger",
"contractType":"one-time-event",
"expiryDate":"1668504446",
"expiryTime":"sunnov 152022 14:55:00gmt+0530",
"flodata":"Createasmartcontractofthenametwitter-survive@ofthetypeone-time-event*usingasset
bioscope#attheFLOaddressoVbebBNuERWbouDg65zLfdataWEMTnsL8r$withcontract-conditions:(1)
expiryTime=SunNov 152022 14:55:00GMT+0530(2)userchoices=survives|dies(3)
minimumsubscriptionamount=0.04(4)maximumsubscriptionamount=1(5)contractAmount=0.
end-contract-conditions",
"incorporationDate":"1668503201",
"maximumsubscriptionamount":1,
"minimumsubscriptionamount":0.04,
"status":"closed",
"subtype":"external-trigger",
"tokenIdentification":"bioscope",
"unix_expiryTime":"1668543900.0",
"userChoices":[
"survives",
"dies"
]
},
"contractName":"twitter-survive"
}
```
## 2) GET/api/v2/smartContractInfo-

## Parameters :

## ● CompulsoryParameters:expirytime,userchoices


### ● OptionalParameters:N/A

### Link(testnet) :

### https://ranchimallflo-testnet.ranchimall.net/api/v2/smartContractInfo?contractName=mus

### k-vs-zuck-cage-war&contractAddress=ocEjM1W92oRpujLyuxN7wAiTmi33qdbAzg

### ResponseFormat :JSON

### JSONResponse:

#### {

```
"contractAddress":"ocEjM1W92oRpujLyuxN7wAiTmi33qdbAzg",
"contractInfo":{
"contractAddress":"ocEjM1W92oRpujLyuxN7wAiTmi33qdbAzg",
"contractName":"musk-vs-zuck-cage-war",
"contractSubtype":"external-trigger",
"contractType":"one-time-event",
"expiryDate":"1695587378",
"expiryTime":"monsep 252023 01:59:00gmt+0530(indiastandardtime)",
"flodata":"CreateasmartcontractofthenameMusk-vs-Zuck-Cage-War@ofthetypeone-time-event*using
assetbioscope#attheFLOaddressocEjM1W92oRpujLyuxN7wAiTmi33qdbAzg$withcontract-conditions:
(1)expiryTime=MonSep 252023 01:59:00GMT+0530(IndiaStandardTime)(2)userchoices=Musk|Zuck
end-contract-conditions",
"incorporationDate":"1695586967",
"status":"expired",
"subtype":"external-trigger",
"tokenIdentification":"bioscope",
"unix_expiryTime":"1695626940.0",
"userChoices":[
"musk",
"zuck"
]
},
"contractName":"musk-vs-zuck-cage-war"
}
```
### 3) GET/api/v2/smartContractInfo-

### Parameters :

### ● CompulsoryParameters:expirytime,userchoices

### ● OptionalParameters:contractamount

### Link(testnet) :

### https://ranchimallflo-testnet.ranchimall.net/api/v2/smartContractInfo?contractName=worl

### d-cup-winner&contractAddress=oV2yXU9pAWEB1HXrS5qVa5ANPFEKqu4Eoh

### ResponseFormat :JSON

### JSONResponse:

```
{
"contractAddress":"oV2yXU9pAWEB1HXrS5qVa5ANPFEKqu4Eoh",
"contractInfo":{
"contractAddress":"oV2yXU9pAWEB1HXrS5qVa5ANPFEKqu4Eoh",
"contractAmount":0.01,
"contractName":"world-cup-winner",
"contractSubtype":"external-trigger",
"contractType":"one-time-event",
"expiryDate":"1695564603",
"expiryTime":"sunsep 242023 19:38:00gmt+0530(indiastandardtime)",
"flodata":"Createasmartcontractofthenameworld-cup-winner@ofthetypeone-time-event*usingasset
bioscope#attheFLOaddressoV2yXU9pAWEB1HXrS5qVa5ANPFEKqu4Eoh$withcontract-conditions:(1)
expiryTime=SunSep 242023 19:38:00GMT+0530(IndiaStandardTime)(2)userchoices=India|Pakistan
(3)contractamount=0.01end-contract-conditions",
"incorporationDate":"1695563108",
"status":"expired",
"subtype":"external-trigger",
"tokenIdentification":"bioscope",
"unix_expiryTime":"1695604080.0",
"userChoices":[
"india",
"pakistan"
]
},
"contractName":"world-cup-winner"
}
```
### 4) GET/api/v2/smartContractInfo-

### Parameters :

### ● CompulsoryParameters:expirytime,userchoices

### ● OptionalParameters:maximumsubscriptionamout

### Link(testnet) :

### https://ranchimallflo-testnet.ranchimall.net/api/v2/smartContractInfo?contractName=nfl-w

### inner-2023&contractAddress=oUmSj8w4aQPikn7DAv4RgR11LJ18kwL2uB

### ResponseFormat :JSON

### JSONResponse:

```
{
"contractAddress":"oUmSj8w4aQPikn7DAv4RgR11LJ18kwL2uB",
"contractInfo":{
"contractAddress":"oUmSj8w4aQPikn7DAv4RgR11LJ18kwL2uB",
"contractName":"nfl-winner-2023",
"contractSubtype":"external-trigger",
"contractType":"one-time-event",
"expiryDate":"1695587708",
"expiryTime":"monsep 252023 02:05:00gmt+0530(indiastandardtime)",
"flodata":"CreateasmartcontractofthenameNFL-Winner-2023@ofthetypeone-time-event*usingasset
bioscope#attheFLOaddressoUmSj8w4aQPikn7DAv4RgR11LJ18kwL2uB$withcontract-conditions:(1)
expiryTime=MonSep 252023 02:05:00GMT+0530(IndiaStandardTime)(2)
maximumsubscriptionamount=0.004(3)userchoices=Kansas|Denverend-contract-conditions",
"incorporationDate":"1695573403",
"maximumsubscriptionamount":0.004,
"status":"expired",
"subtype":"external-trigger",
"tokenIdentification":"bioscope",
"unix_expiryTime":"1695627300.0",
"userChoices":[
"kansas",
"denver"
]
},
"contractName":"nfl-winner-2023"
}
```

### 5) GET/api/v2/smartContractInfo-

### Parameters :

### ● CompulsoryParameters:expirytime,userchoices

### ● OptionalParameters:minimumsubscriptionamount

### Link(testnet) :

### https://ranchimallflo-testnet.ranchimall.net/api/v2/smartContractInfo?contractName=cd-c

### ontest&contractAddress=od7HZTPsndHDiwiieSxxmtYiCaLf3vNZ6m

### ResponseFormat :JSON

### JSONResponse:

```
{
"contractAddress":"od7HZTPsndHDiwiieSxxmtYiCaLf3vNZ6m",
"contractInfo":{
"closeDate":"1696769551",
"contractAddress":"od7HZTPsndHDiwiieSxxmtYiCaLf3vNZ6m",
"contractName":"cd-contest",
"contractSubtype":"external-trigger",
"contractType":"one-time-event",
"expiryDate":"1696769551",
"expiryTime":"sunoct 082023 18:22:00gmt+0530(indiastandardtime)",
"flodata":"CreateasmartcontractofthenameCD-Contest@ofthetypeone-time-event*usingasset
bioscope#attheFLOaddressod7HZTPsndHDiwiieSxxmtYiCaLf3vNZ6m$withcontract-conditions:(1)
expiryTime=SunOct 082023 18:22:00GMT+0530(IndiaStandardTime)(2)minimumsubscriptionamount=
0.0003(3)userchoices=A|Bend-contract-conditions",
"incorporationDate":"1696768381",
"minimumsubscriptionamount":0.0003,
"status":"closed",
"subtype":"external-trigger",
"tokenIdentification":"bioscope",
"unix_expiryTime":"1696809120.0",
"userChoices":[
"a",
"b"
]
},
"contractName":"cd-contest"
}
```
### Timetrigger-

### 6) GET/api/v2/smartContractInfo-

### Parameters :

### ● CompulsoryParameters:expirytime,payeeaddress

### ● OptionalParameters:contractamount

### Link(testnet) :

### https://ranchimallflo-testnet.ranchimall.net/api/v2/smartContractInfo?contractName=albu

### m-fund-2&contractAddress=oaALNw1n8sXPeWuG7HWbks8DwkTr6v1vGn

### ResponseFormat :JSON

### JSONResponse :

#### 

```
{
"contractAddress":"oVbebBNuERWbouDg65zLfdataWEMTnsL8r",
"contractInfo":{
"closeDate":"1681983849",
"contractAddress":"oVbebBNuERWbouDg65zLfdataWEMTnsL8r",
"contractAmount":0.02,
"contractName":"twitter-survive",
"contractSubtype":"external-trigger",
"contractType":"one-time-event",
"expiryDate":"1668504446",
"expiryTime":"sunnov 152022 14:55:00gmt+0530",
"flodata":"Createasmartcontractofthenametwitter-survive@ofthetypeone-time-event*usingasset
bioscope#attheFLOaddressoVbebBNuERWbouDg65zLfdataWEMTnsL8r$withcontract-conditions:(1)
expiryTime=SunNov 152022 14:55:00GMT+0530(2)userchoices=survives|dies(3)
minimumsubscriptionamount=0.04(4)maximumsubscriptionamount=1(5)contractAmount=0.
end-contract-conditions",
"incorporationDate":"1668503201",
"maximumsubscriptionamount":1,
"minimumsubscriptionamount":0.04,
"status":"closed",
"subtype":"external-trigger"{
"contractAddress":"oaALNw1n8sXPeWuG7HWbks8DwkTr6v1vGn",
"contractInfo":{
"closeDate":"1682883309",
"contractAddress":"oaALNw1n8sXPeWuG7HWbks8DwkTr6v1vGn",
"contractAmount":0.1,
"contractName":"album-fund-2",
"contractSubtype":"time-trigger",
"contractType":"one-time-event",
"expiryDate":"1682883309",
"expiryTime":"monmay 012023 01:05:00gmt+0530(indiastandardtime)",
"flodata":"Createasmartcontractofthenamealbum-fund-2@ofthetypeone-time-event*usingasset
bioscope#attheFLOaddressoaALNw1n8sXPeWuG7HWbks8DwkTr6v1vGn$withcontract-conditions:(1)
expiryTime=MonMay 012023 01:05:00GMT+0530(IndiaStandardTime)(2)payeeAddress=
oMsVNPCDSK5jiy4H3tdnbnBebKqGKcDGn3:70:odzijPEJ1ToULkvRKiKYuzgbGFSXgC4R1o:30(3)
contractamount=0.1end-contract-conditions",
"incorporationDate":"1682882712",
"payeeAddress":{
"oMsVNPCDSK5jiy4H3tdnbnBebKqGKcDGn3":70,
"odzijPEJ1ToULkvRKiKYuzgbGFSXgC4R1o": 30
},
"status":"closed",
"subtype":"time-trigger",
"tokenIdentification":"bioscope",
"unix_expiryTime":"1682922900.0"
},
"contractName":"album-fund-2"
}
"tokenIdentification":"bioscope",
"unix_expiryTime":"1668543900.0",
"userChoices":[
"survives",
"dies"
]
},
"contractName":"twitter-survive"
}
```
### 7) GET/api/v2/smartContractInfo-

### Parameters :

### ● CompulsoryParameters:expirytime,payeeaddress

### ● OptionalParameters:minimumsubscriptionamout,contractamount

### Link(testnet) :

### https://ranchimallflo-testnet.ranchimall.net/api/v2/smartContractInfo?contractName=mini

### mum-subscription-test&contractAddress=ockp7EQr4SXxqbDH4KktovBsBspwgmPoGb

### ResponseFormat :JSON

### JSONResponse:

```
{
"contractAddress":"ockp7EQr4SXxqbDH4KktovBsBspwgmPoGb",
"contractInfo":{
"closeDate":"1694803203",
"contractAddress":"ockp7EQr4SXxqbDH4KktovBsBspwgmPoGb",
"contractAmount":0.001,
"contractName":"minimum-subscription-test",
"contractSubtype":"time-trigger",
"contractType":"one-time-event",
"expiryDate":"1694803203",
"expiryTime":"satsep 162023 00:10:00gmt+0530(indiastandardtime)",
"flodata":"Createasmartcontractofthenameminimum-subscription-test@ofthetypeone-time-event*
usingassetbioscope#attheFLOaddressockp7EQr4SXxqbDH4KktovBsBspwgmPoGb$with
contract-conditions:(1)expiryTime=SatSep 162023 00:10:00GMT+0530(IndiaStandardTime)(2)
payeeAddress=oaALNw1n8sXPeWuG7HWbks8DwkTr6v1vGn:100(3)contractamount=0.001(4)
minimumsubscriptionamount= 1 end-contract-conditions",
"incorporationDate":"1694802743",
"minimumsubscriptionamount":1,
"payeeAddress":{
"oaALNw1n8sXPeWuG7HWbks8DwkTr6v1vGn": 100
},
"status":"closed",
"subtype":"time-trigger",
"tokenIdentification":"bioscope",
"unix_expiryTime":"1694842800.0"
},
"contractName":"minimum-subscription-test"
}
```
### 8) GET/api/v2/smartContractInfo-

### Parameters :

### ● CompulsoryParameters:expirytime,payeeaddress

### ● OptionalParameters:maximumsubscriptionamout,contractamount

### Link(testnet) :

### https://ranchimallflo-testnet.ranchimall.net/api/v2/smartContractInfo?contractName=maxi

### mum-subscription-test&contractAddress=odXR6DxV84UVxPSehzWkgcTdYrmM1tBApV

### ResponseFormat :JSON


### JSONResponse:

```
{
"contractAddress":"odXR6DxV84UVxPSehzWkgcTdYrmM1tBApV",
"contractInfo":{
"closeDate":"1695508830",
"contractAddress":"odXR6DxV84UVxPSehzWkgcTdYrmM1tBApV",
"contractName":"maximum-subscription-test",
"contractSubtype":"time-trigger",
"contractType":"one-time-event",
"expiryDate":"1695508830",
"expiryTime":"sunsep 242023 04:10:00gmt+0530",
"flodata":"Createasmartcontractofthenamemaximum-subscription-test@ofthetypeone-time-event*
usingassetbioscope#attheFLOaddressodXR6DxV84UVxPSehzWkgcTdYrmM1tBApV$with
contract-conditions:(1)expiryTime=SunSep 242023 04:10:00GMT+0530(2)payeeAddress=
oMunmikKvxsMSTYzShm2X5tGrYDt9EYPij:100(3)maximumsubscriptionamount=0.
end-contract-conditions",
"incorporationDate":"1695508373",
"maximumsubscriptionamount":0.02,
"payeeAddress":{
"oMunmikKvxsMSTYzShm2X5tGrYDt9EYPij": 100
},
"status":"closed",
"subtype":"time-trigger",
"tokenIdentification":"bioscope",
"unix_expiryTime":"1695548400.0"
},
"contractName":"maximum-subscription-test"
}
```
### 9) GET/api/v2/smartContractInfo-

### Parameters :

### ● CompulsoryParameters:expirytime,payeeaddress

### ● OptionalParameters:minimumsbscriptionamount

### Link(testnet) :

### https://ranchimallflo-testnet.ranchimall.net/api/v2/smartContractInfo?contractName=icc-w

### inner-2023&contractAddress=oasgK1ZGWSDHFL5moHfEAycwJRjT3DS66J

### ResponseFormat :JSON

### JSONResponse:

```
{
"contractAddress":"oasgK1ZGWSDHFL5moHfEAycwJRjT3DS66J",
"contractInfo":{
"closeDate":"1695593123",
"contractAddress":"oasgK1ZGWSDHFL5moHfEAycwJRjT3DS66J",
"contractName":"icc-winner-2023",
"contractSubtype":"external-trigger",
"contractType":"one-time-event",
"expiryDate":"1695587568",
"expiryTime":"monsep 252023 02:02:00gmt+0530(indiastandardtime)",
"flodata":"CreateasmartcontractofthenameICC-Winner-2023@ofthetypeone-time-event*usingasset
bioscope#attheFLOaddressoasgK1ZGWSDHFL5moHfEAycwJRjT3DS66J$withcontract-conditions:(1)
```

```
expiryTime=MonSep 252023 02:02:00GMT+0530(IndiaStandardTime)(2)
minimumsubscriptionamount=0.01(3)userchoices=India|Pakistanend-contract-conditions",
"incorporationDate":"1695571039",
"minimumsubscriptionamount":0.01,
"status":"closed",
"subtype":"external-trigger",
"tokenIdentification":"bioscope",
"unix_expiryTime":"1695627120.0",
"userChoices":[
"india",
"pakistan"
]
},
"contractName":"icc-winner-2023"
}
```
### 10)GET/api/v2/smartContractInfo-

### Parameters :

### ● CompulsoryParameters:expirytime,payeeaddress

### ● OptionalParameters:maximumsbscriptionamount

### Link(testnet) :

### https://ranchimallflo-testnet.ranchimall.net/api/v2/smartContractInfo?contractName=stud

### ents-token-crowdfunding&contractAddress=of3v1U84JemDzqPnNwsqmXZzHN2y3JFyt

### ResponseFormat :JSON

### JSONResponse:

```
{
"contractAddress":"of3v1U84JemDzqPnNwsqmXZzHN2y3JFyt9",
"contractInfo":{
"closeDate":"1696007853",
"contractAddress":"of3v1U84JemDzqPnNwsqmXZzHN2y3JFyt9",
"contractName":"students-token-crowdfunding",
"contractSubtype":"time-trigger",
"contractType":"one-time-event",
"expiryDate":"1696007853",
"expiryTime":"frisep 292023 22:43:00gmt+0530(indiastandardtime)",
"flodata":"CreateasmartcontractofthenameStudents-token-crowdfunding@ofthetypeone-time-event*
usingassetbioscope#attheFLOaddressof3v1U84JemDzqPnNwsqmXZzHN2y3JFyt9$with
contract-conditions:(1)expiryTime=FriSep 292023 22:43:00GMT+0530(IndiaStandardTime)(2)
maximumsubscriptionamount=0.02(3)payeeAddress=
oQotdnMBAP1wZ6Kiofx54S2jNjKGiFLYD7:50:oMunmikKvxsMSTYzShm2X5tGrYDt9EYPij:
end-contract-conditions",
"incorporationDate":"1696007195",
"maximumsubscriptionamount":0.02,
"payeeAddress":{
"oMunmikKvxsMSTYzShm2X5tGrYDt9EYPij":50,
"oQotdnMBAP1wZ6Kiofx54S2jNjKGiFLYD7": 50
},
"status":"closed",
"subtype":"time-trigger",
"tokenIdentification":"bioscope",
"unix_expiryTime":"1696047180.0"
},
"contractName":"students-token-crowdfunding"
}
```
### 11)GET/api/v2/smartContractInfo-

### Parameters :

### ● CompulsoryParameters:expirytime,payeeaddress

### ● OptionalParameters:minimumsubscriptionamount,

### maximumsubscriptionamount,contractamount

### Link(testnet) :

### https://ranchimallflo-testnet.ranchimall.net/api/v2/smartContractInfo?contractName=abc-t

### oken-crowdfunding&contractAddress=oTvJzjA96hb57WakJSMQ8cXfAxCqQCqcKD

### ResponseFormat :JSON

### JSONResponse:

```
{
"contractAddress":"oTvJzjA96hb57WakJSMQ8cXfAxCqQCqcKD",
"contractInfo":{
"closeDate":"1696581615",
"contractAddress":"oTvJzjA96hb57WakJSMQ8cXfAxCqQCqcKD",
"contractAmount":0.0001,
"contractName":"abc-token-crowdfunding",
"contractSubtype":"time-trigger",
"contractType":"one-time-event",
"expiryDate":"1696581615",
"expiryTime":"frioct 062023 14:10:00gmt+0530(indiastandardtime)",
"flodata":"CreateasmartcontractofthenameABC-token-crowdfunding@ofthetypeone-time-event*using
assetbioscope#attheFLOaddressoTvJzjA96hb57WakJSMQ8cXfAxCqQCqcKD$withcontract-conditions:
(1)expiryTime=FriOct 062023 14:10:00GMT+0530(IndiaStandardTime)(2)contractamount=0.0001(3)
minimumsubscriptionamount=0.0003(4)maximumsubscriptionamount=0.0005(5)payeeAddress=
oQotdnMBAP1wZ6Kiofx54S2jNjKGiFLYD7:100end-contract-conditions",
"incorporationDate":"1696579986",
"maximumsubscriptionamount":0.0005,
"minimumsubscriptionamount":0.0003,
"payeeAddress":{
"oQotdnMBAP1wZ6Kiofx54S2jNjKGiFLYD7": 100
},
"status":"closed",
"subtype":"time-trigger",
"tokenIdentification":"bioscope",
"unix_expiryTime":"1696621200.0"
},
"contractName":"abc-token-crowdfunding"
}
```
### 12)GET/api/v2/smartContractInfo-

### Parameters :

### ● CompulsoryParameters:expirytime,payeeaddress

### ● OptionalParameters:minimumsubscriptionamount,maximumsubscriptionamout


### Link(testnet) :

### https://ranchimallflo-testnet.ranchimall.net/api/v2/smartContractInfo?contractName=ghi-t

### oken-crowdfund&contractAddress=oQe3V3UttSnGm6PRxz8Go8Dv8cYSSJ11u

### ResponseFormat :JSON

### JSONResponse:

```
{
"contractAddress":"oQe3V3UttSnGm6PRxz8Go8Dv8cYSSJ11u7",
"contractInfo":{
"closeDate":"1696586151",
"contractAddress":"oQe3V3UttSnGm6PRxz8Go8Dv8cYSSJ11u7",
"contractName":"ghi-token-crowdfund",
"contractSubtype":"time-trigger",
"contractType":"one-time-event",
"expiryDate":"1696586151",
"expiryTime":"frioct 062023 15:25:00gmt+0530(indiastandardtime)",
"flodata":"CreateasmartcontractofthenameGHI-token-crowdfund@ofthetypeone-time-event*using
assetbioscope#attheFLOaddressoQe3V3UttSnGm6PRxz8Go8Dv8cYSSJ11u7$with
contract-conditions:(1)expiryTime=FriOct 062023 15:25:00GMT+0530(IndiaStandardTime)(2)
minimumsubscriptionamount=0.0003(3)maximumsubscriptionamount=0.0005(4)payeeAddress=
oQotdnMBAP1wZ6Kiofx54S2jNjKGiFLYD7:100end-contract-conditions",
"incorporationDate":"1696585118",
"maximumsubscriptionamount":0.0005,
"minimumsubscriptionamount":0.0003,
"payeeAddress":{
"oQotdnMBAP1wZ6Kiofx54S2jNjKGiFLYD7": 100
},
"status":"closed",
"subtype":"time-trigger",
"tokenIdentification":"bioscope",
"unix_expiryTime":"1696625700.0"
},
"contractName":"ghi-token-crowdfund"
}
```
## Continuouseventsmartcontracts-

### 1) GET/api/v2/smartContractInfo-

### Parameters :

### ● CompulsoryParameters:subtype-token-incorp,accepting_token

### ● OptionalParameters:selling_token,pricetype,price

### Link(testnet) :

### https://ranchimallflo-testnet.ranchimall.net/api/v2/smartContractInfo?contractName=swap-

### rupee-bioscope&contractAddress=oTzrcpLPRXsejSdYQ3XN6V4besrAPuJQrk

### ResponseFormat :JSON

### JSONResponse :

```
{
"contractAddress":"oTzrcpLPRXsejSdYQ3XN6V4besrAPuJQrk",
"contractInfo":{
"acceptingToken":"rupee",
"accepting_token":"rupee",
"contractAddress":"oTzrcpLPRXsejSdYQ3XN6V4besrAPuJQrk",
"contractName":"swap-rupee-bioscope",
"contractSubtype":"tokenswap",
"contractType":"continuos-event",
"currentDepositBalance":0,
"flodata":"CreateSmartContractwiththenameswap-rupee-bioscope@ofthetypecontinuous-event*atthe
addressoTzrcpLPRXsejSdYQ3XN6V4besrAPuJQrk$withcontract-conditions:(1)subtype=tokenswap(2)
accepting_token=rupee#(3)selling_token=bioscope#(4)price='0.4'(5)priceType=predetermined
end-contract-conditions",
"numberOfDeposits":2,
"numberOfParticipants":0,
"price":0.4,
"priceType":"predetermined",
"pricetype":"predetermined",
"sellingToken":"bioscope",
"selling_token":"bioscope",
"subtype":"tokenswap",
"totalHonorAmount":null,
"totalParticipationAmount":null
},
"contractName":"swap-rupee-bioscope"
}
```


