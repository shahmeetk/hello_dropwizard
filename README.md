# hello_dropwizard
# Introduction

The Dropwizard Hello World application

# Running The Application

To test the example application run the following commands.

* To create config kind.

        kubectl apply -f application-config.yaml

* To run the deployment service.

        kubectl apply -f application-deployment.yaml
		
* To check deployment status.

        kubectl get svc application

* To test application.

        curl localhost:8080/hello
		
* To hit the Hello World example (hit refresh a few times).

	http://localhost:8080/hello-world

	http://localhost:8080/hello-world?name=World
