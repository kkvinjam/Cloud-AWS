# Description
A Collection of templates and instructions for setting up and using AWS Systems Manager to install and uninstall the CrowdStrike Falcon agent in AWS.

# Important Information: 
* The solution requires version *2.3.1550.0* or later of the AWS Sytems Manager agent installed on the host.

* The DEFAULT version of the package will be (latest-release)-2. For example
if the latest release of the linux sensor is 5.34.9918 the DEFAULT version installed would be 5.33.9808.  
It is expected that once installed, sensor versions will be managed via the falcon console.
![](./documentation/using/media/downloads.png) 

# Folder Structure

## CloudFormation
#### *cft*
Folder containing a CloudFormation template **CrowdStrike-ssm-setup.yaml**.
#### *lambda*
The **staging** Folder contains the lambda zip **createSsmParams.zip** and **layer.zip** files that must be uploaded to an S3 bucket prior to deploying the CFT.

## Documentation

#### *Overview*
Overview of the integration

[https://github.com/CrowdStrike/Cloud-AWS/blob/master/systems-manager/documentation/overview/AWS-Systems-Manager-Intro.md](https://github.com/CrowdStrike/Cloud-AWS/blob/master/systems-manager/documentation/overview/AWS-Systems-Manager-Intro.md)

#### *Setup*
How to setup your account using the CloudFormation template

[https://github.com/CrowdStrike/Cloud-AWS/blob/master/systems-manager/documentation/setup/Setup-your-account.md](https://github.com/CrowdStrike/Cloud-AWS/blob/master/systems-manager/documentation/setup/Setup-your-account.md)

#### *Using Sytems Manager with CrowdStrike*

[https://github.com/CrowdStrike/Cloud-AWS/blob/master/systems-manager/documentation/using/Using-Crowdstrike-with-Systems-Manager.md](https://github.com/CrowdStrike/Cloud-AWS/blob/master/systems-manager/documentation/using/Using-Crowdstrike-with-Systems-Manager.md)

