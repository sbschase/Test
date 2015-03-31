The Cloud Data Object (CDO) provides client side support for critical data management such as complex record relationships, transaction scope, adata synchronization and error reconciliation with the server. Enterprise App Development tools like OpenEdge (and .NET) provide very robust desktop client data management but that has not been extended to the cloud.

Most cloud applications use simple data management and update the server one record at a time. This is often not robust enough for true enterprive applications which require complex custom logic to manage data complexity and synchronization with the server. The purpose of the CDO is to provide a single data management strategy when working in an n-tier application architecture.

The CDO supports data management between any client and any web server. The CDO supports a complex data model and an API to manipulate that data while maintaining data integrity. Data synchronization with the server is fully supported. A CDO catalog defines the logical schema and data mapping to a remote data source. The catalog also defines an API and mapping to invoke remote business logic and CRUD operations normally made available through a REST server. The CDO should fit easily into any MVC-like pattern.

Client applications often run in a stateless environment. A CDO Session establishes and maintains context with a server so that the user only needs to provide their credentials once while every request is stateless and often made asyncronously. The CDO Session also hides all the complexity of the communication with a server. 

# Definitions

*Cloud Data Catalog – Cloud Service schema and interface definition. This is a replacement name for the JSDO catalog.
Cloud Data Service --  Set of services on a server that provides data and operations to the Cloud Data Object.

*Cloud Data Object (CDO)	Set of objects used to manage complex data. , in a standard fashion, data and business logic on a server; also, an instance of the client-side object that provides the actual methods and properties used to access the data and business logic on a server instance. The JSDO is an implementation of this in JavaScript.

*Cloud Data Object (CDO) catalog	A mapping file that maps the schema and access methods of a given CDO to the schema and access methods defined for the data and business logic of a server instance according to the CDO operations that the corresponding CDO service supports. The JSDO catalog is an instance of this.

*Cloud Data Object (CDO) resource	The set of server data and business logic that a given CDO accesses on a server instance. This is normally one or more related tables and methods that support data synchronization between the CDO and the remote data.

*Cloud Data Object (CDO) operation	The set of operations supported by a given CDO on the resource that it accesses

*Cloud Data Object (CDO) service	A service managed by a Web application that is running on a Web server and that provides client access to a given CDO resource; a given service instance can support multiple CDO resources and their corresponding CDOs. Referred to as an OE Web Service in OpenEdge.

*Client Data Object (CDO) server interface	The server interface that supports access to server data and business logic using the operations of a given CDO resource; this can be the interface to a formal Business Entity or to any encapsulated set of server routines that implement the corresponding CDO operations


# Prerequisites

- 

# Installation

1. 

# See Also

