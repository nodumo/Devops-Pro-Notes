AWS IAM
=======

:::danger
Must know! This is the backbone of AWS security. Know the ins and outst before moving into Solutions Architect Pro or Devops Engineer Pro!
:::

### Terms
* AssumeRole 
* PaasRole

### Concepts
* Login vs Iam API access 
* PaasRole

### Usecases 
* STS service 
* Hooking into account created to send a notification 
* Hooking into account created to disable login and IAM 
* Created a work tasks account and have an admin account and admin account users need access to the work task account. Where do the IAM roles get created 

https://youtu.be/viVoZBc-33s?t=146

### Misc
```
Sample ARNs to be aware of
arn:aws:iam::123456789012:root
arn:aws:iam::123456789012:user/username
arn:aws:iam::123456789012:user/division_abc/subdivision_xyz/JaneDoe
arn:aws:iam::123456789012:group/Developers
arn:aws:iam::123456789012:group/division_abc/subdivision_xyz/product_A/Developers
arn:aws:iam::123456789012:role/S3Access
Service ARNS
arn:aws:ec2:ap-southeast-1:123456789123:volume/vol-03303bf453f8d7ee5
```



Organizations 
=======
:::danger
Must know! This is the backbone of AWS!
:::
### Terms and concepts 
* Control Tower 
* Organizations OU
* Landing Zones
* Cross account permissions 

### Usecases 
* Created a work tasks account and have an admin account and admin account users need access to the work task account. Where do the IAM roles get created 


### Concepts 
* Cross account permissions 
* 	- setup s3 replication 
* Organization restrictions 
* Parent org vs child org 
* Disable account right after its created 
*  ~ login 
*  ~ accont iam 



Cloud Formation
=======
### Terms and concepts 
* Stacks 
* Stack Sets 
* Nested Stacks 
* Instrisinc Functions 
### Usecases 
* Cloud Faied to create resource with permissions
* Cloudformation run permissions
* Cloudformation failure cases 
* Clodudformation failure to roleback
* Cloudformation make sure multiple stacks run in order. cloudformations keep changging

 
 
AWS Services (General!)
=======

### Storage 

#### S3 
* S3 events 
* Replication
* Direct connection
* Processing with Lambda 

#### FS
* File system types
    * Linux 


AWS Services (Security)
=======

#### Guard duty 
AWS Guard duty

#### SCP 
* S


AWS Services (Database)
=======

#### Guard duty 
AWS Guard duty

#### SCP 
* S


#### AWS Application Load Balancer(ALB)
* Attach target group
* Deployment options 
* SSL certificate 
    * Attach application load balancer
 
EC2 
=======
- EC2 auto-scaling group 
- Target group 
- EC2 auto-scaling lifecycle hooks 
- EC2 standby by 
- AWS inspector

Dynamodb 
======
- global table 
- multi-region
- dynamodb 


EBS volumes
======= 
EBS volumes resources id 
EBS volumes encrypted 
EBS volumses are oncly for Tagging EBS volumes for backup 
EBS make volume required fir backup


Beanstalk notitifcations 
Beanstalk


Cloudwatch agent EC2 
Clouwatch alarm 
API Gateway - Canary Deployment

EFS file system 
EFS file system between accounts 
EFS file system lambda in one account and lambda in the other 
Cloudwatch
Config events 


control tower guard rail 

AWS code builld 
========
* deployment groups
* multoople applications with different deployment groups 
* CodeStar 
* Code Artifact 
* Building applications locally 
    * Q: Artifact must be built before installation. 
    * Q: License must be added before installation
* Codebuild env variables parameter store vs 
* Codebuild IAM 

AWS confug 
=======
Config rules (when evaluated)
Config rules across accounts 

S3 replication between accounts 


Lifecycle for code deploy


Code deploy sources 
AWS codestar 

Complex IAM stuff 


AWA3950B0541


aws event for codebuild aws failed build events 
aws codebui


cloudwatch event filter 
cloudwatch event transform


inspector
guard duty

ian other account permissions
iam
assume role
passrole


Organization
 - workload account
 - admin account 
 
IAM when to create iam roles 
When to use iam groups 
When to use attribute based 
Assume Role 
passrole


 

 
Kinesis
Scaling aws kinesis consumers 
Scaling aws kinese lambda consumers 
Using Kineses with cloudwatch


Security team need realtime response when   cloud config rule broken 

Notification that security groups has changed 



Restrict account from creating service in different region and to notificy 

aws least privelege iam 


traffic between vpc in different availability must be encrypted while 
	- direct connection, peer vpc, overlapping didr
	
	
	
	
SSM DOCUMENT

Root user's arn::id 
common arns
importantarns

lambda vpc

efs file systems

* 
* control tower 




  