# awesome-gcp-interview

Repercussion of my disastrous Google Cloud Platform interview for a job I really wanted.

## Topics:

**Core GCP Topics**

- [Cloud Computing](#cloud-computing) <br/>
- [APIs and Services](#apis-and-services) <br/>
- [Billing](#billing)<br/>
- [IAM and Admin](#iam-and-admin)<br/>
- [App Engine](#app-engine)<br/>
- Compute Engine<br/>
- Kubernetes Engine<br/>
- Cloud Functions<br/>
- Cloud Run<br/>
- Cloud Storage<br/>
- Cloud SQL<br/>
- Cloud Spanner<br/>
- VPC Networks and Firewalls<br/>
- Load Balancing<br/>
- Stackdriver<br/>
- Development Tools<br/>
- Cloud Dataflow and Apache Beam<br/>
- BigQuery<br/>
- Pub/Sub<br/>
- Dataproc<br/>
- AI Platform<br/>
- Cloud AutoML and Machine Learning APIs<br/>
- Cloud Shell and Cloud SDK<br/>
- Client Libraries<br/>

---

### <u>Cloud Computing</u>


#### What is Cloud Computing?
The practice of using a network of remote servers hosted on the Internet to store, manage, and process data, rather than a local server or a personal computer.

#### What is virtualisation?

#### What are some advantages of cloud computing?

TODO
#### What are the cloud computing models available today?
- IaaS - Infrastructure as a Service <br/>
- PaaS - Platform as a Service <br/>
- SaaS - Software as a Service <br/>

#### What is Infrastructure as a Service?
Infrastructure as a service is a form of cloud computing where bare computing resources such as compute, memory, network and storage are provisioned over the internet.

#### What is Platform as a Service?
TODO

#### What is Software as a Service?
TODO

#### What are public cloud providers?

#### What are private cloud providers?

#### Name some public cloud providers.

#### Name some private cloud providers.

#### Name some IaaS providers.

#### Name some PaaS providers.

#### Name some SaaS providers.

#### What is serverless computing?

#### Name some serverless platforms.

#### What is Container as a Service?

#### What is Function as a Service?

#### What is Backend as a Service?

---

### <u>APIs and Services</u>

#### How do you enable an API in Google Cloud Platform?

#### How can you access private GCP data via API?

#### How can you restrict access scopes for your API key?

#### What do client key and client credentials signify?

---
### <u>Billing</u>

#### What is a billing account associated with?

#### How can you setup billing alerts?

#### What are the billing export sinks?

#### How can you analyse your billing data?

#### True or False: A project can have more than one billing accounts.

#### How can I transfer a project from one billing account to another?

#### Billing account roles are assigned at what level of the resource hierarchy?

#### What billing account role would you assign to the CTO of your company?

#### What billing account role would you assign to the CFO of your company?

#### True or False. Billing data cannot be analysed in Google BigQuery.

#### How can you set up notifications for your billing account?

#### True or False. Google will stop serving API requests after budget is exceeded

#### True or False. No matter the size of organization, even large enterprises have to sign up using a credit card.

#### On what parameters can billing alerts be set?

#### How can you estimate billing costs for your newly setup BigTable cluster?

#### You've a BigQuery table in a new project that you query infrequently. The total size of the table is 8.5 GB. What will be the associated costs at the end of the month?

#### True or False. You can continue to use your $300 credits from trial after 12 months.

#### True or False. You need a credit card to evaluate Google BigQuery.

#### How can you incorporate GCP billing data with your company's custom pre-existing finances app?

#### After setting up billing exports, the bill is higher than originally estimated. What did you miss to consider?

---


### <u>IAM and Admin</u>

#### What does IAM stand for?

#### What are roles?

#### What are the types of roles available on Google Cloud Platform?

#### What are primitive roles?

#### What are predefined roles?

#### What are custom roles?

#### What are members in Google Cloud Platform?

#### What does a permission look like in GCP?

#### What are the various ways to assign roles to the user in GCP?

#### What is resource hierarchy?

#### What is an Organisation?

#### What is a Folder?

#### What is a Project?

#### What is a Resource?

#### How can you manage permissions across multiple teams working in your Fortune 500 company?

#### True or False. Project ID and Project Name should be same in order to create a valid project.

#### How can you change the Project ID of your sandbox project?

#### True or False. Two projects in the same organisation can have same name.

#### How can you uniquely choose a project number to optimise performance of your Compute Engine VM?

#### You want to get started with exploring GCP. You've signed up for the free trial and are ready to go. Your friend who's experienced with GCP tells you that all their billing accounts are affiliated to the organisation that their founder owns. This has got you worried as you can't find any organisation anywhere in your GCP console. What should you do?

#### What is it called? Granting only necessary permissions to a user and revoking access when their role in the organisation changes?

#### How can you assign the permission storage.buckets.list to a user?

#### A new developer has joined your team. You want to grant them access to the development project. How do you grant them access and what roles would you assign?

#### Your organisation has been growing rapidly and today 8 new people joined your staging team. How do you grant them access to the staging project?

#### Your company's organisation is owned by the CTO. Following Security practices, you suggest to revoke his access to the production project. How will you do it?

#### What is a service account?

#### How is a service account different from a regular account?

#### Is service account a member or a resource?

#### How will you authenticate an application using service account?

#### True or False. You need to use GOOGLE_APP_AUTH environment variable to authenticate applications using service account.

#### Your teammate is trying to authenticate to an application using the newly created service account. However they're unable to do so. What could be wrong?

#### What are some of the best practices for service accounts?

#### What is the recommended way to store service account keys?

#### What are organisation policies?

#### What are resource constraints?

#### What role do you need to see data access logs?

#### What is the difference between quotas and labels in GCP?

#### A user is running a Cloud Dataflow job. However they start receiving errors suggesting that the service cannot scale to 1000 CPUs. What could be happening?

#### You're creating a managed instance group with a minimum CPUs of 150. However, when you finish creating the MIG, you receive an error suggesting that there are only about 32 CPUs available. What should you do to start the group with desired number of instances?

---

### <u>App Engine</u>

#### What is App Engine?

#### What type of computing model is App Engine?

#### What runtimes are supported by App Engine?

#### How many environments is App Engine available in?

#### What is the difference between standard and flexible environment?

#### How many and what runtimes does App Engine Standard support?

#### How many and what runtimes does App Engine Flexible support?

#### What year was App Engine launched in?

#### What use cases are best suited for App Engine?

#### What is traffic-splitting?

#### How can you implement blue-green deployment strategy in App Engine?

#### How can you implement canary testing in App Engine?

#### Your current app is hosted on App Engine. The marketing team has been working on a new UI about which they are sure, will increase user engagement to an extent. You want to test the application before deploying the app. How can you support this request?

#### The new layout that marketing team introduced is facing issues interacting with the backend. Your customers can feel this disorientation while they engage as they are not able to access their data. What should you do to resolve this issue?

#### What C++ library do you need to import in App Engine to enable traffic splitting?

#### True or False. App Engine traffic-splitting can only be implemented in App Engine Flexible environment.

#### True or False. App Engine was the first GCP offering.

#### What is versioning in App Engine?

#### True or False. You can only serve one app per project using App Engine.

#### Which App Engine service is necessary to utilize App Engine?

#### How many ways can App Engine scale in?

#### True or False. You can SSH into an App Engine instance.

#### True or False. It would be misleading to say that when App Engine scales down to 0 instances, you pay nothing.

#### What is the difference between automatic, basic and manual scaling?

#### Which file would you describe your configuration in for deploying your app to App Engine Python runtime?

#### Which file would you describe your configuration in for deploying your app to App Engine Java runtime?

#### How will you install external Python libraries in First Generation App Engine Standard Environment?

#### Which directory is available as temporary storage in App Engine?

#### How many machine types are available in App Engine?

#### True or False. You cannot create stateful applications in App Engine.

#### How can you run your Docker container on App Engine?

#### Which App Engine environment can run Docker containers?

#### You have an API backend deployed in App Engine. However you see that every time the API stays idle for a few seconds, the next request that comes in has a higher response time than the ones that follow it. What could be happening and how could you standardise response times across requests?

#### You have an App Engine application set up in manual scaling mode. You notice that some of the nodes have high CPU usage while one of them has relatively low consumption. Logs show that that instances is trying to start but is unable to do so successfully. How would you debug?

#### How can you schedule cron jobs in App Engine?

#### Cron jobs are described in what file?

#### cron.yaml should be placed in which folder to provision it for deployment?

#### Do Cron jobs in App Engine follow the same Unix compatible cron syntax?

#### What are task queues in App Engine?

#### True or False. App Engine apps are accessible globally and therefore they are deployed in multi-regional projects.

#### How can you migrate App Engine app from one region to another?

#### How can you migrate App Engine app from one project to another?

#### How can App Engine apps communicate with other GCP services?

#### How can you disable an app in App Engine?

#### True or False. To view logs of older versions of an App Engine app, you have to setup an Elastic Search cluster.

#### How can you improve performance of your web page hosted on App Engine?

#### What is the difference between shared and dedicated memcache?

#### What are firewall rules in terms of App Engine?

***
***
## Extending Google Cloud:

**Clouds are big. These are extended topics that will crawl their way in a GCP interview.**

Kubernetes<br/>
Containers and Docker<br/>
Linux<br/>
DevOps<br/>
Networking<br/>
Security and Authorization<br/>
Machine Learning <br/>
