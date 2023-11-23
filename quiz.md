## Long Quiz in Advanced Systems Integration & Architecture
1. Define Service Oriented Architecture (SOA).  
- Service Oriented Architecture is an Enterprise-Wide software development technique that utilizes reusable components called services.  
Each service are self contained modules that perform specific functions, allowing for mixing and matching of components in order to build applications.  
In short, SOA is an architecture that connects and matches different services to produce new applications, similar to how Lego builds structures using pre-defined bricks.


2. List and discuss the characteristics of SOA.  
- Standardized Service Contracts:  
Each service module follows a service description which dictates what the service is for and what it can and cannot do.

- Loose Coupling:  
The services must be independent or at least have minimal dependencies with each other. Ensuring that each module is usable on its own.

- Abstraction:  
The nitty and gritty details of the services are hidden or "abstracted" from public view ensuring that how the service works remains a mystery for security purposes.

- Service Reusability:  
Each service must be reusable, meaning that the components can be extracted and mixed and matched with different modules without sacrificing on functionality.

- Autonomy:  
Each service is self governing, having full control on its functions independently. In short, the service is isolated.

- Statelessness:  
The service must be stateless, and not hold/keep a specific stated of being. Meaning, that each service should always be a blank slate.

- Discoverability:  
Services are discoverable/findable. Meaning that the user can search for the services using the registry or via its metadata.

- Composability:  
Each service must breakdown large problems into smaller ones. Being efficient in individual execution, exhibiting a divide and conquer strategy.

- Interoperability:  
Each service must be interoperable not just focusing on one subscriber but allow a multitude of them to utilize the service.


3. Define Microservices.  
- Microservices are similar to SOA but differ in scope as microservices operate on a smaller scale.  
Typically focusing on an individual application, and use a cloud native architectural approach.  
Still Microservices builds individual applications using smaller services, just on a smaller scale.  
 

4. List and discuss the benefits of using Microservices.  
- Independently Deployable:  
Microservices are ready to use/deploy without the need to rely on other services as it is independently functioning on its own.

- Right Tool For The Job:  
Being independent means that each module can be specialized to a specific task or problem.

- Precise Scaling:  
Since it is made up of smaller services scaling is fine tuned as services can be added based on necessity.


5. List and discuss the similarities and differences of SOA and Microservices.  
Similarities:  
- Made up of Services:  
Both SOA and Microservices use services as components in order to create applications.

- Loose Coupling:  
Both SOA and Microservices push for independence between services.

Differences:  
- Scope:  
SOA is enterprise-wide while Microservices is application specific. In layman's term SOA is broader in scope while Microservices is on a smaller scale hence why it is "micro".

- Way of Reusing:  
SOA Reuse the integrations themselves resulting in pure reusing, while in Microservices reusing is done via copying of code and data duplication.

- Synchronous Calls:  
SOA utilize synchronous protocols since it is available throughout the entire enterprise, while Microservices use asynchronous communication.

- Data Duplication:  
As stated previously SOA is synchronous meaning that no data is duplicated and changes are made at the source, while Microservices specifically pushes duplication in order to maintain indipendence.

- Communication:  
Each service is entirely independent in Microservices, in SOA on the otherhand, there must be a common communication protocol.

- Interoperability:  
Microservices focus and strictly adheres to lightweight messaging protocols, while SOA is more loose and use heterogenous messaging protocols.

- Service granularity:  
Microservices as stated before is highly specialized, while SOA is more of a mixed bag having specialized, small, and enterprise-wide services.

- Speed:  
Microservices tend to operate at a much quicker rate compared to SOA.


6. Define Web Services.  
- Web Services are applications, software, or service that can be accessed by users using the internet. They are dynamic, modular, distributed,  
and self-contained apps that use a standardized messaging system, and facilitates data exchange with different apps and systems regardless of  
programming language or platform that it is being run on all being available via the internet.


7. List and discuss the benefits of using Web Services.  
- Exposing the Existing Function on the network:  
Web Services allow the use of HTTP requests over the internet. Meaning that, functionality of your code can be exposed and utilized by other  
applications so long as they make HTTP requests.

- Interoperability:  
Web Services isolates application platform and technology making them independent. Meaning that, Web Services allows for data exchange,  
communication, and service sharing with various apps regardless of their platform or technology that the application was built on.

- Standardized Protocol:  
Web Services utilize industry-standard protocols when it comes to communication. Meaning that, the business gain boons like increase in  
choices, significant cost reduction, and quality increase all because the protocol stack is well defined using industry-standards.

- Low Cost Communication:  
Web Services although allowing HTTP requests, utilize SOAP (Simple Object Access Protocol) which then in turn allow low-cost internet  
to implement web services. This is a cheaper alternative compared to EDI/B2B(Electronic Data Interchange/Business to Business  
Furthermore, aside from SOAP, FTP(File Transfer Protocol) can also be implemented as a reliable low cost transport mechanism.


8. List and discuss the characteristics of Web Services.  
- XML-Based:  
Utilizing XML in both data representation and data transportation layers, it allows for web services to be interoperable.  
Since it allows for any binding in platform, networking, or operating systems to be non-existent.

- Loosely Coupled:  
The user is not bound to the Web Service. Meaning that, as a consequence of the server logic and client logic being loosely  
tied together, any changes in the Web Service will not compromise/affect the access of the user to that web-service.

- Coarse-Grained:  
Web Services allows definition of coarse-grained services that access just the right amount of business logic naturally.  
Meaning that, Object-Oriented Technologies can expose businesses and interfaces that should be coarse-grained much more effectively.

- Ability to be Synchronous or Asynchronous:  
Web Services allow the utilization of both synchronous and asynchronous operations. Meaning that, data exchange can be retrieved  
at a later point in time or when the service has been completed, which in turn allows loosely coupled systems to exist as  
asynchronous capabilities are vital to them.

- Supports Remote Procedure Calls:  
Web Services allow the invoking of procedures, functions, and methods remotely. Meaning that, remote objects and procedures can  
be exposed to input and output paramaters via XML-based procedures.

- Supports Document Exchange:  
Web Services allow document exchanging in a completely transparent manner. Since, XML represents complex documents and data in a generic way.


9. List and discuss the distinct roles in Web Services Architecture.  
- Provider:  
They create the Web Service and makes that service available for use. In short, the Provider provides a usable Web Service.

- Requestor:  
This is the client or client application that needs the Web Service. In short, the Requestor requests the Web Service.

- Broker:  
This is the application that povides the Requestor access to the UDDI(Universal Description, Discovery and Integration). In short  
the Broker is the bridge/middleman.


10. List and discuss the Web Services Components.  
- SOAP(Simple Object Access Protocol):  
This is a communication protocol that has the ability to run on any app and allow server firewalls. This protocol describes the  
encoding process of an HTTP header and an XML file to facilitate communication between two computers. Furthermore, this protocol  
is completely independent in both platform and language.

- WSDL(Web Services Description Language):  
This XML-based language allows the description of web services and the method of how they can be accessed. This is a very important  
part of the next component(UDDI) that facilitates business and service listing via the internet. Furthermore, this also navigates  
service access for both individuals and businesses.

- UDDI(Universal Description, Discovery and Integration):  
This describes, finds, and publishes web services making them ready for use. UDDI works hand-in-hand with both SOAP and WSDL as a  
cornerstone standard of Web Services. Furthermore, UDDI is the specification when it comes to the distributed registry of Web Services.