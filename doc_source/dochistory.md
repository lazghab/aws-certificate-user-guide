# Document history<a name="dochistory"></a>



The following table describes the documentation release history of AWS Certificate Manager beginning in 2018\.

| Change | Description | Date | 
| --- |--- |--- |
| [Updating key algorithm types for import](#dochistory) | Certificates imported into ACM may now have keys with additional RSA and Elliptic Curve algorithms\. For a list of currently supported key algorithms, see [https://docs.aws.amazon.com/acm/latest/userguide/import-certificate-prerequisites.html](https://docs.aws.amazon.com/acm/latest/userguide/import-certificate-prerequisites.html)\. | July 14, 2021 | 
| [Promoting "Monitoring and Logging" as a separate chapter\.](#dochistory) | Moved monitoring and logging documentation to its own chapter\. This change covers CloudWatch Metrics, CloudWatch Events/EventBridge, and CloudTrail\. For more information, see [https://docs.aws.amazon.com/acm/latest/userguide/monitoring-and-logging.html](https://docs.aws.amazon.com/acm/latest/userguide/monitoring-and-logging.html)\. | March 23, 2021 | 
| [Added CloudWatch Metrics and Events support](#dochistory) | Added DaysToExpiry metric and event and supporting APIs\. For more information, see [https://docs.aws.amazon.com/acm/latest/userguide/cloudwatch-metrics.html](https://docs.aws.amazon.com/acm/latest/userguide/cloudwatch-metrics.html) and [https://docs.aws.amazon.com/acm/latest/userguide/cloudwatch-events.html](https://docs.aws.amazon.com/acm/latest/userguide/cloudwatch-events.html)\. | March 3, 2021 | 
| [Added cross\-account support](#dochistory) | Added cross\-account support for using private CAs from ACM Private CA\. For more information, see [https://docs.aws.amazon.com/acm/latest/userguide/ca-access.html](https://docs.aws.amazon.com/acm/latest/userguide/ca-access.html)\. | August 17, 2020 | 
| [Added region support](#dochistory) | Added region support for the AWS China \(Beijing and Ningxia\) Regions\. For a complete list of supported regions, see [https://docs.aws.amazon.com/general/latest/gr/rande.html#acm-pca_region](https://docs.aws.amazon.com/general/latest/gr/rande.html#acm-pca_region)\. | March 4, 2020 | 
| [Added renewal workflow testing](#dochistory) | Customers can now manually test the configuration of their ACM managed renewal workflow\. For more information, see [Testing ACM's Managed Renewal Configuration](https://docs.aws.amazon.com/acm/latest/userguide/manual-renewal.html)\. | March 14, 2019 | 
| [Certificate transparency logging now default](#dochistory) | Added ability to publish ACM public certificates into certificate transparency logs by default\. | April 24, 2018 | 
| [Launching ACM Private CA](#dochistory) | Launched ACM Private Certificate Manager \(CM\), and extension of AWS Certificate Manager that allows users to establish a secure managed infrastructure for issuing and revoking private digital certificates\. For more information, see [AWS Private Certificate Authority](https://docs.aws.amazon.com/acm-pca/latest/userguide/PcaWelcome.html)\. | April 4, 2018 | 
| [Certificate transparency logging](#dochistory) | Added certificate transparency logging to Best Practices\. | March 27, 2018 | 

The following table describes the documentation release history of AWS Certificate Manager prior to 2018\.


| Change | Description | Release Date | 
| --- | --- | --- | 
| New content | Added DNS validation to [DNS validationDNS validation](dns-validation.md)\.  | November 21, 2017 | 
| New content | Added new Java code examples to [Using the ACM API](sdk.md)\.  | October 12, 2017 | 
| New content | Added information about CAA records to [\(Optional\) Configure a CAA record](setup-caa.md)\.  | September 21, 2017 | 
| New content | Added information about \.IO domains to [Troubleshooting](troubleshooting.md)\.  | July 07, 2017 | 
| New content | Added information about reimporting a certificate to [Reimporting a certificate](import-reimport.md)\.  | July 07, 2017 | 
| New content | Added information about certificate pinning to [Best practices](acm-bestpractices.md) and to [Troubleshooting](troubleshooting.md)\.  | July 07, 2017 | 
| New content | Added AWS CloudFormation to [Services integrated with AWS Certificate Manager](acm-services.md)\.  | May 27, 2017 | 
| Update | Added more information to [Quotas](acm-limits.md)\.  | May 27, 2017 | 
| New content | Added documentation about [Identity and access management for AWS Certificate Manager](security-iam.md)\.  | April 28, 2017 | 
| Update | Added a graphic to show where validation email is sent\. See [Email validation](email-validation.md)\.  | April 21, 2017 | 
| Update | Added information about setting up email for your domain\. See [\(Optional\) Configure email for your domain](setup-email.md)\.  | April 6, 2017 | 
| Update | Added information about checking certificate renewal status in the console\. See [Check a certificate's renewal status](check-certificate-renewal-status.md)\.  | March 28, 2017 | 
| Update | Updated the documentation for using Elastic Load Balancing\. | March 21, 2017 | 
| New content | Added support for AWS Elastic Beanstalk and Amazon API Gateway\. See [Services integrated with AWS Certificate Manager](acm-services.md)\. | March 21, 2017 | 
| Update | Updated the documentation about [Managed renewal](managed-renewal.md)\. | February 20, 2017 | 
|  New content  |  Added documentation about [Import certificates](import-certificate.md)\.  |  October 13, 2016  | 
|  New content  |  Added AWS CloudTrail support for ACM actions\. See [Using CloudTrail with AWS Certificate Manager](cloudtrail.md)\.  |  March 25, 2016  | 
|  New guide  |  This release introduces AWS Certificate Manager\.  |  January 21, 2016  | 