Title: AWS Security 

# AWS Security

## News

### Cloud Security Reading List

Low volume mailing list (once per week) that highlights security-related news focused on the cloud native landscape

<https://cloudseclist.com>

## General

### AWS Security notices

<https://aws.amazon.com/security/security-bulletins/> / [RSS feed](https://aws.amazon.com/security/security-bulletins/feed/)

### Amazon Linux Security Center (ALAS)

Bulletins for security or privacy events pertaining to the Amazon Linux AMI (Amazon Linux AMI Security Advisory).

<https://alas.aws.amazon.com>

### AWS Security Workshops

collection of workshops and other hands-on content aimed at helping you gain an understanding of the AWS service ecosystem.

<https://awssecworkshops.com>

### AWS Compliance Center

<https://atlas.aws>

### Managed policies

Unofficial updated AWS Managed Policies

<https://gist.github.com/gene1wood/55b358748be3c314f956>

### Policy repository

A free repository of customizable AWS security configurations and best practices

<https://asecure.cloud>

### MITRE ATT&CK AWS Matrix

<https://attack.mitre.org/matrices/enterprise/cloud/aws/>

### Hacking the Cloud

Hacking the cloud is a encyclopedia of attacks/tactics/techniques that offensive security professionals can use on their next cloud exploitation adventure.

<https://hackingthe.cloud>

## AWS Security gurus

Short-list of blogs' experts and their twitter accounts

### Scott Piper

<https://summitroute.com> - <https://twitter.com/0xdabbad00>

### Kinnaird McQuade

<https://kmcquade.com> - <https://twitter.com/kmcquade3>

### Chris Farris

<https://www.chrisfarris.com> - <https://twitter.com/jcfarris>

### Ian Mckay

<https://onecloudplease.com> - <https://twitter.com/iann0036>

## Tools

### toniblyx's arsenal

Massive tool list

<https://github.com/toniblyx/my-arsenal-of-aws-security-tools>

### ThreatResponse - Hardening

A Free Open Source Security Suite for Hardening and Responding in AWS.

<https://github.com/ThreatResponse>

### Diffy - DFIR tool

Diffy is a digital forensics and incident response (DFIR) tool developed by Netflix's Security Intelligence and Response Team (SIRT).

<https://github.com/Netflix-Skunkworks/diffy>

### LambdaGuard

AWS Lambda auditing tool designed to create asset visibility and provide actionable results.

<https://github.com/Skyscanner/LambdaGuard>

### BinaryAlert

Serverless, Real-time & Retroactive Malware Detection

<https://github.com/airbnb/binaryalert>

### Cloud Assesment products

Aka Cloud Security Posture Management. CSPM is a class of security tools as defined by Gartner include use cases for compliance monitoring, DevOps integration, incident response, risk assessment, and risk visualization.

Product | CSP support, remarks | Link
------------ | ------------- | ------------
Divvy Cloud | AWS, Azure, GCP, Alibaba, Kubernetes | <https://divvycloud.com>
Cloud Custodian | AWS, Azure, GCP. Open Source, good community | <https://cloudcustodian.io>
Palto Alto Prisma Cloud (Redlock) | AWS, Azure, GCP, Alibaba, Kubernetes, Doker, IBM Cloud | <https://www.paloaltonetworks.com/prisma/cloud>
Netflix Security Monkey | AWS, GCP. End of life 2020 | <https://github.com/Netflix/security_monkey>
TurBot | AWS, Azure, GCP | <https://turbot.com/>
DisruptOps | ? | <https://disruptops.com/>
CheckPoint CloudGuard Dome9 | AWS, Azure, GCP. Some remediations focused primarily on network and IAM | <https://dome9.com/>
Aqua CloudSploit | AWS, Azure, GCP, Oracle Cloud | <https://cloudsploit.com/>
Trend Micro Cloud Conformity | AWS, (Azure) | <https://www.cloudconformity.com/>
Fugue | AWS, Azure | <https://www.fugue.co/>

### Infrastructure-as-code (IaC) scanners

Prevent misconfigurations during build time

Scanner | Compatible software | Link
------------ | ------------- | ------------
Checkov | Terraform, CloudFormation | <https://github.com/bridgecrewio/checkov>
terraform-aws-secure-baseline | Terraform | <https://github.com/nozaq/terraform-aws-secure-baseline>
tfsec | Terraform | <https://github.com/liamg/tfsec>
Terrascan | Terraform | <https://github.com/cesar-rodriguez/terrascan>
CFripper | CloudFormation | <https://github.com/Skyscanner/cfripper>
cfn-nag | CloudFormation | <https://github.com/stelligent/cfn_nag>
Regula | Terraform | <https://github.com/fugue/regula>

### truffleHog - Find secrets

Searches through git repositories for secrets (like AWS keys), digging deep into commit history and branches. This is effective at finding secrets accidentally committed.

