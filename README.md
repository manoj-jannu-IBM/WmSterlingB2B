# WmSterlingB2B
 webMethods package to enable integration with Sterling B2B. Provides 4 services that can be used to decode request received from Sterling B2B, as well as services to update Sterling with the result of local processing
 
 ## Setup
 
 Update the following 3 package variables to configure the endpoint and credentials for the Sterling B2B server
 
 - **sterling.endpoint.url**: endpoint for tenant
 - **sterling.endpoint.clientid**: client id
 - **sterling.endpoint.clientsecret**: client secret
 
 ## Services
 
 ### decode
 Converts the encoded payload into a document that can then be used in webMethods workflow or flow services
 
 ### log
 Updates the Sterling B2B tenant with the current processing status
 
 ### submit
 Sends back the response as a json document for processing in Sterling B2B
 
 ### finish
 Flags to Sterling B2B that integration has completed 
 
 ## Resources
 
 You can find the Open API 3.0 definition for the Sterling B2B API in the resources directory - sterling.yml
 There is also a sample workflow showing how to use these sevices that you can import into your IWHI tenant - workflow-sterling-template.zip
 
 
