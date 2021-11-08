# SERVICE ORIENTED ARCHITECTURE

## CONTENT

* Introduction
* SOA Building blocks
* How SOA works
* Benefits of SOA
* Drawbacks of SOA
* References

 ## INTRODUCTION

As the competition within the market is increasing day by day, companies are facing increasing pressure to become more effective and resilient. Organizations should have the flexibility to integrate with diverse data sources and different systems securely. SOA is one of the solutions, is a way of structuring other technologies to achieve tasks.

**The Open Group (2007)** defines SOA as an architectural style that supports service orientation [1]. Service orientation provides a progressive approach to building distributed software that facilitates loosely coupled integration and is flexible to change. Loose coupling means that all the services are independent of each other such that changes in one service will not affect any other. Services are the fundamental building block of SOA. It is like a **black box** to consumers of the service which means a service consumer has no knowledge of what is going inside [2].

## SOA BUILDING BLOCKS

Each of the SOA Building Blocks has three roles :

* Service provider: A service provider is a maintainer and organization of services that create services and makes them available to service users.

* Service repository: Re-use of software services is a very important aspect of SOA for many enterprises. Service repository enables you to maintain and search a database of service descriptions.

* Service requester: It searches for the service required in the service repository and then binds it to the service provider to invoke its services [3].

<p align = "center">
<img src="https://www.oracle.com/a/tech/img/soa-find-bind-execute-paradigm.gif" alt= "SOA building blocks" height = "350px" width = "450px">
</p>

## HOW SOA WORKS

In SOA, all the Services communicate with messages formally defined using XML. XML is the language used to write many of the Web services. UDDI is a registry that lists all services offered. Web Services Description Language (WSDL) is an XML-based prototype that describes the function of the service and how to access it. All of the communication is maintained by Simple Object Access Protocol (SOAP) [4].
<p align = "center">
<img src="https://www.researchgate.net/publication/327054573/figure/fig1/AS:660230866231298@1534422713647/SOAP-protocol-SOAP-is-the-master-leader-in-communications-Its-main-purpose-is-to-send.png" alt= "How SOA works" height = "350px" width = "450px">
</p>


## BENEFITS OF SOA

Since SOA is platform-independent, services communicate with other applications through a common language. One of the most important advantages of SOA is code reusability. If there is an existing software module that is needed, instead of creating a new one from scratch, we can use the old one and this will reduce the maintenance cost and development time for the new function significantly. Loose coupling allows developers to add more functionalities smoothly. Among other benefits, it improves their flexibility by enabling rapid development and modification of the software application. They are more reliable as services are broken down into small, independent services that are easier to test and debug [5]. One of the key ideas of SOA is that it breaks the service down into small, independent services that can run on multiple servers and these services are stateless, which means that services do not withhold information from one state to the other. It allows them to run the services on multiple computers and because of this architecture, the SOA application is scalable.
SOA acts as a very powerful business tool as it can impact the entire business. It enhances business agility as it reacts quickly to changes in the business by adding or upgrading existing functionality. It interacts with customers on different platforms by creating additional services for different devices. Whenever the volume of data increases, separate services can scale up to address the load. Thus it helps businesses respond more quickly and more cost-effectively to changing market conditions, customer preferences, and changing technology [6].

## DRAWBACKS OF SOA

SOA may not always be the best choice for the organization as there are different additional requirements to be the optimal solution. The implementation of SOA requires huge investments through technology and human resources. Using too many services or managing multiple services could be challenging. It is not desirable for stand-alone, non-distributed applications and short-term applications that do not have much scope. SOA applications have to deal with large amounts of data which becomes a scalability bottleneck [7].

***

## REFERENCES

1. <https://collaboration.opengroup.org/projects/soa-book/pages.php?action=show&ggid=1314>

1. <https://publications.opengroup.org/standards/soa>

1. <https://medium.com/@SoftwareDevelopmentCommunity/what-is-service-oriented-architecture-fa894d11a7ec>

1. <https://www.umsl.edu/~sauterv/analysis/F2015/Service%20Oriented%20Architecture.html.htm>

1. <https://techspirited.com/advantages-disadvantages-of-service-oriented-architecture-soa>

1. <https://soatutor.wordpress.com/2014/09/29/soa-what-is-it-to-a-layman/>

1. <https://docs.microsoft.com/en-us/archive/msdn-magazine/2010/june/msdn-magazine-soa-tips-address-scalability-bottlenecks-with-distributed-caching>
