# Knative serving sample applications

This directory contains sample applications, developed on Knative, to illustrate
different use-cases and resources. See [Knative serving](https://github.com/knative/docs/tree/master/serving)
to learn more about Knative Serving resources.

| Name | Description | Languages |
| ---- | ----------- |:---------:|
| Hello World | A quick introduction that highlights how to deploy an app using Knative Serving. | [C#](helloworld-csharp/README.md), [Go](helloworld-go/README.md), [Java](helloworld-java/README.md), [Node.js](helloworld-nodejs/README.md), [PHP](helloworld-php/README.md), [Python](helloworld-python/README.md), [Ruby](helloworld-ruby/README.md), [Rust](helloworld-rust/README.md) |
| Advanced Deployment | Simple blue/green-like application deployment pattern illustrating the process of updating a live application without dropping any traffic. | [YAML](blue-green-deployment.md) |
| Autoscale | A demonstration of the autoscaling capabilities of Knative. | [Go](autoscale-go/README.md) |
| Private Repo Build | An example of deploying a Knative Serving Service using a Github deploy-key and a DockerHub image pull secret. | [Go](build-private-repo-go/README.md) |
| Buildpack for Applications | A sample app that demonstrates using Cloud Foundry buildpacks on Knative Serving. | [.NET](buildpack-app-dotnet/README.md) |
| Buildpack for Functions | A sample function that demonstrates using Cloud Foundry buildpacks on Knative Serving. | [Node.js](buildpack-function-nodej/README.md) |
| Github Webhook | A simple webhook handler that demonstrates interacting with Github. | [Go](gitwebhook-go/README.md) |
| gRPC | A simple gRPC server. | [Go](grpc-ping-go/README.md) |
| Knative Routing | An example of mapping multiple Knative services to different paths under a single domain name using the Istio VirtualService concept. | [Go](knative-routing-go/README.md) |
| REST API | A simple Restful service that exposes an endpoint defined by an environment variable described in the Knative Configuration. | [Go](rest-api-go/README.md) |
| Source to URL | A sample that shows how to use Knative to go from source code in a git repository to a running application with a URL. | [Go](source-to-url-go/README.md) |
| Telemetry | This sample runs a simple web server that makes calls to other in-cluster services and responds to requests with "Hello World!". The purpose of this sample is to show generating metrics, logs, and distributed traces. | [Go](telemetry-go/README.md) |
| Thumbnailer | An example of deploying a "dockerized" application to Knative Serving which takes video URL as an input and generates its thumbnail image. | [Go](thumbnailer-go/README.md) |
| Traffic Splitting | This samples builds off the [Creating a RESTful Service](../rest-api-go) sample to illustrate applying a revision, then using that revision for manual traffic splitting. | [YAML](traffic-splitting/README.md) |
