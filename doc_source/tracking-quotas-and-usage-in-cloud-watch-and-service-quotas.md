# Tracking quotas and usage in CloudWatch and Service Quotas<a name="tracking-quotas-and-usage-in-cloud-watch-and-service-quotas"></a>

You can monitor Amazon Cognito user pools using Amazon CloudWatch or using Service Quotas\. CloudWatch collects raw data and processes it into readable, near\-real\-time metrics\. In CloudWatch, you can set alarms that watch for certain thresholds and send notifications or take actions when those thresholds are met\. To create a CloudWatch alarm for a service quota, see [Create a CloudWatch alarm](https://docs.aws.amazon.com/cognito/latest/developerguide/limits.html#create-a-cloud-watch-alarm)\. Amazon Cognito metrics are available at five minute intervals\. For more information about retention periods in CloudWatch, visit the [Amazon CloudWatch FAQ page\.](http://aws.amazon.com/cloudwatch/faqs) 

 You can use Service Quotas to view and manage your Amazon Cognito user pools quota usage\. The Service Quotas console has three features, view service quotas, request a service quota increase, and view current utilization\. You can use the first feature to view quotas and see whether the quota is adjustable\. You can use the second feature to request a Service Quotas increase\. You can use the last feature to view quota utilization\. This feature is only available after your account has been active for awhile\. For more information on viewing quotas in the Service Quotas console, see [Viewing Service Quotas](https://docs.aws.amazon.com/servicequotas/latest/userguide/gs-request-quota.html)\. 

**Note**  
Amazon Cognito metrics are available at 5 minute intervals\. For more information about retention periods in CloudWatch, visit the [Amazon CloudWatch FAQ page](http://aws.amazon.com/cloudwatch/faqs/)\.

**Topics**
+ [Metrics for Amazon Cognito user pools](metrics-for-cognito-user-pools.md)
+ [Dimensions for Amazon Cognito user pools](dimensions-for-cognito-user-pools.md)
+ [Use the Service Quotas console to track metrics](use-the-service-quota-console-to-track-metrics.md)
+ [Use the CloudWatch console to track metrics](use-the-cloud-watch-console-to-track-metrics.md)
+ [Create a CloudWatch alarm for a quota](create-a-cloud-watch-alarm.md)