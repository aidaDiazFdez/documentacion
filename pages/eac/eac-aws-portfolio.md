---
title: Terraform - AWS Portfolio
sidebar: eac
permalink: eac-aws-portfolio.html
folder: eac
toc: false
---
  
## Purpose  
  
Find here the collection of all the AWS products.  
**Reference document:** [List of Acronyms](https://confluence.alm.europe.cloudcenter.corp/display/OPTIMUM/List+of+Acronyms)  
  
## Product Version  
  
The product policy version decided by the CCoE Products team is:      

  * **x.x.x-beta. ReleaseNumber** (for those pending pass QA in Pro)
    * **x.x.x**: Number of  version to implement
    * **-Beta.1**: Beta **indicate a product in Technical Readiness status**, the number indicate the release number where was generated the beta artifact  
  
* **x.x.x** (for those that passed QA in Pro)
  
## Status description  
  
* In Development: products being currently developed
* Technical Readiness: Product automation finished but:
  * Still pending to be reviewed in Pre environment or already reviewed but pending to solve security issues
* Published: automation finished, production environment compliance. Compliance with a specific version of Security Control Framework (SCF)
* Backlog: products in backlog pending to be automated  

<br>

**Product Support**  
Any bug found on a product version, will be solved in the latest major version and is necessary to update always the product version to the latest major version product available.  
  
## Product Summary  
  
<div class="panel-group" id="accordion">
                    <div class="panel panel-default">
                        <div class="panel-heading">
                            <h4 class="panel-title">
                                <a class="noCrossRef accordion-toggle" data-toggle="collapse" data-parent="#accordion" href="#collapseOne">Network Load Balancer (NLB)</a>
                            </h4>
                        </div>
                        <div id="collapseOne" class="panel-collapse collapse noCrossRef">
                            <div class="panel-body">
                            <p>Elastic Load Balancing (ELB) automatically distributes incoming application traffic across multiple targets, such as Amazon EC2 instances, containers, and IP addresses.</p>
                            <p>Network Load Balancer (NLB) is best suited for load balancing of TCP traffic where extreme performance is required. Operating at the connection level (Layer 4), Network Load Balancer routes traffic to targets within Amazon Virtual Private Cloud (Amazon VPC) and is capable of handling millions of requests per second while maintaining ultra-low latencies. Network Load Balancer is also optimized to handle sudden and volatile traffic patterns.</p><br>
                            <a href="https://docs.aws.amazon.com/whitepapers/latest/aws-overview/networking-services.html#elastic-load-balancing">AWS Documentation</a><br>
                            <hr>
                            <table>
                              <thead>
                              <tr>
                                  <th>terraform-aws-module-nlb-sa</th>
                                  <th></th>
                              </tr>
                              </thead>
                              <tbody>
                              <tr>
                                  <td>Git Repo</td>
                                  <td><a href="https://github.alm.europe.cloudcenter.corp/ccc-ccoe-aws/terraform-aws-module-nlb-sa/tree/v1.1.0">Source Code</a></td>
                              </tr>
                              <tr>
                                  <td>README</td>
                                  <td><a href="https://github.alm.europe.cloudcenter.corp/ccc-ccoe-aws/terraform-aws-module-nlb-sa/tree/v1.1.0/README.md">README</a> </td>
                              </tr>
                              <tr>
                                  <td><b>Latest Release Version</b></td>
                                  <td><b>v1.1.0</b></td>
                              </tr>
                              <tr>
                                  <td>Status</td>
                                  <td>Published</td>
                              </tr>
                              <tr>
                                  <td>Support</td>
                                  <td>Yes</td>
                              </tr>
                              </tbody>
                            </table>
                            </div>
                        </div>
                    </div>
                    <!-- /.panel -->
                    <div class="panel panel-default">
                        <div class="panel-heading">
                            <h4 class="panel-title">
                                <a class="noCrossRef accordion-toggle" data-toggle="collapse" data-parent="#accordion" href="#collapseTwo">Elastic Compute Cloud (EC2)</a>
                            </h4>
                        </div>
                        <div id="collapseTwo" class="panel-collapse collapse noCrossRef">
                            <div class="panel-body">
                            <p>Amazon Elastic Compute Cloud (Amazon EC2) is a web service that provides secure, resizable compute capacity in the cloud. It is designed to make web-scale computing easier for developers.</p>
                            <p>The Amazon EC2 simple web service interface allows you to obtain and configure capacity with minimal friction. It provides you with complete control of your computing resources and lets you run on Amazon’s proven computing environment. Amazon EC2 reduces the time required to obtain and boot new server instances (called Amazon EC2 instances) to minutes, allowing you to quickly scale capacity, both up and down, as your computing requirements change. Amazon EC2 changes the economics of computing by allowing you to pay only for capacity that you actually use. Amazon EC2 provides developers and system administrators the tools to build failure resilient applications and isolate themselves from common failure scenarios.</p><br>
                            <a href="https://docs.aws.amazon.com/whitepapers/latest/aws-overview/compute-services.html#amazon-ec2">AWS Documentation</a><br>
                            <hr>
                            <table>
                              <thead>
                              <tr>
                                  <th>terraform-aws-module-ec2-sa</th>
                                  <th></th>
                              </tr>
                              </thead>
                              <tbody>
                              <tr>
                                  <td>Git Repo</td>
                                  <td><a href="https://github.alm.europe.cloudcenter.corp/ccc-ccoe-aws/terraform-aws-module-ec2-sa/tree/v1.5.0">Source Code</a></td>
                              </tr>
                              <tr>
                                  <td>README</td>
                                  <td><a href="https://github.alm.europe.cloudcenter.corp/ccc-ccoe-aws/terraform-aws-module-ec2-sa/blob/v1.5.0/README.md">README</a> </td>
                              </tr>
                              <tr>
                                  <td><b>Latest Release Version</b></td>
                                  <td><b>v1.5.0</b></td>
                              </tr>
                              <tr>
                                  <td>Status</td>
                                  <td>Published</td>
                              </tr>
                              <tr>
                                  <td>Support</td>
                                  <td>Yes</td>
                              </tr>
                              </tbody>
                            </table>
                            </div>
                        </div>
                    </div>
                    <!-- /.panel -->
                    <div class="panel panel-default">
                        <div class="panel-heading">
                            <h4 class="panel-title">
                                <a class="noCrossRef accordion-toggle" data-toggle="collapse" data-parent="#accordion" href="#collapseThree">Application Load Balancer (ALB)</a>
                            </h4>
                        </div>
                        <div id="collapseThree" class="panel-collapse collapse noCrossRef">
                            <div class="panel-body">
                            <p>Elastic Load Balancing (ELB) automatically distributes incoming application traffic across multiple targets, such as Amazon EC2 instances, containers, and IP addresses.</p>
                            <p>Application Load Balancer (ALB) is best suited for load balancing of HTTP and HTTPS traffic and provides advanced request routing targeted at the delivery of modern application architectures, including microservices and containers. Operating at the individual request level (Layer 7), Application Load Balancer routes traffic to targets within Amazon Virtual Private Cloud (Amazon VPC) based on the content of the request.</p><br>
                            <a href="https://docs.aws.amazon.com/whitepapers/latest/aws-overview/networking-services.html#elastic-load-balancing">AWS Documentation</a><br>
                            <hr>
                            <table>
                              <thead>
                              <tr>
                                  <th>terraform-aws-module-alb-sa</th>
                                  <th></th>
                              </tr>
                              </thead>
                              <tbody>
                              <tr>
                                  <td>Git Repo</td>
                                  <td><a href="https://github.alm.europe.cloudcenter.corp/ccc-ccoe-aws/terraform-aws-module-alb-sa/tree/v1.3.0">Source Code</a></td>
                              </tr>
                              <tr>
                                  <td>README</td>
                                  <td><a href="https://github.alm.europe.cloudcenter.corp/ccc-ccoe-aws/terraform-aws-module-alb-sa/tree/v1.3.0/README.md">README</a> </td>
                              </tr>
                              <tr>
                                  <td><b>Latest Release Version</b></td>
                                  <td><b>v1.3.0</b></td>
                              </tr>
                              <tr>
                                  <td>Status</td>
                                  <td>Published</td>
                              </tr>
                              <tr>
                                  <td>Support</td>
                                  <td>Yes</td>
                              </tr>
                              </tbody>
                            </table>
                            </div>
                        </div>
                    </div>
                    <!-- /.panel -->
                    <div class="panel panel-default">
                        <div class="panel-heading">
                            <h4 class="panel-title">
                                <a class="noCrossRef accordion-toggle" data-toggle="collapse" data-parent="#accordion" href="#collapseFour">Simple Storage Service (S3)</a>
                            </h4>
                        </div>
                        <div id="collapseFour" class="panel-collapse collapse noCrossRef">
                            <div class="panel-body">
                            <p>Amazon Simple Storage Service (Amazon S3) is an object storage service that offers industry-leading scalability, data vailability, security, and performance. This means customers of all sizes and industries can use it to store and protect any amount of data for a range of use cases, such as websites, mobile applications, backup and restore, archive, enterprise applications, IoT devices, and big data analytics. Amazon S3 provides easy-to-use management features so you can organize your data and configure finely-tuned access controls to meet your specific business, organizational, and compliance requirements. Amazon S3 is designed for 99.999999999% (11 9’s) of durability, and stores data for millions of applications for companies all around the world.</p><br>
                            <a href="https://docs.aws.amazon.com/whitepapers/latest/aws-overview/storage-services.html#amazon-s3">AWS Documentation</a><br>
                            <hr>
                            <table>
                              <thead>
                              <tr>
                                  <th>terraform-aws-module-as3-sa</th>
                                  <th></th>
                              </tr>
                              </thead>
                              <tbody>
                              <tr>
                                  <td>Git Repo</td>
                                  <td><a href="https://github.alm.europe.cloudcenter.corp/ccc-ccoe-aws/terraform-aws-module-as3-sa/tree/v1.2.1">Source Code</a></td>
                              </tr>
                              <tr>
                                  <td>README</td>
                                  <td><a href="https://github.alm.europe.cloudcenter.corp/ccc-ccoe-aws/terraform-aws-module-as3-sa/tree/v1.2.1/README.md">README</a> </td>
                              </tr>
                              <tr>
                                  <td><b>Latest Release Version</b></td>
                                  <td><b>v1.2.1</b></td>
                              </tr>
                              <tr>
                                  <td>Status</td>
                                  <td>Published</td>
                              </tr>
                              <tr>
                                  <td>Support</td>
                                  <td>Yes</td>
                              </tr>
                              </tbody>
                            </table>
                            </div>
                        </div>
                    </div>
                    <!-- /.panel -->
                    <div class="panel panel-default">
                        <div class="panel-heading">
                            <h4 class="panel-title">
                                <a class="noCrossRef accordion-toggle" data-toggle="collapse" data-parent="#accordion" href="#collapseFive">Key Management Service (KMS)</a>
                            </h4>
                        </div>
                        <div id="collapseFive" class="panel-collapse collapse noCrossRef">
                            <div class="panel-body">
                            <p>AWS Key Management Service (KMS) makes it easy for you to create and manage keys and control the use of encryption across a wide range of AWS services and in your applications. AWS KMS is a secure and resilient service that uses FIPS 140-2 validated hardware security modules to protect your keys. AWS KMS is integrated with AWS CloudTrail to provide you with logs of all key usage to help meet your regulatory and compliance needs.</p><br>
                            <a href="https://aws.amazon.com/kms/">AWS Documentation</a><br>
                            <hr>
                            <table>
                              <thead>
                              <tr>
                                  <th>terraform-aws-module-kms-sa</th>
                                  <th></th>
                              </tr>
                              </thead>
                              <tbody>
                              <tr>
                                  <td>Git Repo</td>
                                  <td><a href="https://github.alm.europe.cloudcenter.corp/ccc-ccoe-aws/terraform-aws-module-kms-sa/tree/v1.4.0">Source Code</a></td>
                              </tr>
                              <tr>
                                  <td>README</td>
                                  <td><a href="https://github.alm.europe.cloudcenter.corp/ccc-ccoe-aws/terraform-aws-module-kms-sa/blob/v1.4.0/README.md">README</a> </td>
                              </tr>
                              <tr>
                                  <td><b>Latest Release Version</b></td>
                                  <td><b>v1.4.0</b></td>
                              </tr>
                              <tr>
                                  <td>Status</td>
                                  <td>Published</td>
                              </tr>
                              <tr>
                                  <td>Support</td>
                                  <td>Yes</td>
                              </tr>
                              </tbody>
                            </table>
                            </div>
                        </div>
                    </div>
                    <!-- /.panel -->
                    <div class="panel panel-default">
                        <div class="panel-heading">
                            <h4 class="panel-title">
                                <a class="noCrossRef accordion-toggle" data-toggle="collapse" data-parent="#accordion" href="#collapseSix">DynamoDB</a>
                            </h4>
                        </div>
                        <div id="collapseSix" class="panel-collapse collapse noCrossRef">
                            <div class="panel-body">
                            <p>Amazon DynamoDB is a key-value and document database that delivers single-digit millisecond performance at any scale. It’s a fully managed, multiregion, multimaster database with built-in security, backup and restore, and in-memory caching for internet-scale applications. DynamoDB can handle more than 10 trillion requests per day and support peaks of more than 20 million requests per second.</p><br>
                            <a href="https://docs.aws.amazon.com/whitepapers/latest/aws-overview/database.html#amazon-dynamodb">AWS Documentation</a><br>
                            <hr>
                            <table>
                              <thead>
                              <tr>
                                  <th>terraform-aws-module-dyn-sa</th>
                                  <th></th>
                              </tr>
                              </thead>
                              <tbody>
                              <tr>
                                  <td>Git Repo</td>
                                  <td><a href="https://github.alm.europe.cloudcenter.corp/ccc-ccoe-aws/terraform-aws-module-dyn-sa/tree/v1.2.0">Source Code</a></td>
                              </tr>
                              <tr>
                                  <td>README</td>
                                  <td><a href="https://github.alm.europe.cloudcenter.corp/ccc-ccoe-aws/terraform-aws-module-dyn-sa/blob/v1.2.0/README.md">README</a> </td>
                              </tr>
                              <tr>
                                  <td><b>Latest Release Version</b></td>
                                  <td><b>v1.2.0</b></td>
                              </tr>
                              <tr>
                                  <td>Status</td>
                                  <td>Published</td>
                              </tr>
                              <tr>
                                  <td>Support</td>
                                  <td>Yes</td>
                              </tr>
                              </tbody>
                            </table>
                            </div>
                        </div>
                    </div>
                    <!-- /.panel -->
                    <div class="panel panel-default">
                        <div class="panel-heading">
                            <h4 class="panel-title">
                                <a class="noCrossRef accordion-toggle" data-toggle="collapse" data-parent="#accordion" href="#collapseSeven">Elasticsearch Service (ES)</a>
                            </h4>
                        </div>
                        <div id="collapseSeven" class="panel-collapse collapse noCrossRef">
                            <div class="panel-body">
                            <p>Amazon Elasticsearch Service (Amazon ES) is a managed service that makes it easy to deploy, operate, and scale Elasticsearch clusters in the AWS Cloud. Elasticsearch is a popular open-source search and analytics engine for use cases such as log analytics, real-time application monitoring, and clickstream analysis. With Amazon ES, you get direct access to the Elasticsearch APIs; existing code and applications work seamlessly with the service.</p><br>
                            <a href="https://docs.aws.amazon.com/elasticsearch-service/latest/developerguide/what-is-amazon-elasticsearch-service.html">AWS Documentation</a><br>
                            <hr>
                            <table>
                              <thead>
                              <tr>
                                  <th>terraform-aws-module-els-sa</th>
                                  <th></th>
                              </tr>
                              </thead>
                              <tbody>
                              <tr>
                                  <td>Git Repo</td>
                                  <td><a href="https://github.alm.europe.cloudcenter.corp/ccc-ccoe-aws/terraform-aws-module-els-sa/tree/v1.1.0">Source Code</a></td>
                              </tr>
                              <tr>
                                  <td>README</td>
                                  <td><a href="https://github.alm.europe.cloudcenter.corp/ccc-ccoe-aws/terraform-aws-module-els-sa/tree/v1.1.0/README.md">README</a> </td>
                              </tr>
                              <tr>
                                  <td><b>Latest Release Version</b></td>
                                  <td><b>v1.1.0</b></td>
                              </tr>
                              <tr>
                                  <td>Status</td>
                                  <td>Published</td>
                              </tr>
                              <tr>
                                  <td>Support</td>
                                  <td>Yes</td>
                              </tr>
                              </tbody>
                            </table>
                            </div>
                        </div>
                    </div>
                    <!-- /.panel -->
                    <div class="panel panel-default">
                        <div class="panel-heading">
                            <h4 class="panel-title">
                                <a class="noCrossRef accordion-toggle" data-toggle="collapse" data-parent="#accordion" href="#collapseEight">Simple Notification Service (SNS)</a>
                            </h4>
                        </div>
                        <div id="collapseEight" class="panel-collapse collapse noCrossRef">
                            <div class="panel-body">
                            <p>Amazon Simple Notification Service (SNS) is a highly available, durable, secure, fully managed pub/sub messaging service that enables you to decouple microservices, distributed systems, and serverless applications. Amazon SNS provides topics for high-throughput, push-based, many-to-many messaging. Using Amazon SNS topics, your publisher systems can fan out messages to a large number of subscriber endpoints for parallel processing, including Amazon SQS queues, AWS Lambda functions, and HTTP/S webhooks. Additionally, SNS can be used to fan out notifications to end users using mobile push, SMS, and email.</p><br>
                            <a href="https://aws.amazon.com/sns/?nc1=h_ls&whats-new-cards.sort-by=item.additionalFields.postDateTime&whats-new-cards.sort-order=desc">AWS Documentation</a><br>
                            <hr>
                            <table>
                              <thead>
                              <tr>
                                  <th>terraform-aws-module-sns-sa</th>
                                  <th></th>
                              </tr>
                              </thead>
                              <tbody>
                              <tr>
                                  <td>Git Repo</td>
                                  <td><a href="https://github.alm.europe.cloudcenter.corp/ccc-ccoe-aws/terraform-aws-module-sns-sa/tree/v1.1.2">Source Code</a></td>
                              </tr>
                              <tr>
                                  <td>README</td>
                                  <td><a href="https://github.alm.europe.cloudcenter.corp/ccc-ccoe-aws/terraform-aws-module-sns-sa/tree/v1.1.2/README.md">README</a> </td>
                              </tr>
                              <tr>
                                  <td><b>Latest Release Version</b></td>
                                  <td><b>v1.1.2</b></td>
                              </tr>
                              <tr>
                                  <td>Status</td>
                                  <td>Published</td>
                              </tr>
                              <tr>
                                  <td>Support</td>
                                  <td>Yes</td>
                              </tr>
                              </tbody>
                            </table>
                            </div>
                        </div>
                    </div>
                    <!-- /.panel -->
                    <div class="panel panel-default">
                        <div class="panel-heading">
                            <h4 class="panel-title">
                                <a class="noCrossRef accordion-toggle" data-toggle="collapse" data-parent="#accordion" href="#collapseNine">Lambda</a>
                            </h4>
                        </div>
                        <div id="collapseNine" class="panel-collapse collapse noCrossRef">
                            <div class="panel-body">
                            <p>You can use AWS Lambda to run your code in response to events, such as changes to data in an Amazon S3 bucket or an Amazon DynamoDB table; to run your code in response to HTTP requests using Amazon API Gateway; or invoke your code using API calls made using AWS SDKs. With these capabilities, you can use Lambda to easily build data processing triggers for AWS services like Amazon S3 and Amazon DynamoDB, process streaming data stored in Kinesis, or create your own back end that operates at AWS scale, performance, and security. You can also build serverless applications composed of functions that are triggered by events and automatically deploy them using CodePipeline and AWS CodeBuild.</p><br>
                            <a href="https://docs.aws.amazon.com/lambda/latest/dg/welcome.html">AWS Documentation</a><br>
                            <hr>
                            <table>
                              <thead>
                              <tr>
                                  <th>terraform-aws-module-lam-sm</th>
                                  <th></th>
                              </tr>
                              </thead>
                              <tbody>
                              <tr>
                                  <td>Git Repo</td>
                                  <td><a href="https://github.alm.europe.cloudcenter.corp/ccc-ccoe-aws/terraform-aws-module-lam-sm/tree/v1.3.1">Source Code</a></td>
                              </tr>
                              <tr>
                                  <td>README</td>
                                  <td><a href="https://github.alm.europe.cloudcenter.corp/ccc-ccoe-aws/terraform-aws-module-lam-sm/blob/v1.3.1/README.md">README</a> </td>
                              </tr>
                              <tr>
                                  <td><b>Latest Release Version</b></td>
                                  <td><b>v1.3.1</b></td>
                              </tr>
                              <tr>
                                  <td>Status</td>
                                  <td>Published</td>
                              </tr>
                              <tr>
                                  <td>Support</td>
                                  <td>Yes</td>
                              </tr>
                              </tbody>
                            </table>
                            </div>
                        </div>
                    </div>
                    <!-- /.panel -->
                    <div class="panel panel-default">
                        <div class="panel-heading">
                            <h4 class="panel-title">
                                <a class="noCrossRef accordion-toggle" data-toggle="collapse" data-parent="#accordion" href="#collapseTen">EC2 Auto Scaling</a>
                            </h4>
                        </div>
                        <div id="collapseTen" class="panel-collapse collapse noCrossRef">
                            <div class="panel-body">
                            <p>Amazon EC2 Auto Scaling helps you ensure that you have the correct number of Amazon EC2 instances available to handle the load for your application. You create collections of EC2 instances, called Auto Scaling groups. You can specify the minimum number of instances in each Auto Scaling group, and Amazon EC2 Auto Scaling ensures that your group never goes below this size. You can specify the maximum number of instances in each Auto Scaling group, and Amazon EC2 Auto Scaling ensures that your group never goes above this size. If you specify the desired capacity, either when you create the group or at any time thereafter, Amazon EC2 Auto Scaling ensures that your group has this many instances. If you specify scaling policies, then Amazon EC2 Auto Scaling can launch or terminate instances as demand on your application increases or decreases.</p><br>
                            <a href="https://docs.aws.amazon.com/autoscaling/ec2/userguide/what-is-amazon-ec2-auto-scaling.html">AWS Documentation</a><br>
                            <hr>
                            <table>
                              <thead>
                              <tr>
                                  <th>terraform-aws-module-aas-sa</th>
                                  <th></th>
                              </tr>
                              </thead>
                              <tbody>
                              <tr>
                                  <td>Git Repo</td>
                                  <td><a href="https://github.alm.europe.cloudcenter.corp/ccc-ccoe-aws/terraform-aws-module-aas-sa/tree/v1.0.4">Source Code</a></td>
                              </tr>
                              <tr>
                                  <td>README</td>
                                  <td><a href="https://github.alm.europe.cloudcenter.corp/ccc-ccoe-aws/terraform-aws-module-aas-sa/tree/v1.0.4/README.md">README</a> </td>
                              </tr>
                              <tr>
                                  <td><b>Latest Release Version</b></td>
                                  <td><b>v1.0.4</b></td>
                              </tr>
                              <tr>
                                  <td>Status</td>
                                  <td>Published</td>
                              </tr>
                              <tr>
                                  <td>Support</td>
                                  <td>Yes</td>
                              </tr>
                              </tbody>
                            </table>
                            </div>
                        </div>
                    </div>
                    <!-- /.panel -->
                    <div class="panel panel-default">
                        <div class="panel-heading">
                            <h4 class="panel-title">
                                <a class="noCrossRef accordion-toggle" data-toggle="collapse" data-parent="#accordion" href="#collapseEleven">CloudWatch</a>
                            </h4>
                        </div>
                        <div id="collapseEleven" class="panel-collapse collapse noCrossRef">
                            <div class="panel-body">
                            <p>Amazon CloudWatch monitors your Amazon Web Services (AWS) resources and the applications you run on AWS in real time. You can use CloudWatch to collect and track metrics, which are variables you can measure for your resources and applications. The CloudWatch home page automatically displays metrics about every AWS service you use.</p>
                            <p>You can additionally create custom dashboards to display metrics about your custom applications, and display custom collections of metrics that you choose. You can create alarms that watch metrics and send notifications or automatically make changes to the resources you are monitoring when a threshold is breached. For example, you can monitor the CPU usage and disk reads and writes of your Amazon EC2 instances and then use this data to determine whether you should launch additional instances to handle increased load. You can also use this data to stop under-used instances to save money.</p><br>
                            <a href="https://docs.aws.amazon.com/AmazonCloudWatch/latest/monitoring/WhatIsCloudWatch.html">AWS Documentation</a><br>
                            <hr>
                            <table>
                              <thead>
                              <tr>
                                  <th>terraform-aws-module-acw-sa</th>
                                  <th></th>
                              </tr>
                              </thead>
                              <tbody>
                              <tr>
                                  <td>Git Repo</td>
                                  <td><a href="https://github.alm.europe.cloudcenter.corp/ccc-ccoe-aws/terraform-aws-module-acw-sa/tree/v1.1.2">Source Code</a></td>
                              </tr>
                              <tr>
                                  <td>README</td>
                                  <td><a href="https://github.alm.europe.cloudcenter.corp/ccc-ccoe-aws/terraform-aws-module-acw-sa/blob/v1.1.2/README.md">README</a> </td>
                              </tr>
                              <tr>
                                  <td><b>Latest Release Version</b></td>
                                  <td><b>v1.1.2</b></td>
                              </tr>
                              <tr>
                                  <td>Status</td>
                                  <td>Published</td>
                              </tr>
                              <tr>
                                  <td>Support</td>
                                  <td>Yes</td>
                              </tr>
                              </tbody>
                            </table>
                            </div>
                        </div>
                    </div>
                    <!-- /.panel -->
                    <div class="panel panel-default">
                        <div class="panel-heading">
                            <h4 class="panel-title">
                                <a class="noCrossRef accordion-toggle" data-toggle="collapse" data-parent="#accordion" href="#collapseTwelve">Elastic Container Registry (ECR)</a>
                            </h4>
                        </div>
                        <div id="collapseTwelve" class="panel-collapse collapse noCrossRef">
                            <div class="panel-body">
                            <p>Amazon Elastic Container Registry (Amazon ECR) is a managed AWS Docker registry service that is secure, scalable, and reliable. Amazon ECR supports private Docker repositories with resource-based permissions using AWS IAM so that specific users or Amazon EC2 instances can access repositories and images. Developers can use the Docker CLI to push, pull, and manage images.</p><br>
                            <a href="https://docs.aws.amazon.com/AmazonECR/latest/userguide/what-is-ecr.html">AWS Documentation</a><br>
                            <hr>
                            <table>
                              <thead>
                              <tr>
                                  <th>terraform-aws-module-ecr-sm</th>
                                  <th></th>
                              </tr>
                              </thead>
                              <tbody>
                              <tr>
                                  <td>Git Repo</td>
                                  <td><a href="https://github.alm.europe.cloudcenter.corp/ccc-ccoe-aws/terraform-aws-module-ecr-sm/tree/v1.2.0">Source Code</a></td>
                              </tr>
                              <tr>
                                  <td>README</td>
                                  <td><a href="https://github.alm.europe.cloudcenter.corp/ccc-ccoe-aws/terraform-aws-module-ecr-sm/tree/v1.2.0/README.md">README</a> </td>
                              </tr>
                              <tr>
                                  <td><b>Latest Release Version</b></td>
                                  <td><b>v1.2.0</b></td>
                              </tr>
                              <tr>
                                  <td>Status</td>
                                  <td>Published</td>
                              </tr>
                              <tr>
                                  <td>Support</td>
                                  <td>Yes</td>
                              </tr>
                              </tbody>
                            </table>
                            </div>
                        </div>
                    </div>
                    <!-- /.panel -->
                    <div class="panel panel-default">
                        <div class="panel-heading">
                            <h4 class="panel-title">
                                <a class="noCrossRef accordion-toggle" data-toggle="collapse" data-parent="#accordion" href="#collapseThirdteen">Fargate</a>
                            </h4>
                        </div>
                        <div id="collapseThirdteen" class="panel-collapse collapse noCrossRef">
                            <div class="panel-body">
                            <p>AWS Fargate is a technology that you can use with Amazon ECS to run containers without having to manage servers or clusters of Amazon EC2 instances. With AWS Fargate, you no longer have to provision, configure, or scale clusters of virtual machines to run containers. This removes the need to choose server types, decide when to scale your clusters, or optimize cluster packing.</p>
                            <p>When you run your tasks and services with the Fargate launch type, you package your application in containers, specify the CPU and memory requirements, define networking and IAM policies, and launch the application. Each Fargate task has its own isolation boundary and does not share the underlying kernel, CPU resources, memory resources, or elastic network interface with another task.</p><br>
                            <a href="https://docs.aws.amazon.com/AmazonECS/latest/developerguide/AWS_Fargate.html">AWS Documentation</a><br>
                            <hr>
                            <table>
                              <thead>
                              <tr>
                                  <th>terraform-aws-module-ecr-sm</th>
                                  <th></th>
                              </tr>
                              </thead>
                              <tbody>
                              <tr>
                                  <td>Git Repo</td>
                                  <td><a href="https://github.alm.europe.cloudcenter.corp/ccc-ccoe-aws/terraform-aws-module-far-sm/tree/v1.2.1">Source Code</a></td>
                              </tr>
                              <tr>
                                  <td>README</td>
                                  <td><a href="https://github.alm.europe.cloudcenter.corp/ccc-ccoe-aws/terraform-aws-module-far-sm/blob/v1.2.1/README.md">README</a> </td>
                              </tr>
                              <tr>
                                  <td><b>Latest Release Version</b></td>
                                  <td><b>v1.2.1</b></td>
                              </tr>
                              <tr>
                                  <td>Status</td>
                                  <td>Published</td>
                              </tr>
                              <tr>
                                  <td>Support</td>
                                  <td>Yes</td>
                              </tr>
                              </tbody>
                            </table>
                            </div>
                        </div>
                    </div>
                    <!-- /.panel -->
                    <div class="panel panel-default">
                        <div class="panel-heading">
                            <h4 class="panel-title">
                                <a class="noCrossRef accordion-toggle" data-toggle="collapse" data-parent="#accordion" href="#collapseFourteen">Secrets Manager</a>
                            </h4>
                        </div>
                        <div id="collapseFourteen" class="panel-collapse collapse noCrossRef">
                            <div class="panel-body">
                            <p>Secrets Manager enables you to replace hardcoded credentials in your code, including passwords, with an API call to Secrets Manager to retrieve the secret programmatically. This helps ensure the secret can’t be compromised by someone examining your code, because the secret no longer exists in the code. Also, you can configure Secrets Manager to automatically rotate the secret for you according to a specified schedule. This enables you to replace long-term secrets with short-term ones, significantly reducing the risk of compromise.</p><br>
                            <a href="https://docs.aws.amazon.com/secretsmanager/latest/userguide/intro.html">AWS Documentation</a><br>
                            <hr>
                            <table>
                              <thead>
                              <tr>
                                  <th>terraform-aws-module-asm-sa</th>
                                  <th></th>
                              </tr>
                              </thead>
                              <tbody>
                              <tr>
                                  <td>Git Repo</td>
                                  <td><a href="https://github.alm.europe.cloudcenter.corp/ccc-ccoe-aws/terraform-aws-module-asm-sa/tree/v1.2.0">Source Code</a></td>
                              </tr>
                              <tr>
                                  <td>README</td>
                                  <td><a href="https://github.alm.europe.cloudcenter.corp/ccc-ccoe-aws/terraform-aws-module-asm-sa/blob/v1.2.0/README.md">README</a> </td>
                              </tr>
                              <tr>
                                  <td><b>Latest Release Version</b></td>
                                  <td><b>v1.2.0</b></td>
                              </tr>
                              <tr>
                                  <td>Status</td>
                                  <td>Published</td>
                              </tr>
                              <tr>
                                  <td>Support</td>
                                  <td>Yes</td>
                              </tr>
                              </tbody>
                            </table>
                            </div>
                        </div>
                    </div>
                    <!-- /.panel -->
                    <div class="panel panel-default">
                        <div class="panel-heading">
                            <h4 class="panel-title">
                                <a class="noCrossRef accordion-toggle" data-toggle="collapse" data-parent="#accordion" href="#collapseFifthteen">Elastic Container Service (ECS)</a>
                            </h4>
                        </div>
                        <div id="collapseFifthteen" class="panel-collapse collapse noCrossRef">
                            <div class="panel-body">
                            <p>Amazon Elastic Container Service (Amazon ECS) is a highly scalable, fast, container management service that makes it easy to run, stop, and manage containers on a cluster. Your containers are defined in a task definition which you use to run individual tasks or as a service. You can run your tasks and services on a serverless infrastructure that is managed by AWS Fargate or, for more control over your infrastructure, you can run your tasks and services on a cluster of Amazon EC2 instances that you manage.</p>
                            <p>Amazon ECS enables you to launch and stop your container-based applications with simple API calls. You can also retrieve the state of your cluster from a centralized service and, for existing users of Amazon EC2, access many familiar Amazon EC2 features.</p>
                            <p>You can schedule the placement of your containers across your cluster based on your resource needs, isolation policies, and availability requirements. With Amazon ECS, you do not have to operate your own cluster management and configuration management systems or worry about scaling your management infrastructure.</p><br>
                            <a href="https://docs.aws.amazon.com/AmazonECS/latest/developerguide/Welcome.html">AWS Documentation</a><br>
                            <hr>
                            <table>
                              <thead>
                              <tr>
                                  <th>terraform-aws-module-cs2-sm</th>
                                  <th></th>
                              </tr>
                              </thead>
                              <tbody>
                              <tr>
                                  <td>Git Repo</td>
                                  <td><a href="https://github.alm.europe.cloudcenter.corp/ccc-ccoe-aws/terraform-aws-module-cs2-sm/tree/v1.4.0">Source Code</a></td>
                              </tr>
                              <tr>
                                  <td>README</td>
                                  <td><a href="https://github.alm.europe.cloudcenter.corp/ccc-ccoe-aws/terraform-aws-module-cs2-sm/tree/v1.4.0/README.md">README</a> </td>
                              </tr>
                              <tr>
                                  <td><b>Latest Release Version</b></td>
                                  <td><b>v1.4.0</b></td>
                              </tr>
                              <tr>
                                  <td>Status</td>
                                  <td>Published</td>
                              </tr>
                              <tr>
                                  <td>Support</td>
                                  <td>Yes</td>
                              </tr>
                              </tbody>
                            </table>
                            </div>
                        </div>
                    </div>
                    <!-- /.panel -->
                    <div class="panel panel-default">
                        <div class="panel-heading">
                            <h4 class="panel-title">
                                <a class="noCrossRef accordion-toggle" data-toggle="collapse" data-parent="#accordion" href="#collapseSixteen">Simple Queue Service (SQS)</a>
                            </h4>
                        </div>
                        <div id="collapseSixteen" class="panel-collapse collapse noCrossRef">
                            <div class="panel-body">
                            <p>Amazon Simple Queue Service (Amazon SQS) offers a secure, durable, and available hosted queue that lets you integrate and decouple distributed software systems and components. Amazon SQS offers common constructs such as dead-letter queues and cost allocation tags. It provides a generic web services API and it can be accessed by any programming language that the AWS SDK supports. Amazon SQS supports both standard and FIFO queues.</p><br>
                            <a href="https://docs.aws.amazon.com/AWSSimpleQueueService/latest/SQSDeveloperGuide/welcome.html">AWS Documentation</a><br>
                            <hr>
                            <table>
                              <thead>
                              <tr>
                                  <th>terraform-aws-module-sqs-sa</th>
                                  <th></th>
                              </tr>
                              </thead>
                              <tbody>
                              <tr>
                                  <td>Git Repo</td>
                                  <td><a href="https://github.alm.europe.cloudcenter.corp/ccc-ccoe-aws/terraform-aws-module-sqs-sa/tree/v1.2.0">Source Code</a></td>
                              </tr>
                              <tr>
                                  <td>README</td>
                                  <td><a href="https://github.alm.europe.cloudcenter.corp/ccc-ccoe-aws/terraform-aws-module-sqs-sa/blob/v1.2.0/README.md">README</a> </td>
                              </tr>
                              <tr>
                                  <td><b>Latest Release Version</b></td>
                                  <td><b>v1.2.0</b></td>
                              </tr>
                              <tr>
                                  <td>Status</td>
                                  <td>Published</td>
                              </tr>
                              <tr>
                                  <td>Support</td>
                                  <td>Yes</td>
                              </tr>
                              </tbody>
                            </table>
                            </div>
                        </div>
                    </div>
                    <!-- /.panel -->    
                    <div class="panel panel-default">
                        <div class="panel-heading">
                            <h4 class="panel-title">
                                <a class="noCrossRef accordion-toggle" data-toggle="collapse" data-parent="#accordion" href="#collapseSeventeen">Athena</a>
                            </h4>
                        </div>
                        <div id="collapseSeventeen" class="panel-collapse collapse noCrossRef">
                            <div class="panel-body">
                            <p>Amazon Athena is an interactive query service that makes it easy to analyze data directly in Amazon Simple Storage Service (Amazon S3) using standard SQL. With a few actions in the AWS Management Console, you can point Athena at your data stored in Amazon S3 and begin using standard SQL to run ad-hoc queries and get results in seconds.</p>
                            <p>Athena is serverless, so there is no infrastructure to set up or manage, and you pay only for the queries you run. Athena scales automatically—executing queries in parallel—so results are fast, even with large datasets and complex queries.</p><br>
                            <a href="https://docs.aws.amazon.com/athena/latest/ug/what-is.html">AWS Documentation</a><br>
                            <hr>
                            <table>
                              <thead>
                              <tr>
                                  <th>terraform-aws-module-ath-sa</th>
                                  <th></th>
                              </tr>
                              </thead>
                              <tbody>
                              <tr>
                                  <td>Git Repo</td>
                                  <td><a href="https://github.alm.europe.cloudcenter.corp/ccc-ccoe-aws/terraform-aws-module-ath-sa/tree/v1.1.0">Source Code</a></td>
                              </tr>
                              <tr>
                                  <td>README</td>
                                  <td><a href="https://github.alm.europe.cloudcenter.corp/ccc-ccoe-aws/terraform-aws-module-ath-sa/tree/v1.1.0/README.md">README</a> </td>
                              </tr>
                              <tr>
                                  <td><b>Latest Release Version</b></td>
                                  <td><b>v1.1.0</b></td>
                              </tr>
                              <tr>
                                  <td>Status</td>
                                  <td>Published</td>
                              </tr>
                              <tr>
                                  <td>Support</td>
                                  <td>Yes</td>
                              </tr>
                              </tbody>
                            </table>
                            </div>
                        </div>
                    </div>
                    <!-- /.panel --> 
                    <div class="panel panel-default">
                        <div class="panel-heading">
                            <h4 class="panel-title">
                                <a class="noCrossRef accordion-toggle" data-toggle="collapse" data-parent="#accordion" href="#collapseEighteen">Elastic Kubernetes Service (EKS)</a>
                            </h4>
                        </div>
                        <div id="collapseEighteen" class="panel-collapse collapse noCrossRef">
                            <div class="panel-body">
                            <p>Amazon Elastic Kubernetes Service (Amazon EKS) is a managed service that makes it easy for you to run Kubernetes on AWS without needing to stand up or maintain your own Kubernetes control plane. Kubernetes is an open-source system for automating the deployment, scaling, and management of containerized applications.</p>
                            <p>Amazon EKS runs Kubernetes control plane instances across multiple Availability Zones to ensure high availability. Amazon EKS automatically detects and replaces unhealthy control plane instances, and it provides automated version upgrades and patching for them.</p>   
                            <p>Amazon EKS runs up-to-date versions of the open-source Kubernetes software, so you can use all the existing plugins and tooling from the Kubernetes community. Applications running on Amazon EKS are fully compatible with applications running on any standard Kubernetes environment, whether running in on-premises data centers or public clouds. This means that you can easily migrate any standard Kubernetes application to Amazon EKS without any code modification required.</p><br>
                            <a href="https://docs.aws.amazon.com/eks/latest/userguide/what-is-eks.html">AWS Documentation</a><br>
                            <hr>
                            <table>
                              <thead>
                              <tr>
                                  <th>terraform-aws-module-eks-sm</th>
                                  <th></th>
                              </tr>
                              </thead>
                              <tbody>
                              <tr>
                                  <td>Git Repo</td>
                                  <td><a href="https://github.alm.europe.cloudcenter.corp/ccc-ccoe-aws/terraform-aws-module-eks-sm/tree/v1.3.0">Source Code</a></td>
                              </tr>
                              <tr>
                                  <td>README</td>
                                  <td><a href="https://github.alm.europe.cloudcenter.corp/ccc-ccoe-aws/terraform-aws-module-eks-sm/tree/v1.3.0/README.md">README</a> </td>
                              </tr>
                              <tr>
                                  <td><b>Latest Release Version</b></td>
                                  <td><b>v1.3.0</b></td>
                              </tr>
                              <tr>
                                  <td>Status</td>
                                  <td>Published</td>
                              </tr>
                              <tr>
                                  <td>Support</td>
                                  <td>Yes</td>
                              </tr>
                              </tbody>
                            </table>
                            </div>
                        </div>
                    </div>
                    <!-- /.panel -->  
                    <div class="panel panel-default">
                        <div class="panel-heading">
                            <h4 class="panel-title">
                                <a class="noCrossRef accordion-toggle" data-toggle="collapse" data-parent="#accordion" href="#collapseNineteen">ElastiCache</a>
                            </h4>
                        </div>
                        <div id="collapseNineteen" class="panel-collapse collapse noCrossRef">
                            <div class="panel-body">
                            <p>Amazon ElastiCache is a web service that makes it easy to set up, manage, and scale a distributed in-memory data store or cache environment in the cloud. It provides a high-performance, scalable, and cost-effective caching solution. At the same time, it helps remove the complexity associated with deploying and managing a distributed cache environment.</p><br>
                            <a href="https://docs.aws.amazon.com/AmazonElastiCache/latest/red-ug/WhatIs.html">AWS Documentation</a><br>
                            <hr>
                            <table>
                              <thead>
                              <tr>
                                  <th>terraform-aws-module-cac-sa</th>
                                  <th></th>
                              </tr>
                              </thead>
                              <tbody>
                              <tr>
                                  <td>Git Repo</td>
                                  <td><a href="https://github.alm.europe.cloudcenter.corp/ccc-ccoe-aws/terraform-aws-module-cac-sa/tree/v1.2.0">Source Code</a></td>
                              </tr>
                              <tr>
                                  <td>README</td>
                                  <td><a href="https://github.alm.europe.cloudcenter.corp/ccc-ccoe-aws/terraform-aws-module-cac-sa/blob/v1.2.0/README.md">README</a> </td>
                              </tr>
                              <tr>
                                  <td><b>Latest Release Version</b></td>
                                  <td><b>v1.2.0</b></td>
                              </tr>
                              <tr>
                                  <td>Status</td>
                                  <td>Published</td>
                              </tr>
                              <tr>
                                  <td>Support</td>
                                  <td>Yes</td>
                              </tr>
                              </tbody>
                            </table>
                            </div>
                        </div>
                    </div>
                    <!-- /.panel -->  
                    <div class="panel panel-default">
                        <div class="panel-heading">
                            <h4 class="panel-title">
                                <a class="noCrossRef accordion-toggle" data-toggle="collapse" data-parent="#accordion" href="#collapseTwenty">API Gateway</a>
                            </h4>
                        </div>
                        <div id="collapseTwenty" class="panel-collapse collapse noCrossRef">
                            <div class="panel-body">
                            <p>Amazon API Gateway is an AWS service for creating, publishing, maintaining, monitoring, and securing REST, HTTP, and WebSocket APIs at any scale. API developers can create APIs that access AWS or other web services, as well as data stored in the AWS Cloud. As an API Gateway API developer, you can create APIs for use in your own client applications. Or you can make your APIs available to third-party app developers.</p><br>
                            <a href="https://docs.aws.amazon.com/apigateway/latest/developerguide/welcome.html">AWS Documentation</a><br>
                            <hr>
                            <table>
                              <thead>
                              <tr>
                                  <th>terraform-aws-module-api-sa</th>
                                  <th></th>
                              </tr>
                              </thead>
                              <tbody>
                              <tr>
                                  <td>Git Repo</td>
                                  <td><a href="https://github.alm.europe.cloudcenter.corp/ccc-ccoe-aws/terraform-aws-module-api-sa/tree/v1.2.0">Source Code</a></td>
                              </tr>
                              <tr>
                                  <td>README</td>
                                  <td><a href="https://github.alm.europe.cloudcenter.corp/ccc-ccoe-aws/terraform-aws-module-api-sa/blob/v1.2.0/README.md">README</a> </td>
                              </tr>
                              <tr>
                                  <td><b>Latest Release Version</b></td>
                                  <td><b>v1.2.0</b></td>
                              </tr>
                              <tr>
                                  <td>Status</td>
                                  <td>Published</td>
                              </tr>
                              <tr>
                                  <td>Support</td>
                                  <td>Yes</td>
                              </tr>
                              </tbody>
                            </table>
                            </div>
                        </div>
                    </div>
                    <!-- /.panel -->
                    <div class="panel panel-default">
                        <div class="panel-heading">
                            <h4 class="panel-title">
                                <a class="noCrossRef accordion-toggle" data-toggle="collapse" data-parent="#accordion" href="#collapseTwentyone">Relational Database Service (RDS)</a>
                            </h4>
                        </div>
                        <div id="collapseTwentyone" class="panel-collapse collapse noCrossRef">
                            <div class="panel-body">
                            <p>Amazon Relational Database Service (Amazon RDS) is a web service that makes it easier to set up, operate, and scale a relational database in the AWS Cloud. It provides cost-efficient, resizable capacity for an industry-standard relational database and manages common database administration tasks.</p><br>
                            <a href="https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/Welcome.html">AWS Documentation</a><br>
                            <hr>
                            <table>
                              <thead>
                              <tr>
                                  <th>terraform-aws-module-rds-sa</th>
                                  <th></th>
                              </tr>
                              </thead>
                              <tbody>
                              <tr>
                                  <td>Git Repo</td>
                                  <td><a href="https://github.alm.europe.cloudcenter.corp/ccc-ccoe-aws/terraform-aws-module-rds-sa/tree/v1.2.0">Source Code</a></td>
                              </tr>
                              <tr>
                                  <td>README</td>
                                  <td><a href="https://github.alm.europe.cloudcenter.corp/ccc-ccoe-aws/terraform-aws-module-rds-sa/blob/v1.2.0/README.md">README</a> </td>
                              </tr>
                              <tr>
                                  <td><b>Latest Release Version</b></td>
                                  <td><b>v1.2.0</b></td>
                              </tr>
                              <tr>
                                  <td>Status</td>
                                  <td>Published</td>
                              </tr>
                              <tr>
                                  <td>Support</td>
                                  <td>Yes</td>
                              </tr>
                              </tbody>
                            </table>
                            </div>
                        </div>
                    </div>
                    <!-- /.panel -->
                    <div class="panel panel-default">
                        <div class="panel-heading">
                            <h4 class="panel-title">
                                <a class="noCrossRef accordion-toggle" data-toggle="collapse" data-parent="#accordion" href="#collapseTwentytwo">Glue</a>
                            </h4>
                        </div>
                        <div id="collapseTwentytwo" class="panel-collapse collapse noCrossRef">
                            <div class="panel-body">
                            <p>AWS Glue is a fully managed ETL (extract, transform, and load) service that makes it simple and cost-effective to categorize your data, clean it, enrich it, and move it reliably between various data stores and data streams. AWS Glue consists of a central metadata repository known as the AWS Glue Data Catalog, an ETL engine that automatically generates Python or Scala code, and a flexible scheduler that handles dependency resolution, job monitoring, and retries. AWS Glue is serverless, so there’s no infrastructure to set up or manage.</p>
                            <p>AWS Glue is designed to work with semi-structured data. It introduces a component called a dynamic frame, which you can use in your ETL scripts. A dynamic frame is similar to an Apache Spark dataframe, which is a data abstraction used to organize data into rows and columns, except that each record is self-describing so no schema is required initially. With dynamic frames, you get schema flexibility and a set of advanced transformations specifically designed for dynamic frames. You can convert between dynamic frames and Spark dataframes, so that you can take advantage of both AWS Glue and Spark transformations to do the kinds of analysis that you want. </p><br>
                            <a href="https://docs.aws.amazon.com/glue/latest/dg/what-is-glue.html">AWS Documentation</a><br>
                            <hr>
                            <table>
                              <thead>
                              <tr>
                                  <th>terraform-aws-module-agl-sm</th>
                                  <th></th>
                              </tr>
                              </thead>
                              <tbody>
                              <tr>
                                  <td>Git Repo</td>
                                  <td><a href="https://github.alm.europe.cloudcenter.corp/ccc-ccoe-aws/terraform-aws-module-agl-sm/tree/v1.2.0">Source Code</a></td>
                              </tr>
                              <tr>
                                  <td>README</td>
                                  <td><a href="https://github.alm.europe.cloudcenter.corp/ccc-ccoe-aws/terraform-aws-module-agl-sm/tree/v1.2.0/README.md">README</a> </td>
                              </tr>
                              <tr>
                                  <td><b>Latest Release Version</b></td>
                                  <td><b>v1.2.0</b></td>
                              </tr>
                              <tr>
                                  <td>Status</td>
                                  <td>Published</td>
                              </tr>
                              <tr>
                                  <td>Support</td>
                                  <td>Yes</td>
                              </tr>
                              </tbody>
                            </table>
                            </div>
                        </div>
                    </div>
                    <!-- /.panel -->  
                    <div class="panel panel-default">
                        <div class="panel-heading">
                            <h4 class="panel-title">
                                <a class="noCrossRef accordion-toggle" data-toggle="collapse" data-parent="#accordion" href="#collapseTwentythree">Elastic File System (EFS)</a>
                            </h4>
                        </div>
                        <div id="collapseTwentythree" class="panel-collapse collapse noCrossRef">
                            <div class="panel-body">
                            <p>Amazon Elastic File System (Amazon EFS) provides a simple, scalable, fully managed elastic NFS file system for use with AWS Cloud services and on-premises resources. It is built to scale on demand to petabytes without disrupting applications, growing and shrinking automatically as you add and remove files, eliminating the need to provision and manage capacity to accommodate growth. Amazon EFS has a simple web services interface that allows you to create and configure file systems quickly and easily. The service manages all the file storage infrastructure for you, meaning that you can avoid the complexity of deploying, patching, and maintaining complex file system configurations.</p><br>
                            <a href="https://docs.aws.amazon.com/efs/latest/ug/whatisefs.html">AWS Documentation</a><br>
                            <hr>
                            <table>
                              <thead>
                              <tr>
                                  <th>terraform-aws-module-efs-sa</th>
                                  <th></th>
                              </tr>
                              </thead>
                              <tbody>
                              <tr>
                                  <td>Git Repo</td>
                                  <td><a href="https://github.alm.europe.cloudcenter.corp/ccc-ccoe-aws/terraform-aws-module-efs-sa/tree/v1.2.0">Source Code</a></td>
                              </tr>
                              <tr>
                                  <td>README</td>
                                  <td><a href="https://github.alm.europe.cloudcenter.corp/ccc-ccoe-aws/terraform-aws-module-efs-sa/blob/v1.2.0/README.md">README</a> </td>
                              </tr>
                              <tr>
                                  <td><b>Latest Release Version</b></td>
                                  <td><b>v1.2.0</b></td>
                              </tr>
                              <tr>
                                  <td>Status</td>
                                  <td>Published</td>
                              </tr>
                              <tr>
                                  <td>Support</td>
                                  <td>Yes</td>
                              </tr>
                              </tbody>
                            </table>
                            </div>
                        </div>
                    </div>
                    <!-- /.panel --> 
                    <div class="panel panel-default">
                        <div class="panel-heading">
                            <h4 class="panel-title">
                                <a class="noCrossRef accordion-toggle" data-toggle="collapse" data-parent="#accordion" href="#collapseTwentyfour">RDS Oracle</a>
                            </h4>
                        </div>
                        <div id="collapseTwentyfour" class="panel-collapse collapse noCrossRef">
                            <div class="panel-body">
                            <p>Amazon Relational Database Service (Amazon RDS) is a web service that makes it easier to set up, operate, and scale a relational database in the AWS Cloud. It provides cost-efficient, resizable capacity for an industry-standard relational database and manages common database administration tasks.</p>
                            <p>With Oracle on Amazon RDS you can create DB instances and DB snapshots, point-in-time restores, and automated or manual backups. You can use DB instances running Oracle inside a VPC. You can also add features to your Oracle DB instance by enabling various options. Amazon RDS supports Multi-AZ deployments for Oracle as a high-availability, failover solution.</p><br>
                            <a href="https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/CHAP_Oracle.html">AWS Documentation</a><br>
                            <hr>
                            <table>
                              <thead>
                              <tr>
                                  <th>terraform-aws-module-rdo-sa</th>
                                  <th></th>
                              </tr>
                              </thead>
                              <tbody>
                              <tr>
                                  <td>Git Repo</td>
                                  <td><a href="https://github.alm.europe.cloudcenter.corp/ccc-ccoe-aws/terraform-aws-module-rdo-sa/tree/v1.2.0">Source Code</a></td>
                              </tr>
                              <tr>
                                  <td>README</td>
                                  <td><a href="https://github.alm.europe.cloudcenter.corp/ccc-ccoe-aws/terraform-aws-module-rdo-sa/blob/v1.2.0/README.md">README</a></td>
                              </tr>
                              <tr>
                                  <td><b>Latest Release Version</b></td>
                                  <td><b>v1.2.0</b></td>
                              </tr>
                              <tr>
                                  <td>Status</td>
                                  <td>Published</td>
                              </tr>
                              <tr>
                                  <td>Support</td>
                                  <td>Yes</td>
                              </tr>
                              </tbody>
                            </table>
                            </div>
                        </div>
                    </div>
                    <!-- /.panel -->
                    <div class="panel panel-default">
                        <div class="panel-heading">
                            <h4 class="panel-title">
                                <a class="noCrossRef accordion-toggle" data-toggle="collapse" data-parent="#accordion" href="#collapseTwentyfive">EventBridge (AEB)</a>
                            </h4>
                        </div>
                        <div id="collapseTwentyfive" class="panel-collapse collapse noCrossRef">
                            <div class="panel-body">
                            <p>Amazon EventBridge is a serverless event bus service that makes it easy to connect your applications with data from a variety of sources. EventBridge delivers a stream of real-time data from your own applications, Software-as-a-Service (SaaS) applications, and AWS services and routes that data to targets such as AWS Lambda.</p>
                            <p>You can set up routing rules to determine where to send your data to build application architectures that react in real time to all of your data sources. EventBridge allows you to build event driven architectures, which are loosely coupled and distributed.</p><br>
                            <a href="https://docs.aws.amazon.com/eventbridge/latest/userguide/what-is-amazon-eventbridge.html">AWS Documentation</a><br>
                            <hr>
                            <table>
                              <thead>
                              <tr>
                                  <th>terraform-aws-module-aeb-sa</th>
                                  <th></th>
                              </tr>
                              </thead>
                              <tbody>
                              <tr>
                                  <td>Git Repo</td>
                                  <td><a href="https://github.alm.europe.cloudcenter.corp/ccc-ccoe-aws/terraform-aws-module-aeb-sa/tree/v1.0.0">Source Code</a></td>
                              </tr>
                              <tr>
                                  <td>README</td>
                                  <td><a href="https://github.alm.europe.cloudcenter.corp/ccc-ccoe-aws/terraform-aws-module-aeb-sa/blob/v1.0.0/README.md">README</a> </td>
                              </tr>
                              <tr>
                                  <td><b>Latest Release Version</b></td>
                                  <td><b>v1.0.0</b></td>
                              </tr>
                              <tr>
                                  <td>Status</td>
                                  <td>Published</td>
                              </tr>
                              <tr>
                                  <td>Support</td>
                                  <td>Yes</td>
                              </tr>
                              </tbody>
                            </table>
                            </div>
                        </div>
                    </div>
                    <!-- /.panel -->
                    <div class="panel panel-default">
                        <div class="panel-heading">
                            <h4 class="panel-title">
                                <a class="noCrossRef accordion-toggle" data-toggle="collapse" data-parent="#accordion" href="#collapseTwentysix">Avamar/ DataDomain</a>
                            </h4>
                        </div>
                        <div id="collapseTwentysix" class="panel-collapse collapse noCrossRef">
                            <div class="panel-body">
                            <p>AVE and DD VE are software-defined versions of the industry leading protection software. The integration of them offers the benefits of Data Domain's scalability and performance, and the simplicity and efficiency of Avamar's integration with business critical applications and robust backup and recovery policy management features. The offer of this solution will provide one-click deployment of Avamar and Data Domain together in the AWS. Their is no need to individually deploy the separate Avamar and Data Domain components.</p>
                            <p>AVE 19.3 now supports up to 16 TB and DD VE 5.0 supports up to 96 TB.</p><br>
                            <a href="https://aws.amazon.com/marketplace/pp/Dell-EMC-Dell-EMC-Avamar-and-Data-Domain-Virtual-E/prodview-32kgz2d4acdns">AWS Documentation</a><br>
                            <hr>
                            <table>
                              <thead>
                              <tr>
                                  <th>terraform-aws-module-avamardatadomain</th>
                                  <th></th>
                              </tr>
                              </thead>
                              <tbody>
                              <tr>
                                  <td>Git Repo</td>
                                  <td><a href="https://github.alm.europe.cloudcenter.corp/ccc-ccoe-aws/terraform-aws-module-avamardatadomain/tree/v1.0.0">Source Code</a></td>
                              </tr>
                              <tr>
                                  <td>README</td>
                                  <td><a href="https://github.alm.europe.cloudcenter.corp/ccc-ccoe-aws/terraform-aws-module-avamardatadomain/blob/v1.0.0/README.md">README</a> </td>
                              </tr>
                              <tr>
                                  <td><b>Latest Release Version</b></td>
                                  <td><b>v1.0.0</b></td>
                              </tr>
                              <tr>
                                  <td>Status</td>
                                  <td>Published</td>
                              </tr>
                              <tr>
                                  <td>Support</td>
                                  <td>Yes</td>
                              </tr>
                              </tbody>
                            </table>
                            </div>
                        </div>
                    </div>
                    <!-- /.panel -->
</div>
<!-- /.panel-group -->

## EaC Internal Modules   

<div class="panel-group" id="accordion">
                    <div class="panel panel-default">
                        <div class="panel-heading">
                            <h4 class="panel-title">
                                <a class="noCrossRef accordion-toggle" data-toggle="collapse" data-parent="#accordion" href="#collapse1">Security Group</a>
                            </h4>
                        </div>
                        <div id="collapse1" class="panel-collapse collapse noCrossRef">
                            <div class="panel-body">
                            <p>A security group acts as a virtual firewall for your instance to control inbound and outbound traffic. When you launch an instance in a VPC, you can assign up to five security groups to the instance. Security groups act at the instance level, not the subnet level. Therefore, each instance in a subnet in your VPC can be assigned to a different set of security groups.If you launch an instance using the Amazon EC2 API or a command line tool and you don't specify a security group, the instance is automatically assigned to the default security group for the VPC. If you launch an instance using the Amazon EC2 console, you have an option to create a new security group for the instance.For each security group, you add rules that control the inbound traffic to instances, and a separate set of rules that control the outbound traffic. This section describes the basic things that you need to know about security groups for your VPC and their rules.</p>
                            <a href="https://docs.aws.amazon.com/es_es/vpc/latest/userguide/VPC_SecurityGroups.html">AWS Documentation</a><br>
                            <hr>
                            <table>
                              <thead>
                              <tr>
                                  <th>terraform-aws-module-nsg-sa</th>
                                  <th></th>
                              </tr>
                              </thead>
                              <tbody>
                              <tr>
                                  <td>Git Repo</td>
                                  <td><a href="https://github.alm.europe.cloudcenter.corp/ccc-ccoe-aws/terraform-aws-module-nsg-sa/tree/v1.1.0">Source Code</a></td>
                              </tr>
                              <tr>
                                  <td>README</td>
                                  <td><a href="https://github.alm.europe.cloudcenter.corp/ccc-ccoe-aws/terraform-aws-module-nsg-sa/blob/v1.1.0/README.md">README</a> </td>
                              </tr>
                              <tr>
                                  <td><b>Latest Release Version</b></td>
                                  <td><b>v1.1.0</b></td>
                              </tr>
                              <tr>
                                  <td>Status</td>
                                  <td>Published</td>
                              </tr>
                              <tr>
                                  <td>Support</td>
                                  <td>Yes</td>
                              </tr>
                              </tbody>
                            </table>
                            </div>
                        </div>
                    </div>
                    <!-- /.panel -->
                    <div class="panel panel-default">
                        <div class="panel-heading">
                            <h4 class="panel-title">
                                <a class="noCrossRef accordion-toggle" data-toggle="collapse" data-parent="#accordion" href="#collapse2">Parameter Store</a>
                            </h4>
                        </div>
                        <div id="collapse2" class="panel-collapse collapse noCrossRef">
                            <div class="panel-body">
                            <p>AWS Systems Manager Parameter Store provides secure, hierarchical storage for configuration data management and secrets management. You can store data such as passwords, database strings, Amazon Machine Image (AMI) IDs, and license codes as parameter values. You can store values as plain text or encrypted data. You can reference Systems Manager parameters in your scripts, commands, SSM documents, and configuration and automation workflows by using the unique name that you specified when you created the parameter.</p>
                            <a href="https://docs.aws.amazon.com/systems-manager/latest/userguide/systems-manager-parameter-store.html">AWS Documentation</a><br>
                            <hr>
                            <table>
                              <thead>
                              <tr>
                                  <th>terraform-aws-module-parameterstore</th>
                                  <th></th>
                              </tr>
                              </thead>
                              <tbody>
                              <tr>
                                  <td>Git Repo</td>
                                  <td><a href="https://github.alm.europe.cloudcenter.corp/ccc-ccoe-aws/terraform-aws-module-parameterstore/tree/v1.0.0">Source Code</a></td>
                              </tr>
                              <tr>
                                  <td>README</td>
                                  <td><a href="https://github.alm.europe.cloudcenter.corp/ccc-ccoe-aws/terraform-aws-module-parameterstore/blob/v1.0.0/README.md">README</a> </td>
                              </tr>
                              <tr>
                                  <td><b>Latest Release Version</b></td>
                                  <td><b>v1.0.0</b></td>
                              </tr>
                              <tr>
                                  <td>Status</td>
                                  <td>Published</td>
                              </tr>
                              <tr>
                                  <td>Support</td>
                                  <td>Yes</td>
                              </tr>
                              </tbody>
                            </table>
                            </div>
                        </div>
                    </div>
                    <!-- /.panel -->
                    <div class="panel panel-default">
                        <div class="panel-heading">
                            <h4 class="panel-title">
                                <a class="noCrossRef accordion-toggle" data-toggle="collapse" data-parent="#accordion" href="#collapse3">VPC-Endpoint</a>
                            </h4>
                        </div>
                        <div id="collapse3" class="panel-collapse collapse noCrossRef">
                            <div class="panel-body">
                            <p>A VPC endpoint enables private connections between your VPC and supported AWS services and VPC endpoint services powered by AWS PrivateLink. AWS PrivateLink is a technology that enables you to privately access services by using private IP addresses. Traffic between your VPC and the other service does not leave the Amazon network. A VPC endpoint does not require an internet gateway, virtual private gateway, NAT device, VPN connection, or AWS Direct Connect connection. Instances in your VPC do not require public IP addresses to communicate with resources in the service. VPC endpoints are virtual devices. They are horizontally scaled, redundant, and highly available VPC components. They allow communication between instances in your VPC and services without imposing availability risks</p>
                            <a href="https://docs.aws.amazon.com/vpc/latest/userguide/vpc-endpoints.html">AWS Documentation</a><br>
                            <hr>
                            <table>
                              <thead>
                              <tr>
                                  <th>terraform-aws-module-vce-sa</th>
                                  <th></th>
                              </tr>
                              </thead>
                              <tbody>
                              <tr>
                                  <td>Git Repo</td>
                                  <td><a href="https://github.alm.europe.cloudcenter.corp/ccc-ccoe-aws/terraform-aws-module-vce-sa/tree/v1.0.0">Source Code</a></td>
                              </tr>
                              <tr>
                                  <td>README</td>
                                  <td><a href="https://github.alm.europe.cloudcenter.corp/ccc-ccoe-aws/terraform-aws-module-vce-sa/blob/v1.0.0/README.md">README</a> </td>
                              </tr>
                              <tr>
                                  <td><b>Latest Release Version</b></td>
                                  <td><b>v1.0.0</b></td>
                              </tr>
                              <tr>
                                  <td>Status</td>
                                  <td>Published</td>
                              </tr>
                              <tr>
                                  <td>Support</td>
                                  <td>Yes</td>
                              </tr>
                              </tbody>
                            </table>
                            </div>
                        </div>
                    </div>
                    <!-- /.panel -->
                    <div class="panel panel-default">
                        <div class="panel-heading">
                            <h4 class="panel-title">
                                <a class="noCrossRef accordion-toggle" data-toggle="collapse" data-parent="#accordion" href="#collapse4">Route Table (RTB)</a>
                            </h4>
                        </div>
                        <div id="collapse4" class="panel-collapse collapse noCrossRef">
                            <div class="panel-body">
                            <p>Your VPC has an implicit router, and you use route tables to control where network traffic is directed. Each subnet in your VPC must be associated with a route table, which controls the routing for the subnet (subnet route table). You can explicitly associate a subnet with a particular route table. Otherwise, the subnet is implicitly associated with the main route table. A subnet can only be associated with one route table at a time, but you can associate multiple subnets with the same subnet route table.</p>
                            <a href="https://docs.aws.amazon.com/vpc/latest/userguide/VPC_Route_Tables.html">AWS Documentation</a><br>
                            <hr>
                            <table>
                              <thead>
                              <tr>
                                  <th>terraform-aws-module-rtb-sa</th>
                                  <th></th>
                              </tr>
                              </thead>
                              <tbody>
                              <tr>
                                  <td>Git Repo</td>
                                  <td><a href="https://github.alm.europe.cloudcenter.corp/ccc-ccoe-aws/terraform-aws-module-rtb-sa/tree/v1.0.0">Source Code</a></td>
                              </tr>
                              <tr>
                                  <td>README</td>
                                  <td><a href="https://github.alm.europe.cloudcenter.corp/ccc-ccoe-aws/terraform-aws-module-rtb-sa/blob/v1.0.0/README.md">README</a> </td>
                              </tr>
                              <tr>
                                  <td><b>Latest Release Version</b></td>
                                  <td><b>v1.0.0</b></td>
                              </tr>
                              <tr>
                                  <td>Status</td>
                                  <td>Published</td>
                              </tr>
                              <tr>
                                  <td>Support</td>
                                  <td>Yes</td>
                              </tr>
                              </tbody>
                            </table>
                            </div>
                        </div>
                    </div>


                    <!-- /.panel -->
                    <!-- <div class="panel panel-default">
                        <div class="panel-heading">
                            <h4 class="panel-title">
                                <a class="noCrossRef accordion-toggle" data-toggle="collapse" data-parent="#accordion" href="#collapseTwentyfive">RDS MariaDB</a>
                            </h4>
                        </div>
                        <div id="collapseTwentyfive" class="panel-collapse collapse noCrossRef">
                            <div class="panel-body">
                            <p>Amazon Relational Database Service (Amazon RDS) is a web service that makes it easier to set up, operate, and scale a relational database in the AWS Cloud. It provides cost-efficient, resizable capacity for an industry-standard relational database and manages common database administration tasks.</p>
                            <p>You first use the Amazon RDS management tools or interfaces to create an Amazon RDS MariaDB DB instance. You can then use the Amazon RDS tools to perform management actions for the DB instance, such as reconfiguring or resizing the DB instance, authorizing connections to the DB instance, creating and restoring from backups or snapshots, creating Multi-AZ secondaries, creating read replicas, and monitoring the performance of the DB instance. You use standard MariaDB utilities and applications to store and access the data in the DB instance</p><br>
                            <a href="https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/CHAP_MariaDB.html">AWS Documentation</a><br>
                            <hr>
                            <table>
                              <thead>
                              <tr>
                                  <th>terraform-aws-module-rdo-sa</th>
                                  <th></th>
                              </tr>
                              </thead>
                              <tbody>
                              <tr>
                                  <td>Git Repo</td>
                                  <td><a href="https://github.alm.europe.cloudcenter.corp/ccc-ccoe-aws/terraform-aws-module-rdm-sa/tree/v1.0.0">Source Code</a></td>
                              </tr>
                              <tr>
                                  <td>README</td>
                                  <td><a href="https://github.alm.europe.cloudcenter.corp/ccc-ccoe-aws/terraform-aws-module-rdm-sa/blob/v1.0.0/README.md">README</a> </td>
                              </tr>
                              <tr>
                                  <td><b>Latest Release Version</b></td>
                                  <td><b>v1.0.0</b></td>
                              </tr>
                              <tr>
                                  <td>Status</td>
                                  <td>Published</td>
                              </tr>
                              <tr>
                                  <td>Support</td>
                                  <td>Yes</td>
                              </tr>
                              </tbody>
                            </table>
                            </div>
                        </div>
                    </div> -->
                    <!-- /.panel -->             

</div>
<!-- /.panel-group -->

{% include links.html %}


   


<script language="javascript"> 
months = ['01', '02', '03', '04', '05', '06', '07', '08', '09', '10', '11', '12']; 
var d=new Date();
var weekday=new Array(7);
weekday[0]="Sunday";
weekday[1]="Monday";
weekday[2]="Tuesday";
weekday[3]="Wednesday";
weekday[4]="Thursday";
weekday[5]="Friday";
weekday[6]="Saturday";

var d = new Date();
(d.getFullYear());


var theDate = new Date(document.lastModified); 
theDate.setTime((theDate.getTime()+(60*60)) ) 
with (theDate) { 
document.write("<i>Last updated "+d.getFullYear()+'-'+months[getMonth()]+'-'+getDate()+' '+weekday[getDay()]+'   '+getHours()+':'+getMinutes()+" GMT</i>") 
} 

</script> 


