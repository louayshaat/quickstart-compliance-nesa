# quickstart-compliance-nesa
## Standardized Architecture for NESA on the AWS Cloud

This Quick Start sets up an AWS Cloud environment that provides a standardized architecture for NESA compliance. 
The templates in the Quick Start automatically configure the AWS resources and deploy a multi-tier, Linux-based web application in a few simple steps. The Quick Start includes a main template for initial setup and three optional templates for additional customization.

**Main template**

![Main template architecture](https://d0.awsstatic.com/partner-network/QuickStart/datasheets/standard-networking-architecture-pci-dss-on-aws.png)

**Centralized logging template**

![Centralized logging template architecture](https://docs.aws.amazon.com/quickstart/latest/compliance-pci/images/centralized-logging-architecture.png)

**Database template**

![Database template architecture](https://docs.aws.amazon.com/quickstart/latest/compliance-pci/images/database-architecture.png)

**Web application template**

![Web application template architecture](https://docs.aws.amazon.com/quickstart/latest/compliance-pci/images/web-application-architecture.png)

## Installation
- Create a net ec2 key pair
- Create a new s3 bucket
- Copy the folder "quickstart-compliance-nesa" into that bucket
- Navigate to Cloudformation and use the s3 URL for the Cloudformation template "s3bucket/quickstart-compliance-nesa/templates/main.template.yaml"
