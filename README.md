A sample Ballerina service

## Use case
When the service is invoked with a message, the service will respond with a record including that message received via an HTTP GET.

## Start the service
Start the sample service by executing `bal run` from the root.

Once successfully executed, you need to invoke the service using the following curl command
```
$ curl http://localhost:8090?name=xxx
```
Now service will be invoked and returns record as  
```
{
  name: "xxx",
  message: "Found book!"
}
```
