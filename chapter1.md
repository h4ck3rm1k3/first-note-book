# REST API caching services

Proprietary apis can lead to vendor lock in. 
Usage of these apis coded into your application contains a use case that can be
re- applied to other services. The first step to manage this would be to create
a man in the middle proxy service. The service would also allow for
authentication tokens to pass through. Results caching speeds up access.


## Document
The next step would be to document the API. Creating of structures to decode
and process the api. Test and Inspect client libraries against server. Show
connection between test cases and api calls. Index API documents to cross
reference terms to strings in the source code.


## Model the domain
Concieve of database tables or nosql collections that implement key concepts of
the API. Create parsers for the API domain specific terms/languages.


## Backend
Generate/Implement high speed code to implement that API. 

## Transport
Find other backends that provide similar services. Create client methods to
transform the backend interface to call into the other API.

##Similar ideas

* Man in the middle proxy https://mitmproxy.org/
* service virtualization terminator https://github.com/BaiduQA/terminator (chinese) see translation https://github.com/h4ck3rm1k3/terminator
* Service Virtualization https://en.wikipedia.org/wiki/Service_virtualization
* Membrane Service Proxy https://github.com/membrane/service-proxy
* Mock Server http://www.mock-server.com/
* Wire Mock http://wiremock.org/

## See Also
* http://www.programmableweb.com/news/top-tools-to-help-you-mock-web-services/how-to/2014/01/13
