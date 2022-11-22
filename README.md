## How to make an ingress service

Ingress exposes HTTP and HTTPS routes from outside the cluster to services within the cluster. Traffic routing is controlled by rules defined on the Ingress resource.

In this emplate, just replace the `<url-to-access-the-UI>` to the link you want to access the application on. Then replace the `<service-name>` with the name of the service and `<service-port>` with the service port on which the application is running.

## Running the service
Just run `kubectl apply -f ingress.yml -n <namespace>`