This is a fork of https://github.com/FozzTexx/tcpser  

It's maybe one of the most uselses fork for this project.  
I just wanted to add ATI command because it looks cool on windows.  
I follow the AT Commands Reference Guide pdf  

ATI[N]  
    0 - numerical identifier.  
    1 - module checksum  
    2 - checksum check result  
    3 - manufacturer  
    4 - product name  
    5 - DOB version   
    
you can set it to what ever you want by changing those line :

```
mdm_responses[MDM_RESP_ATI_NUMERICAL_IDENTIFIER] = ""; // Must be 3 digit 
mdm_responses[MDM_RESP_ATI_CHECKSUM] = "";
mdm_responses[MDM_RESP_ATI_MANUFACTURER] = "";
mdm_responses[MDM_RESP_ATI_PRODUCT_NAME] = "";
mdm_responses[MDM_RESP_ATI_DOB_VERSION] = "";
```
![image](https://user-images.githubusercontent.com/58639121/116122460-1a4c3400-a6c2-11eb-8c98-bedb8bd2b1d0.png)
