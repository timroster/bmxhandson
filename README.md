# Some hands-on labs for Bluemix, Cloudant, and Message Hub

This is a series of labs that introduce a Java developer to IBM Bluemix and some common services used in cloud native applications.

## Prerequisites
You will need the following prerequisites for these labs:

* Bluemix supported [web browser](https://console.ng.bluemix.net/docs/overview/prereqs.html#prereqs)
* A Bluemix account
* [Cloud Foundry CLI](https://github.com/cloudfoundry/cli#downloads)
* [git](https://git-scm.com/)
* [maven](https://maven.apache.org/)
* [Gradle](https://gradle.org/)
* Java 7+ (8 recommended)
* [Eclipse neon or oxygen](http://www.eclipse.org/)

### Deploying your first Java App
Learn how to navigate core aspects of the Bluemix Web UI and deploy a Java application using a boilerplate (combination of runtime, a service, and some code).

[Your First Java App](FirstJavaApp/README.md)

### More deployment options
In this lab you will use the Cloud Foundry and eclipse to deploy an application to Bluemix. You'll also see how to bind a service to an application and then use that service in a local or remote copy of the running application.

[Get Started Java](https://github.com/kostickm/get-started-java)

### Managing Cloudant NoSQL databases
This lab will show you how to manage a Cloudant database using the dashboard. Since you can use one of the Cloudant databases deployed in an earlier lab, it's ok to skip Step 1 of the lab instructions.

[Manage Cloudant](ManageCloudant/README.md)

### Exploring Message Hub
This lab will introduce two sample applications that use the kafka java api to communicate with Bluemix Message Hub.

[Message Hub with Java](https://github.com/timroster/message-hub-samples/blob/master/LAB_README.md)

### The Microprofile platform for Java Enterprise microservices
In this series of labs, you will build a simple Java microprofile application that provides a REST backend for an AngularJS single page application.

*coming soon* based on lab series here:
https://developer.ibm.com/wasdev/docs/writing-simple-microprofile-application/
[GitHub](https://github.com/WASdev/sample.microprofile.meetingapp)
