#anypnt-usage-metrics-api
This is a utility api build on Mule 4.3.

##Purpose
Provides full view of organization resource usage on click of a button in desired format (csv, json, xml). Provides usage metrics at environment level.

##Key Features
* Provides a scheduler to generate report at regular interval.
* Provides a API facade for realtime interaction and supports below resources.
* Complete resource usage metrics available at a click of a button.
* Supports JSON, CSV & XML response formats.
* Support sending report as attachment via email.
* Feed reports to DB or Tableau to perform visualization on usage trends.
* Support Anypoint credential based authentication. Can be extended to support SAML assertion based authentication.
* Provides useful metrics like worker config, runtime support end date, static ip usage, binary version etc.
* Provides metrics for a particular environment like Dev, QA, UAT... (Sandbox) and Prod.
* Provides vCore and active runtime being used for an environment.

##Direction to use

Replace below properties with actual values
* Provide Anypoint credential if intend to use schedule job flow - anypnt.userName,anypnt.password
* email details - errorEmail.from,errorEmail.to,bizEmail.from,smtp.endpoint

##License Type
Open Source.