<https://github.com/dxa4481/truffleHog>

### Cloud Container Attack Tool (CCAT)

Cloud Container Attack Tool (CCAT) is a tool for testing security of container environments.

<https://github.com/RhinoSecurityLabs/ccat>

### barq

A AWS Cloud Post Exploitation framework

<https://github.com/Voulnet/barq>

### awspx

A graph-based tool for visualizing effective access and resource relationships in AWS environments. 

<https://github.com/FSecureLABS/awspx>

### CloudTrail Application Anomaly Detection

 It keeps track of all API actions a principal calls (that are tracked by CloudTrail) for a N day period and alerts on new API calls after the N day period.

<https://github.com/Netflix-Skunkworks/cloudtrail-anomaly>

### Detecting Credential Compromise

Cloudformation Template and Lambda to detect if Instance Profile credentials are being used outside your AWS Account. 

<https://github.com/jchrisfarris/detect-credential-compromise>

### CloudTrail Partitioner

This project sets up partitioned Athena tables for your CloudTrail logs and updates the partitions nightly. As new AWS accounts begin sending you logs or new AWS regions come online, your paritions will always be up-to-date.

<https://github.com/duo-labs/cloudtrail-partitioner>

### Varna

Quick & Cheap AWS CloudTrail Monitoring with Event Query Language (EQL) 

<https://github.com/endgameinc/varna>

### IAM Permissions parser

<https://gist.github.com/0xdabbad00/581714de8f0957fce30efcb1634785a9>

### Open S3 bucket search engine

<https://buckets.grayhatwarfare.com/>

### CloudScraper

Enumerate targets in search of cloud resources

<https://github.com/jordanpotti/cloudscraper>

### Bash-my-AWS

CLI commands for AWS

<https://bash-my-aws.org/>

### AWS Security Toolbox (AST)

<https://github.com/z0ph/aws-security-toolbox>

### Prowler: AWS CIS Benchmark Tool

<https://github.com/toniblyx/prowler>

### IMDS-Filterd

Intercepts and filters requests to the EC2 Instance Metadata Service

<https://github.com/cperciva/imds-filterd>

### aws_ir

Python installable command line utiltity for mitigation of host and key compromises

<https://github.com/ThreatResponse/aws_ir>

### PMapper

A tool for quickly evaluating IAM permissions in AWS

<https://github.com/nccgroup/PMapper>

### DVSA

a Damn Vulnerable Serverless Application

<https://github.com/OWASP/DVSA>

### StreamAlert

Serverless, realtime data analysis framework which empowers you to ingest, analyze, and alert on data from any environment, using datasources and alerting logic you define

<https://github.com/airbnb/streamalert>

### kms-host-key

An easy way to give all your EC2 instances SSH host certificates 

<https://github.com/glassechidna/kms-host-key>

### Cartography

Cartography is a Python tool that consolidates infrastructure assets and the relationships between them in an intuitive graph view powered by a Neo4j database

<https://github.com/lyft/cartography>

### Policy decode

<https://bigorange.cloud/actions>

### Parliament

AWS IAM linting library. It reviews policies looking for problems.

<https://github.com/duo-labs/parliament>

Web version : <https://parliament.summitroute.com>

### Terraform Parliament

Run Parliament AWS IAM Checker on Terraform Files

<https://github.com/rdkls/tf-parliament>

### CloudMapper

CloudMapper helps you analyze your Amazon Web Services (AWS) environments. 

<https://github.com/duo-labs/cloudmapper>

### enumerate-iam

Enumeratethe permissions associated with AWS credential set 

<https://github.com/andresriancho/enumerate-iam>

### Nimbostratus

Tools for fingerprinting and exploiting Amazon cloud infrastructures

<https://github.com/andresriancho/nimbostratus>

### cloud-service-enum

<https://github.com/NotSoSecure/cloud-service-enum>

### caponeme

Vulnerable cloud environment that meant to mock Capital One Breach for educational purposes

<https://github.com/avishayil/caponeme>

### IncidentResponseGenerator

This application simulates an attack on AWS infrastructure

<https://github.com/disruptops/IncidentResponseGenerator>

### Policy Sentry

IAM Least Privilege Policy Generator, auditor, and analysis database

<https://github.com/salesforce/policy_sentry>

### Scout Suite

Multi-Cloud Security Auditing Tool

<https://github.com/nccgroup/ScoutSuite>

### aws_consoler

A utility to convert your AWS CLI credentials into AWS console access. 

<https://github.com/NetSPI/aws_consoler>

### ElectricEye

Continuously monitor your AWS services for configurations that can lead to degradation of confidentiality, integrity or availability. All results will be sent to Security Hub for further aggregation and analysis. 

<https://github.com/jonrau1/ElectricEye>

## Challenges / CTF

