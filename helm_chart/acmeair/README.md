# Acme Air Sample and Benchmark (wasperf version)

This application shows an implementation of a fictitious airline called "Acme Air".  The application was built with some key business requirements: the ability to scale to billions of web API calls per day, the need to develop and deploy the application targeting multiple cloud platforms (including Public, Dedicated, Private and hybrid) and the need to support multiple channels for user interaction (with mobile enablement first and browser/Web 2.0 second).The application can be deployed both on-prem as well as on Cloud platforms. 

This application has been restructured to be a microservices application in addion to a monolithic application. Monolithc appliction is refactored to make sure the application can scale with multiple Cloud Data Servces. Microservices version is being developed actively to support multiple Service Proxy, Service Discovery and Resliency technologies. This application is also being enhanced with additional services using IBM Cognitive capabilites like Watson Dialog etc.,

This version of acmeair supports:
  - WebSphere Liberty Profile to Mongodb


## Accessing ACME Air 
```
When the ACME Air is installed, use https://<external ip>/acmeair/ to access the application.
```

