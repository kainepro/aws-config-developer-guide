# rds\-logging\-enabled<a name="rds-logging-enabled"></a>

Checks if log types exported to Amazon CloudWatch for an Amazon Relational Database Service \(Amazon RDS\) instance are enabled\. The rule is NON\_COMPLIANT if any such log types are not enabled\.

**Identifier:** RDS\_LOGGING\_ENABLED

**Trigger type:** Configuration changes

**AWS Region:**All supported AWS Regions except China \(Ningxia\), Europe \(Milan\), Africa \(Cape Town\) Regions

**Parameters:**

additionalLogs \(Optional\)Type: StringMap  
Comma\-separated list of engine names and log type names\. For example, "additionalLogs": "oracle: general, slowquery ; aurora: alert, slowquery"

## AWS CloudFormation template<a name="w24aac11c29c17d259c15"></a>

To create AWS Config managed rules with AWS CloudFormation templates, see [Creating AWS Config Managed Rules With AWS CloudFormation Templates](aws-config-managed-rules-cloudformation-templates.md)\.