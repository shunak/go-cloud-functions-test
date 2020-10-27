# How to use

deploy to cloud functions
```
gcloud functions deploy go-cloud-functions-test --entry-point HelloWorld --runtime go111 --trigger-http
```
stop cloud functions
```
gcloud functions delete go-cloud-functions-test
```
