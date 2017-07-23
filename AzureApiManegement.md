## Azure API Management L200 complete guide:

L100: 
1.	API Management white papers: It contains basic requirement and challenges for APIs to be managed. Why we need API.
Common API Requirements and Challenges
Gain Insight and Control with an API Management Platform
API Management: In the Cloud vs. On-Premises 
Azure API Management: Cloud-based API Management from a Trusted Enterprise Technology Partner
http://download.microsoft.com/download/6/f/1/6f197bb5-f46e-4678-92df-5a32ecd6f18d/microsoft_azure_api_management_white_paper_20150520.pdf 

2.	What is Azure API management? https://docs.microsoft.com/en-us/azure/api-management/api-management-key-concepts 
3.	What is Postman https://www.getpostman.com/  How to make requests using Postman.
4.	What is Fiddler http://www.telerik.com/fiddler  How to capture traffic using Fiddler (specially https decoded)
5.	What is swagger https://swagger.io/ . Why we need swagger and swagger definition file.
6.	What are backend API? How to create sample backend api using MVC API.
https://www.codeproject.com/Articles/1078249/RESTful-Web-API-Help-Documentation-using-Swagger-U
7.	How to generate sample swagger file for the backend API https://www.codeproject.com/Articles/1078249/RESTful-Web-API-Help-Documentation-using-Swagger-U 
8.	How to create first APIM service in azure portal. https://docs.microsoft.com/en-us/azure/api-management/api-management-get-started#a-namecreate-service-instance-acreate-an-api-management-instance 
Guidance https://docs.microsoft.com/en-us/azure/architecture/best-practices/api-implementation 
9.	Importing your backend APIs in to APIM https://docs.microsoft.com/en-us/azure/api-management/api-management-get-started#a-namecreate-api-aimport-an-api 
10.	How to call  the backend API using developer portal https://docs.microsoft.com/en-us/azure/api-management/api-management-get-started#a-namecall-operation-acall-an-operation-from-the-developer-portal 
11.	How to analyse the calls using built in analytics. https://docs.microsoft.com/en-us/azure/api-management/api-management-get-started#a-nameview-analytics-aview-analytics 
12.	First filter on API call, using rate limit on an API https://docs.microsoft.com/en-us/azure/api-management/api-management-howto-product-with-rules 
13.	Caching in APIM https://docs.microsoft.com/en-us/azure/api-management/api-management-howto-cache 
14.	Trace calls https://docs.microsoft.com/en-us/azure/api-management/api-management-howto-api-inspector 
15.	Training videos https://azure.microsoft.com/en-us/resources/videos/index/?services=api-management 

L200:
1.	Securing the APIs: 
AAD https://docs.microsoft.com/en-us/azure/api-management/api-management-howto-protect-backend-with-aad 
Vnet https://docs.microsoft.com/en-us/azure/api-management/api-management-using-with-vnet , https://docs.microsoft.com/en-us/azure/api-management/api-management-using-with-internal-vnet
Application Gateway https://docs.microsoft.com/en-us/azure/api-management/api-management-howto-integrate-internal-vnet-appgateway
Certificates https://docs.microsoft.com/en-us/azure/api-management/api-management-howto-mutual-certificates
Authenticate Developer accounts using AAD https://docs.microsoft.com/en-us/azure/api-management/api-management-howto-aad 
Authenticate developer accounts using AAD B2C https://docs.microsoft.com/en-us/azure/api-management/api-management-howto-aad-b2c 
Delegation https://docs.microsoft.com/en-us/azure/api-management/api-management-howto-setup-delegation 
OAuth2.0 https://docs.microsoft.com/en-us/azure/api-management/api-management-howto-oauth2 
User based Access Control https://docs.microsoft.com/en-us/azure/api-management/api-management-role-based-access-control 


