# blockchainread blockchain  in three stages  :
1-GET/api​/blockchain :   You can withdraw any blockchain, regardless of the location of the block, if it is in (Contract), so we need permissions to display what is inside the block. 
GET URL:https://api​/blockchain/tokens/(blockchain).
Example :
 input---blockchainURL(https://bscscan.com/token/0x9f19c8e321bd14345b797d43e01f0eed030f5bff)----> 
OUTPUT---------------------------->>
{
  "blockchaindetails": 1,              
  "data": {
    "0x..._0x...": {                 
      "Index": "0",                
      "Hash": "34#$$#@%6FCFGH5EHVC6RF^^",           
  "Data":{// Block details for display

Total Supply:100,000,000 SRG ,
Holders:1,710 addresses,
   Amount =234536457,
}

    },
    // ...
  }
 Transaction
    {  
        FromAddress = 123.34.455, 
        ToAddress = 153.34.455,  
        Amount =234536457, 
       Previous Hash=34#$$#@%6FCFGH5EHVC6RF^^", 
    }  
}

