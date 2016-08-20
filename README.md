# Pentaho_ebay_Dev_API
This is for eBay API designed in Pentaho Kettle.  
Use to Integerate for small/middle/large merchants who does business with eBay

Pre-requisites:
1) You need Pentaho community edition software  (download from http://community.pentaho.com/  --> data integration)
2) Download sun based java from https://java.com/en/download/
3) Please set java_home, pentaho_home directory appropriately
4) You need to signup and generate ebay keys for both sandbox and production  (https://go.developer.ebay.com/)
5) Once generated the ebay keys, you need to add them in kettle.properties (pentaho data integration)

cut and paste the below lines into kettle.properties

#====================================================
#Mail 
EM_TO_ADDRESS=<your company email>
EM_FROM_ADDRESS=<your company email>
EM_FROM_NAME=<your email name>
EM_SMTP_SERVER=<your email server>
EM_SMTP_PORT=<your email port>
EM_SMTP_AUTH_USER=
EM_SMTP_AUTH_PASS=
EM_SUBJ_SUCCESS=OK
EM_SUBJ_FAIL=FAIL

# Ebay General Parameters.
EBAY_SHOP_NAME=<Your shop Name>

# ebay API SandBox
EBAY_SANDBOX_DEV_NAME=<You Sandbox Dev ID>
EBAY_SANDBOX_APP_NAME=<Your Sandbox App ID>
EBAY_SANDBOX_CERT_NAME=<Your Sandbox Cert ID> 
EBAY_SANDBOX_AUTH_TOKEN=<Your Sandbox Auth Token>
EBAY_SANDBOX_TRADING_API_URL=https://api.sandbox.ebay.com/ws/api.dll
EBAY_SANDBOX_SHOPPING_API_URL=http://open.api.sandbox.ebay.com/shopping
EBAY_SANDBOX_FINDING_API_URL=http://svcs.sandbox.ebay.com/services/search/FindingService/v1


# ebay API Prod
EBAY_PROD_DEV_NAME=<You Prod Dev ID>
EBAY_PROD_APP_NAME=<Your Prod App ID>
EBAY_PROD_CERT_NAME=<Your Prod Cert ID> 
EBAY_PROD_AUTH_TOKEN=<Your Prod Auth Token>
EBAY_PROD_TRADING_API_URL=https://api.ebay.com/ws/api.dll
EBAY_PROD_SHOPPING_API_URL=http://open.api.ebay.com/shopping
EBAY_PROD_FINDING_API_URL=http://svcs.ebay.com/services/search/FindingService/v1

#===================================================================================