2.	Policies :
Custom caching https://docs.microsoft.com/en-us/azure/api-management/api-management-sample-cache-by-key 
Log to event hub  https://docs.microsoft.com/en-us/azure/api-management/api-management-log-to-eventhub-sample
https://docs.microsoft.com/en-us/azure/api-management/api-management-howto-log-event-hubs 
Request Throttling https://docs.microsoft.com/en-us/azure/api-management/api-management-sample-flexible-throttling
External Services: https://docs.microsoft.com/en-us/azure/api-management/api-management-sample-send-request 
Calling External Services with Json/XML body. No online document available, I will write a blog on this.
Other Policies: https://docs.microsoft.com/en-us/azure/api-management/api-management-policy-reference 
https://docs.microsoft.com/en-us/azure/api-management/api-management-howto-policies
Properties: https://docs.microsoft.com/en-us/azure/api-management/api-management-howto-properties 
Client Certificate Authentication https://docs.microsoft.com/en-us/azure/api-management/api-management-howto-mutual-certificates-for-clients 
JWT Policy for security: https://docs.microsoft.com/en-us/azure/api-management/api-management-access-restriction-policies#ValidateJWT 
JWT token generation: https://stormpath.com/blog/jwt-java-create-verify , https://auth0.com/docs/tutorials/generate-jwt-dotnet
Policy Expressions https://docs.microsoft.com/en-us/azure/api-management/api-management-policy-expressions 

3.	Customizing Developer portal:
Page Layout https://docs.microsoft.com/en-us/azure/api-management/api-management-modify-content-layout 
Styling https://docs.microsoft.com/en-us/azure/api-management/api-management-customize-styles 
Using Templates: https://docs.microsoft.com/en-us/azure/api-management/api-management-developer-portal-templates 

4.	Email notification templates https://docs.microsoft.com/en-us/azure/api-management/api-management-howto-configure-notifications 
5.	Manage developers accounts using groups https://docs.microsoft.com/en-us/azure/api-management/api-management-howto-create-groups 
6.	Multi region support in APIM https://docs.microsoft.com/en-us/azure/api-management/api-management-howto-deploy-multi-region 
7.	Backup and Restore https://docs.microsoft.com/en-us/azure/api-management/api-management-howto-disaster-recovery-backup-restore 
8.	Managing User accounts https://docs.microsoft.com/en-us/azure/api-management/api-management-howto-create-or-invite-developers 
9.	Powershell commands https://azure.microsoft.com/en-us/updates/full-set-of-windows-powershell-cmdlets-for-azure-api-management-api/ 
10.	Configure APIM using GIT https://docs.microsoft.com/en-us/azure/api-management/api-management-configuration-repository-git 
11.	Activity logs https://docs.microsoft.com/en-us/azure/api-management/api-management-howto-use-azure-monitor 
12.	APIM REST APIs https://docs.microsoft.com/en-us/rest/api/apimanagement/ 
13.	APIM Templates:
APIs  https://docs.microsoft.com/en-us/azure/api-management/api-management-api-templates 
Products https://docs.microsoft.com/en-us/azure/api-management/api-management-product-templates 
Application https://docs.microsoft.com/en-us/azure/api-management/api-management-application-templates 
Issues https://docs.microsoft.com/en-us/azure/api-management/api-management-issue-templates 
User Profile https://docs.microsoft.com/en-us/azure/api-management/api-management-user-profile-templates 
Pages https://docs.microsoft.com/en-us/azure/api-management/api-management-page-templates , https://docs.microsoft.com/en-us/azure/api-management/api-management-page-controls 
Template Model reference https://docs.microsoft.com/en-us/azure/api-management/api-management-template-data-model-reference 
String resources https://docs.microsoft.com/en-us/azure/api-management/api-management-template-resources 

14.	RBAC functionality  https://blogs.msdn.microsoft.com/katriend/2015/12/21/using-the-azure-api-management-rest-api-as-workaround-to-rbac-functionality/ 
15.	Consuming SOAP/WCF services http://mostlydotnetdev.blogspot.in/2015/03/azure-api-management-apim-consuming.html 
16.	Integration with ADFS. Active Directory Federation Services https://phvbaars.wordpress.com/2016/02/06/using-adfs-in-api-management/ 

17.	CORS in APIM:
Cross Origin Resource Sharing. https://docs.microsoft.com/en-us/azure/api-management/api-management-cross-domain-policies#CORS  
JSONP: “Adds JSON with padding (JSONP) support to an operation or an API to allow cross-domain calls from JavaScript browser-based clients” https://docs.microsoft.com/en-us/azure/api-management/api-management-cross-domain-policies#a-namejsonpa-jsonp 

