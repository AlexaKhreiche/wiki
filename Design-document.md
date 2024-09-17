## Introduction

<!-- TODO: Provide a Product Description.

- Describe why the software (or upgrade) is being developed,  
- List the most important features and capabilities,  
- What is the software project intended to accomplish (objectives) 

This section should also summarize the decision to develop software of a particular type. 
For some software types, certain sections are not applicable
 -->


## Assumptions and Constrains

### Assumptions

<!-- TODO: Provide a list of assumptions that are made in the design of the software.

Assumptions are statements about future situations, beyond the control of the project, 
whose outcome influence the success of a project. Identify basic assumptions upon which 
the specific software requirements depend such that if the assumptions change, the 
requirements also change.

Assumptions include:  
- Availability of a hardware / software platform  
- Developments in technology  
- Availability of personnel 
- Availability of specific equipment
 -->

### Constraints

<!-- TODO: Provide a list of constraints that are imposed on the design of the software.

Constraints are conditions outside the control of the project that limit the design 
alternatives. Describe any high level items that limit the developer's options for designing 
the software such as: 
- Standards (including hardware and software) Imposed on the Solution  
- Schedule  
- Budget  
- Preferred Software Programming Language(s)  
- Required Development Tools  
- Handling of Security Requirements (if any)  
- Potential Risks 
- Policy and Regulation
 -->

## General System Description

### System Context

<!-- TODO: Describe the functions of each component and identify the respective interfaces (frontend, backend, database)
 -->

### Infrastructure Architecture design

<!-- TODO: Draw a diagram that depicts the infrastructure architecture design of the system for each environment. Below, provide a description of all the necessary components, include a description of the configuration that will be enabled for each infrastructure component.

Reference links:
- Basic web application: https://learn.microsoft.com/en-us/azure/architecture/web-apps/app-service/architectures/basic-web-app
- Scalable web and mobile applications using Azure Database for PostgreSQL: https://learn.microsoft.com/en-us/azure/architecture/solution-ideas/articles/scalable-web-and-mobile-applications-using-azure-database-for-postgresql
- Azure Well-Architected Framework perspective on Azure App Service (Web Apps): https://learn.microsoft.com/en-us/azure/well-architected/service-guides/app-service-web-apps
- Azure Well-Architected Framework review - Azure Database for PostgreSQL: https://learn.microsoft.com/en-us/azure/well-architected/service-guides/postgresql
- Azure App Service: https://learn.microsoft.com/en-us/azure/app-service/overview
- Azure Database for PostgreSQL: https://learn.microsoft.com/en-us/azure/postgresql/flexible-server/service-overview
-->

### Environments design

<!-- TODO: Describe the environments the proposed system requires: local development environment, cloud  development environment and user acceptance test environment.

Describe the purpose of each environments and the components they are made of.
-->

### Release strategy

<!-- TODO: Describe how you have designed your release strategy. Include a description of the elements you need in order to deploy your code and infrastructure to each of the environments you have defined.
-->
## Functional requirements

<!-- TODO: describe 20 functional requirements. These requirements should describe high-level business functions performed by the system. Each requirement should be uniquely numbered and identified for traceability.  
- Describe engineering algorithms and business rules to be used in general terms  
- Describe sources of inputs (manual data entry, read files, etc.) 
- Describe the range of validity of input and validation  
- Describe any processing requirements: such as validity checks, sequence of operations, error handling, or responses to abnormal situations and degraded operations  
- Describe the outputs required: such as report formats, plotting, etc. 
- Requirements Traceability Matrix: A Requirements Traceability Matrix (RTM) helps track the requirements and features of the software throughout the software process.
-->

## Non-functional requirements

### Security

<!-- TODO: describe 5 non functional requirements for application system security controls applied for each environment;

Reference links:
- Azure App Service: https://learn.microsoft.com/en-us/azure/app-service/overview-security
- Azure Database for PostgreSQL: https://learn.microsoft.com/en-us/azure/postgresql/flexible-server/concepts-security
-->

### Availability and reliability

<!-- TODO: describe 5 non functional requirements for system availability, which is the time when the application must be available for use and times that are most acceptable for maintenance; and for system reliability, which is the probability that the system will operate without failure over a specified time period. Reliability aims to minimize system failures and downtime, while availability aims to maximize operational time.

Reference links:
- Service Level Agreements (SLA) for Azure Services: https://www.microsoft.com/licensing/docs/view/Service-Level-Agreements-SLA-for-Online-Services?lang=1
- Product availability: https://azure.microsoft.com/en-us/explore/global-infrastructure/products-by-region/
- Azure reliability documentation: https://learn.microsoft.com/en-us/azure/reliability/overview
- Reliability guides by service: https://learn.microsoft.com/en-us/azure/reliability/overview-reliability-guidance
- Azure App Service: https://learn.microsoft.com/en-us/azure/reliability/reliability-app-service?tabs=cli#availability-zone-support
- PostgreSQL: https://learn.microsoft.com/en-us/azure/reliability/reliability-postgresql-flexible-server

