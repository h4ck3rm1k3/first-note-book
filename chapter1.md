# REST API caching services

Proprietary apis can lead to vendor lock in. 
Usage of these apis coded into your application contains a use case that can be re- applied to other services. The first step to manage this would be to create a man in the middle proxy service. The service would also allow for authentication tokens to pass through. Results caching speeds up access.

## Document
The next step would be to document the API. Creating of structures to decode and process the api. Test and Inspect client libraries against server. Show connection between test cases and api calls. Index API documents to cross reference terms to strings in the source code. 

## Model the domain
Concieve of database tables or nosql collections that implement key concepts of the API. Create parsers for the API domain specific terms/languages. 

## Backend
Generate/Implement high speed code to implement that API. 

## Transport
Find other backends that provide similar services. Create client methods to transform the backend interface to call into the other API.