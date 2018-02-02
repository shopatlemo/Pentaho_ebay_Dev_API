* Pentaho eBay API for Merchants.
* This is for eBay API designed in Pentaho Kettle.  
* Use to Integerate for small/middle/large merchants who does business with eBay from backend
* This example contains Trading API, Shopping API and Finding API

* Pre-requisites:
* You need Pentaho community edition software  (download from http://community.pentaho.com/  --> data integration)
* Download sun based java from https://java.com/en/download/
* Please set java_home, kettle_home directory appropriately.  Kettle_home is the directory where you installed pentaho.  This is where your kettle.properties file will be created.
* You need to signup and generate ebay keys for both sandbox and production  (https://go.developer.ebay.com/)
* Once generated the ebay keys, you need to add them in kettle.properties file (pentaho data integration).  They are located in \<Pentaho Home DIr\>/.kettle directory

* cut and paste the below lines into kettle.properties 
* and add your keys from ebay website
* ====================================================
* # eMail 
* EM_TO_ADDRESS=\<your company email group if any\>
* EM_FROM_ADDRESS=\<your company email\>
* EM_FROM_NAME=\<your email name\>
* EM_SMTP_SERVER=\<your email server\>
* EM_SMTP_PORT=\<your email port\>
* EM_SMTP_AUTH_USER=\<your email user name\>
* EM_SMTP_AUTH_PASS=\<your password\>
* EM_SUBJ_SUCCESS=OK
* EM_SUBJ_FAIL=FAIL

* #eBay General Parameters.
* EBAY_SHOP_NAME=\<Your shop Name\>

* #eBay API SandBox
* EBAY_SANDBOX_DEV_NAME=\<You Sandbox Dev ID\>
* EBAY_SANDBOX_APP_NAME=\<Your Sandbox App ID\>
* EBAY_SANDBOX_CERT_NAME=\<Your Sandbox Cert ID\> 
* EBAY_SANDBOX_AUTH_TOKEN=\<Your Sandbox Auth Token\>
* EBAY_SANDBOX_TRADING_API_URL=https://api.sandbox.ebay.com/ws/api.dll
* EBAY_SANDBOX_SHOPPING_API_URL=http://open.api.sandbox.ebay.com/shopping
* EBAY_SANDBOX_FINDING_API_URL=http://svcs.sandbox.ebay.com/services/search/FindingService/v1


* # eBay API Prod
* EBAY_PROD_DEV_NAME=\<You Prod Dev ID\>
* EBAY_PROD_APP_NAME=\<Your Prod App ID\>
* EBAY_PROD_CERT_NAME=\<Your Prod Cert ID\> 
* EBAY_PROD_AUTH_TOKEN=\<Your Prod Auth Token\>
* EBAY_PROD_TRADING_API_URL=https://api.ebay.com/ws/api.dll
* EBAY_PROD_SHOPPING_API_URL=http://open.api.ebay.com/shopping
* EBAY_PROD_FINDING_API_URL=http://svcs.ebay.com/services/search/FindingService/v1

# Integrate to Jenkins test
