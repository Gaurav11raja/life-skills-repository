# Service Oriented Architecture (SOA) Investigation Report

## Introduction

The purpose of this report is to explore the  benefits of adopting a Service Oriented Architecture (SOA) within our project to address performance and scaling issues. SOA is an architectural approach that can help in achieving greater flexibility and scalability in software systems.

## Understanding SOA

Service-oriented architecture (SOA) is a method of software development that uses software components called services to create business applications. Each service provides a business capability, and services can also communicate with each other across platforms and languages. Developers use SOA to reuse services in different systems or combine several independent services to perform complex task

## Characteristics of SOA

--*They are loosely coupled.*
--*They support interoperability.*
--*They are location-transparent*
--*They are self-contained.*

## Benefits of SOA

1. **Scalability:** SOA lets service run on different servers, increasing scalability. In addition, using a standard communication protocol allows organizations to reduce the level of interaction between clients and services. With a lower level of interaction, applications can be scaled without adding extra pressure.

2. **Flexibility:** SOA promotes loose coupling between services, making it easier to modify or replace components without affecting the entire system.

3. **Reusability:** SOA services are held in a repository and linked on demand, making each service a resource available to all, subject to governance constraints.

4. **Interoperability:** The use of a standardized communication protocol lets platforms easily transmit data among clients and services regardless of the languages they're built on.

5. **Isolation:** Isolating services can limit the impact of failures and improve fault tolerance.

6. **Standardization:** SOA uses the RPC model commonly from structured programming. It standardizes how business processes are automated and used in a way that maintains security and governance.

## Key Considerations

1. **Service Design:** Careful planning of service boundaries, interfaces, and data sharing is essential for a successful SOA implementation.

2. **Data Management:** Handling data consistency and integration between services can be a complex task.

3. **Integration Tools:** The choice of tools and technologies for service integration is critical.

4. **Testing:** Rigorous testing is required to ensure the reliability and robustness of the services.

## Challenges

1. **Complexity:** Implementing SOA can introduce complexity, especially in managing service interactions.

2. **Initial Overhead:** Setting up an SOA infrastructure may require an initial investment of time and resources.

3. **Change Management:** Adapting to a service-oriented mindset may require changes in development practices and team structure.

4. **Security:** When SOA is used, application-managed security is not suitable. Hence separate technologies and standards have to be followed for this purpose.

## Conclusion

Service Oriented Architecture (SOA) holds the potential to address our project's performance and scaling issues effectively. However, it's crucial to carefully plan the transition, considering the design, integration, and testing aspects. SOA can offer scalability, flexibility, and reusability, but it also introduces challenges that need to be managed effectively.

Further analysis and discussion within the team are recommended to determine if adopting SOA is the right step for our project.

---

*Resource: * 
--https://www.techtarget.com/searchapparchitecture/definition/service-oriented-architecture-SOA#:~:text=SOA%20lets%20service%20run%20on,scaled%20without%20adding%20extra%20pressure.

--https://aws.amazon.com/what-is/service-oriented-architecture/#:~:text=Service%2Doriented%20architecture%20(SOA),other%20across%20platforms%20and%20languages.

--https://www.javatpoint.com/service-oriented-architecture