-->

### Recoverability

<!-- TODO: describe 5 non functional requirements for system recoverability, which is the ability to restore the system to a specified operational level after a disaster or other failure. Recoverability aims to minimize the time and data lost during a system failure.

Reference links:
- Disaster recovery overview: https://learn.microsoft.com/en-us/azure/reliability/disaster-recovery-overview
- Azure App Service: https://learn.microsoft.com/en-us/azure/reliability/reliability-app-service?tabs=cli#availability-zone-support
- PostgreSQL: https://learn.microsoft.com/en-us/azure/reliability/reliability-postgresql-flexible-server
-->

### Business Continuity

<!-- TODO: describe 5 non functional requirements for business continuity, which is the ability of an organization to maintain essential functions during, as well as after, a disaster has occurred. Business continuity aims to minimize the impact of a disaster on the organization.

Reference links:
- Business Continuity Management Program: https://learn.microsoft.com/en-us/azure/reliability/business-continuity-management-program
-->

### Cost management

<!-- TODO: describe 5 non functional requirements for cost management, which is the process of planning and controlling the budget of a project or business. Cost management aims to minimize the cost of the project or business.

Reference links:
- Gets started: Manage cloud costs: https://learn.microsoft.com/en-us/azure/cloud-adoption-framework/get-started/manage-costs
- Azure App Service: https://azure.microsoft.com/en-us/pricing/details/app-service/linux
- PostgreSQL: https://azure.microsoft.com/en-us/pricing/details/postgresql/flexible-server/
-->

### System maintenance and support

<!-- TODO: describe 5 non functional requirements for system maintenance and support, which is the process of maintaining and supporting the system for end users in production. System maintenance and support aims to minimize the time and effort required to maintain and support the system.

Reference links:
- Azure Monitor overview: https://learn.microsoft.com/en-us/azure/azure-monitor/overview
- Azure Application Insights overview: https://learn.microsoft.com/en-us/azure/azure-monitor/app/app-insights-overview
- Overview of Log Analytics in Azure Monitor: https://learn.microsoft.com/en-us/azure/azure-monitor/logs/log-analytics-overview
- Apply design principles and advanced operations: https://learn.microsoft.com/en-us/azure/cloud-adoption-framework/manage/design-principles
- Workload operations in cloud management: https://learn.microsoft.com/en-us/azure/cloud-adoption-framework/manage/considerations/workload

-->

## Software modelling

### Use Case and Sequential model

<!-- TODO: Add at least 3 use case and sequence diagram/s and explain each use case. This sample table can be useful to qualify each use case.

| Use Case Name | Register User |
| --- | --- |
| Summary | In order to get personalized or restricted information, place orders or do other specialized transactions a new user must register a username and password.
| Basic Flow |  <ol><li> The use case start when a user indicates that he wants to register.</li><li>The system requests a username and password.</li><li>The user enters a username and password.</li><li>The system checks that the username does not duplicate any existing registered usernames.</li><li>The system requests a name (*), street, city, state, zipcode(*), phone and email address. Items marked by (*) are required.</li><li>The user enters the information.</li><li>The system determines the user's location and access level and stores all user information.</li><li>The system executes use case Register Preferences.</li><li>The system starts a login session and displays a welcome message based on the user's preferences.</li></ol>
| Alternative Flows | <ul><li>Step 4: If the username duplicates an existing username the system displays a message and the use case goes back to step 2.</li><li>Step 5: If the user does not enter a required field, a message is displayed and the use case repeats step 4.
| Extension Points | Register Preferences
| Preconditions | none |
| Postconditions | The user can now obtain data and perform functions according to his registered access level.
| Business Rules | <ul><li>A registered user's location is the SBE location nearest his zip code.</li><li>Access levels are</li><ul><li>0: A user can access only data classification 0</li><li>1: The user can access data classification <= 1</li><li>2: The user can access data classification <= 2</li></ul></li></ul><br/>The default access level is 0

Reference links:
- Visual paradigm: https://online.visual-paradigm.com/app/diagrams/

-->

### Entity relationship diagram

<!-- TODO: Add an entity relationship diagram that represents the data model of the system. -->

### Data flow diagram

<!-- TODO: Add a data flow diagram that represents the data flow of the system. -->

## Software Quality Assurance (SQA) requirements

### Test plan

<!-- TODO: The following Test Plan sections contain a project-specific description of testing for this project.
- Testing Approach: A general overview of the plan for testing the entire system is given here. Included are how each major group of software features will be tested, major testing activities, techniques, and testing tools to be used.
- Tests to be Performed: This describe a detailed explanation of the tests that have been developed for the system, including links to each of the tests and to the test results.
-->
