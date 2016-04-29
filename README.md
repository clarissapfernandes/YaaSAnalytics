# SAP YaaS Analytics Extension
==========================================================

YaaS is a cloud platform that allows everyone to easily develop, extend and sell services and applications. YaaS exposes REST Based API’s with OAuth 2.0 authorization.
SAP Lumira supports consumption of different data sources to create data sets but does not support REST based web services with OAuth 2.0 functionality. YaaS exposes  its web services which are REST based. The extension gives the users the option to conveniently access YaaS APIs within SAP Lumira. This extension is built with the version 2 Lumira Data Access Extension SDK.  


Install the SAP YaaS Analytics Extension
-----------------
* Open Extension Manager, `File > Extensions`
* Click `Manual Installation`
* Select the zip file from `\docs\YaaSAnalytics.zip`
* Restart SAP Lumira Desktop
* Select `File > New Dataset`
* Select `SAP YaaS Analytics` from the list of connectors


Environment Setup
-----------------
 + SAP Lumira 1.29 and above
 + Java Development Kit 7, Update 75 or later


Third-party libraries
-------------------
* jackson-annotations-2.6.1.jar,
* jackson-core-2.5.4.jar,
* jackson-databind-2.5.4.jar,
* json-20090211.jar,
* org.json_0.0.0.jar,
* slf4j-api-1.7.7.jar

Caveats
-------------------
* Language Support for only English
* Support for only YaaS Json APIs

Resources
-------------------
* SCN - blog post http://scn.sap.com/docs/DOC-72394

License
---------

    Copyright 2015, SAP SE

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.