### flAWS

Two online challenges about S3 security misconfigurations.

<http://flaws.cloud>

<http://flaws2.cloud>

### S3 Game

Another good challenge on S3.

<http://s3game-level1.s3-website.us-east-2.amazonaws.com>

### Lambda Shell

This is a simple AWS lambda function that does a straight exec. Essentially giving you a shell directly in my AWS infrastructure to just run your commands.

<http://www.lambdashell.com>

### CloudGoat - "Vulnerable by Design" AWS deployment tool

It allows you to hone your cloud cybersecurity skills by creating and completing several "capture-the-flag" style scenarios.

<https://github.com/RhinoSecurityLabs/cloudgoat>

### KrkAnalytica

<https://www.securing.pl/krkanalytica/>

### CyberRange

Bootstrap framework for a complete offensive, defensive, reverse engineering, & security intelligence tooling in a private research lab using the AWS Cloud.

<https://github.com/secdevops-cuse/CyberRange>

## S3 tools

### Bucket Stream

Find interesting Amazon S3 Buckets by watching certificate transparency logs.

<https://github.com/eth0izzle/bucket-stream>

### aws-s3-data-finder

AWS S3 Sensitive Data Search 

<https://github.com/Ucnt/aws-s3-data-finder/>

### lazys3

A Ruby script to bruteforce for AWS s3 buckets using different permutations.

<https://github.com/nahamsec/lazys3>

### BucketScanner

A tool for testing objects' permissions in AWS buckets 

<https://github.com/securing/BucketScanner>

### S3scanner

Scan for open AWS S3 buckets and dump the contents 

<https://github.com/sa7mon/S3Scanner>

### AirIAM

It moves existing AWS IAM configurations to a least privelege Terraform. 

<https://airiam.io/>

### SkyWrapper

SkyWrapper helps to discover suspicious creation forms and uses of temporary tokens in AWS

<https://github.com/cyberark/SkyWrapper>

### Panther

A Cloud-Native SIEM for the Modern Security Team. Panther is a platform for detecting threats with log data, improving cloud security posture, and conducting investigations.

<https://runpanther.io>

<https://github.com/panther-labs/panther>

### Cloudsplaining

Cloudsplaining is an AWS IAM Security Assessment tool that identifies violations of least privilege and generates a risk-prioritized HTML report with a triage worksheet.

<https://github.com/salesforce/cloudsplaining>

### CRFT

No-Code Automation for Cybersecurity

<https://crft.app>

### actionhero

Action Hero is a sidecar style utility to assist with creating least privilege IAM Policies for AWS.

<https://github.com/princespaghetti/actionhero>

### Leonidas - Attack Detection

A tool for automating the simulation of attacks against cloud environments.

<https://github.com/fsecurelabs/leonidas>
<http://detectioninthe.cloud>

### cloud-forensics-utils

Python library to carry out DFIR analysis on the Cloud

#<https://github.com/google/cloud-forensics-utils>

### MAMIP - Monitor AWS Managed IAM Policies

<https://github.com/z0ph/aws_managed_policies>

### CloudFrontier

Monitor the internet attack surface of various public cloud environments. Currently supports AWS, GCP, Azure, DigitalOcean and Oracle Cloud.

<https://github.com/riskprofiler/CloudFrontier>

### AWS CloudFormation Guard

[PREVIEW] A set of tools to check AWS CloudFormation templates for policy compliance using a simple, policy-as-code, declarative syntax 

<https://github.com/aws-cloudformation/cloudformation-guard>

### Aardvark

Aardvark is a multi-account AWS IAM Access Advisor API (and caching layer).

<https://github.com/Netflix-Skunkworks/aardvark>

### CloudTracker

It helps you find over-privileged IAM users and roles by comparing CloudTrail logs with current IAM policies. 

<https://github.com/duo-labs/cloudtracker>

### Action Hero

Action Hero is a sidecar style utility to assist with creating least privilege IAM Policies for AWS by using AWS SDK Client Side Monitoring.

<https://github.com/princespaghetti/actionhero>

### AWS Auto Remediate

Open source application to instantly remediate common security issues through the use of AWS Config

<https://github.com/servian/aws-auto-remediate>

### lsh - The Lambda shell

Run interactive shell commands on AWS Lambda

<https://github.com/tobilg/lsh>

### Offensive Terraform Modules

Automated multi step offensive attack modules with Infrastructure as Code (IAC).

<https://offensive-terraform.github.io>

## Publications / Posts

### Rhino Security Labs blog

<https://rhinosecuritylabs.com/blog-technical/?category=aws>

### Security roadmap

Excellent roadmap from a consultant (founder of flAWS challenges). Updated on May 2020.

<https://summitroute.com/downloads/aws_security_maturity_roadmap-Summit_Route.pdf>

### AWS re:Invent 2019 Sessions : Security, Compliance, and Identity

