# Disable Codepipeline auto trigger cloudwatch events for production
Via console 
`CloudWatch > Rules > disable`

Via CLI
`https://serverfault.com/questions/869484/temporarily-disable-aws-codepipeline`

No option to disable Bitbucket (codestar) webhooks connections.

# AWS CLI Service already exists
`aws servicediscovery list-services`
`aws servicediscovery delete-service --id "xxx"`

# cloudwatch metrics
https://docs.aws.amazon.com/AmazonCloudWatch/latest/monitoring/aws-services-cloudwatch-metrics.html

# cloudwatch concepts
https://docs.aws.amazon.com/AmazonCloudWatch/latest/monitoring/cloudwatch_concepts.html

# To configure an Amazon SNS topic to use as a target for AWS CodeStar Notifications notification rules
https://docs.aws.amazon.com/codestar-notifications/latest/userguide/set-up-sns.html

