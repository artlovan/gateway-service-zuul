# gateway-service-zuul

Gateway service that will forward requests to services and act as single entry point for clients.


1. Run discovery-server
2. Run gateway-service
3. Run hello-app
4. Run goodbye-service
5. Request: $ curl http://localhost:8080/hello (observe request forwarding to hello-service)
6. Request: $ curl http://localhost:8080/goodbye (observe request forwarding to goodbye-service)
7. Bring down all you instances