<https://www.youtube.com/playlist?list=PL2yQDdvlhXf9Ub-ekxAq0wMJpslV562SP>

### Privilege escalation examples

<https://know.bishopfox.com/research/privilege-escalation-in-aws>

### Finding evil in AWS: A key pair to remember

<https://expel.io/blog/finding-evil-in-aws>

### The Extended AWS Security Ramp-Up Guide

<https://research.nccgroup.com/2020/04/24/the-extended-aws-security-ramp-up-guide>

### Breaking and Pwning Apps and Servers on AWS and Azure

Free Training Courseware and Labs

<https://github.com/appsecco/breaking-and-pwning-apps-and-servers-aws-azure-training>

### How we abused Slack's TURN servers to gain access to internal services

Slack’s TURN server allowed relaying of TCP connections and UDP packets to internal Slack network and meta-data services on AWS.

<https://www.rtcsec.com/2020/04/01-slack-webrtc-turn-compromise>

### How to build a useful (and entertaining) threat emulation exercise for AWS

<https://expel.io/blog/how-to-build-useful-threat-emulation-exercise-aws>

### Murder in the Amazon cloud

Code Spaces had all of its files deleted, including backups, and had to shutdown within 24 hours of their incident.

<https://www.infoworld.com/article/2608076/murder-in-the-amazon-cloud.html>

### Top 10 security items to improve in your AWS account

From AWS Security Blog

<https://aws.amazon.com/blogs/security/top-10-security-items-to-improve-in-your-aws-account>

### Unsecured databases attacked 18 times per day by hackers

Someone did set up an Elasticsearch honeypot and watched it destroyed. Over three dozen attacks occurred before the database was even indexed by search engines like Shodan / BinaryEdge. (not sure it's was on AWS)

<https://www.comparitech.com/blog/information-security/unsecured-database-honeypot>

### Access Keys in AWS Lambda

Let’s look at AWS Access Keys inside a Lambda function, from how they are populated into the function’s execution context, how long they last, how to exfiltrate them out and use them, and how we might detect an compromised access keys.

<https://www.keithrozario.com/2020/06/access-keys-in-aws-lambda.html>

### Reverse engineering AWS Lambda

<https://www.denialof.services/lambda>

### Library of Cloud security posts

Another impresive repo of cloud security posts

<https://www.zotero.org/groups/2507373/cloudsecurity/items/D4KJ4WIK/library>

### Fixing 5 Common AWS IAM Errors

<https://info.acloud.guru/resources/fixing-5-common-aws-iam-errors>


### Open Source DFIR blog posts (Google)

Introducing Libcloudforensics

<https://osdfir.blogspot.com/2020/05/introducing-libcloudforensics.html>

 Forensic Disk Copies in GCP & AWS

<https://osdfir.blogspot.com/2020/06/forensic-disk-copies-in-gcp-aws.html>

Libcloudforensics and Cloud Logs

<https://osdfir.blogspot.com/2020/06/libcloudforensics-and-cloud-logs.html>

Incident Response in the Cloud

<https://osdfir.blogspot.com/2020/07/incident-response-in-cloud.html>

### Access Keys in AWS Lambda

<https://www.keithrozario.com/2020/06/access-keys-in-aws-lambda.html>

### Fixing 5 Common AWS IAM Errors

<https://acloudguru.com/blog/engineering/fixing-5-common-aws-iam-errors>

### Controlling egress traffic with Istio 

<https://banzaicloud.com/blog/istio-external-demo>

### Tools for Cloud examination (Forensic) - Google

<https://github.com/randorisec/talks/blob/upload/RandoriSec-Friends2020-Enlarge_your_toolkit/RandoriSec-Friends-Tools_for_Cloud_Examination_Thomas_Chopitea.pdf>

### 27 Things AWS Can Do to Reduce Cloud Security Misconfigurations

<https://medium.com/@matthewdf10/27-things-aws-can-do-to-reduce-cloud-security-misconfigurations-f3ed06d6aba8>

### AWS Mindmap

<https://twitter.com/jhencinski/status/1283810412950106112>

### AWS Lambda abuse

<https://luminousmen.com/post/aws-lambda-abuse>

### A few thoughts on the $80 million fine from the Capital One Breach

<https://twitter.com/kmcquade3/status/1291801858676228098>

### An AWS IAM Security Tooling Reference

<https://ramimac.me/cloudsec/security/aws-iam-tool-reference>

### Cloud Encryption is worthless

<https://www.chrisfarris.com/post/cloud-encryption>

### AWS Exposable Resources

Resource types that can be publicly exposed on AWS

<https://github.com/SummitRoute/aws_exposable_resources>

### Investigating S3 Scanning Activites on AWS 

<https://www.logsec.cloud/blog/2020-06-04-investigating-on-aws>