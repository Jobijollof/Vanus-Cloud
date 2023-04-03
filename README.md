# Vanus-Cloud 

### Introduction

Vanus helps users build event pipelines between SaaS, cloud services, and cloud functions in minutes.

### Build the event-driven system

- Get events from cloud services and SaaS, and deliver them to cloud functions or microservices.

- Synchronize changed data or transfer data to the data lake.

- Obtain events generated by SaaS and send them to other SaaS.

### Out-of-the-box event computing capabilities

- Real-time processing during event transmissions, such as filtering and transformation.

- Natively support the CloudEvents specification, and can directly send events to workloads that support CloudEvent. [VANUS](https://github.com/vanus-labs/vanus)

Vanus is a tool that helps different parts of a computer system talk to each other. It's like a mailbox where one part of the system can leave a message for another part to read later.

But Vanus is special because it can do more than just deliver messages. It can also do something called "event processing." This means that it can automatically do something when it receives a message, like sending an email or updating a database.

Vanus is also really good at handling lots of messages at the same time, so it can be used for systems that have to process a lot of data quickly.

It is an open-source project, which means that it is free to use, modify, and distribute under an open-source license.

Super easy to use
One-click deployment, the installation is completed within 1 minute, and developers without MQ experience can also use it.

### Vanus Demo

***GitHub star event that triggers a Slack message***

log in to [cloud vanus.ai](https://www.vanus.ai/)

[vanus.txt](https://github.com/Jobijollof/Vanus-Cloud/files/11136546/vanus.txt)

- Sign in

![sign-in](https://user-images.githubusercontent.com/113374279/229461551-858a8488-c56e-454b-ad4f-ce34ec395862.png)

- Fill in your bio data. In the space of Company name you can specify individual if you do not work or own a company.


![bio-data](https://user-images.githubusercontent.com/113374279/229462123-df645679-1b01-452c-843d-8fbf965f61e6.png)


![bio-data2](https://user-images.githubusercontent.com/113374279/229463131-616faaf5-315b-4b0e-a329-980a2f9992a2.png)

### Vanus Templates

These are pre-configurred event triggers.
 
 ![choose template](https://user-images.githubusercontent.com/113374279/229463718-359e3d06-7e3e-44c9-9d91-cad7a455ba01.png)
 
 We are going to choose the template with `GitHub star event that triggers a Slack message`. 
 
 ![try-now](https://user-images.githubusercontent.com/113374279/229466681-1d628843-5c04-457a-a4a2-51e4496a30b7.png)
 
 ### Authourise Source connector
 
 Github

![authorise](https://user-images.githubusercontent.com/113374279/229470662-4932f154-2027-4f0c-b86e-0a3d3e6fca70.png)

  You would have to authorize access to your github account.
 

![authorise-github](https://user-images.githubusercontent.com/113374279/229470273-f93a5748-a3ea-491b-a83f-4e1a01f9e57b.png)
 

After authourisation you willbe re-directed to Vanus Cloud
 
 - Pick the repo you want the trigger for
 - Click on next
 
 ### Authorise the Sink Connector
 
 Get webhook url for slack Channel to send trigger
 
 Useful article to get [slack-webhook-url](https://support.accelq.com/hc/en-us/articles/4403072462605-Create-a-Webhook-URL-for-a-Slack-channel)
 
 - Insert  webhook url
 
 ![webhook-url](https://user-images.githubusercontent.com/113374279/229489103-4ce87bfd-a747-4180-b403-000cf48acc41.png)
 
 ![running](https://user-images.githubusercontent.com/113374279/229489336-843433de-b71d-4e82-be86-a65c3c3c5ae2.png)
 
 - Go ahead and star the repo
 
 ![star](https://user-images.githubusercontent.com/113374279/229489745-96ed8d63-4c11-477c-bdd0-f4617df9155e.png)



 
 
 

 

