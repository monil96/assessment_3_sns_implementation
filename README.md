# assessment_3_sns_implementation

1. CloudHub Logs:

13:26:30.158     11/17/2019     Deployment     system     SYSTEM
Application queued to be deployed...
13:26:32.515     11/17/2019     Deployment     system     SYSTEM
Deploying application to 1 workers in us-east-2 region(s).
13:26:33.110     11/17/2019     Deployment     system     SYSTEM
Provisioning CloudHub worker in region=us-east-2...
13:26:33.670     11/17/2019     Deployment     system     SYSTEM
Starting CloudHub worker at 13.59.226.82 ...
13:26:49.508     11/17/2019     Deployment     system     SYSTEM
Worker(13.59.226.82): Starting your application on mule=4.2.2...
13:26:52.144     11/17/2019     Worker-0     qtp1491071291-38     INFO
The PersistentQueueManager is NOT configured. The normal VM queue manager will be used.
13:26:59.109     11/17/2019     Worker-0     qtp1491071291-38     INFO
Loaded MuleMessageBuilderFactory implementation 'org.mule.runtime.core.internal.message.DefaultMessageBuilderFactory' from classloader 'org.mule.runtime.module.reboot.internal.MuleContainerSystemClassLoader@4e3a336'
13:26:59.169     11/17/2019     Worker-0     qtp1491071291-38     INFO
Loaded BindingContextBuilderFactory implementation 'org.mule.runtime.core.api.el.DefaultBindingContextBuilderFactory' from classloader 'org.mule.runtime.module.reboot.internal.MuleContainerSystemClassLoader@4e3a336'
13:26:59.673     11/17/2019     Worker-0     qtp1491071291-38     INFO
Using files for tx logs /opt/mule/mule-4.2.2/./.mule/aws-s3-sns-implementation/queue-tx-log/tx1.log and /opt/mule/mule-4.2.2/./.mule/aws-s3-sns-implementation/queue-tx-log/tx2.log
13:26:59.690     11/17/2019     Worker-0     qtp1491071291-38     INFO
Using files for tx logs /opt/mule/mule-4.2.2/./.mule/aws-s3-sns-implementation/queue-xa-tx-log/tx1.log and /opt/mule/mule-4.2.2/./.mule/aws-s3-sns-implementation/queue-xa-tx-log/tx2.log
13:26:59.804     11/17/2019     Worker-0     qtp1491071291-38     INFO
Initialising Bean: org.mule.runtime.module.extension.internal.runtime.config.ConfigurationProviderToolingAdapter-HTTP_Listener_config
13:27:00.241     11/17/2019     Worker-0     qtp1491071291-38     INFO
Initialising Bean: org.mule.runtime.module.extension.internal.runtime.config.ConfigurationProviderToolingAdapter-Amazon_SNS_configuration
13:27:00.248     11/17/2019     Worker-0     qtp1491071291-38     INFO
Initialising Bean: org.mule.runtime.module.extension.internal.runtime.config.ConfigurationProviderToolingAdapter-Amazon_S3_Configuration
13:27:00.272     11/17/2019     Worker-0     qtp1491071291-38     INFO
Initialising flow: aws_s3_sns_implementationFlow
13:27:00.339     11/17/2019     Worker-0     qtp1491071291-38     INFO
Initialising Bean: listener
13:27:00.634     11/17/2019     Worker-0     qtp1491071291-38     INFO
Persistent queues is not enabled for batch module as it was not configured in Cloudhub console
13:27:00.650     11/17/2019     Worker-0     qtp1491071291-38     INFO
Starting ResourceManager
13:27:00.650     11/17/2019     Worker-0     qtp1491071291-38     INFO
Started ResourceManager
13:27:00.656     11/17/2019     Worker-0     qtp1491071291-38     INFO
Starting Bean: org.mule.runtime.module.extension.internal.runtime.config.ConfigurationProviderToolingAdapter-HTTP_Listener_config
13:27:00.680     11/17/2019     Worker-0     qtp1491071291-38     INFO
Starting Bean: org.mule.runtime.module.extension.internal.runtime.config.ConfigurationProviderToolingAdapter-Amazon_SNS_configuration
13:27:01.266     11/17/2019     Worker-0     qtp1491071291-38     INFO
Starting Bean: org.mule.runtime.module.extension.internal.runtime.config.ConfigurationProviderToolingAdapter-Amazon_S3_Configuration
13:27:01.869     11/17/2019     Worker-0     qtp1491071291-38     INFO
Starting flow: aws_s3_sns_implementationFlow
13:27:02.132     11/17/2019     Worker-0     qtp1491071291-38     INFO
Starting Bean: listener
13:27:02.145     11/17/2019     Worker-0     qtp1491071291-38     INFO

**********************************************************************
* Application: aws-s3-sns-implementation                             *
* OS encoding: UTF-8, Mule encoding: UTF-8                           *
*                                                                    *
**********************************************************************
13:27:02.308     11/17/2019     Deployment     system     SYSTEM
Worker(13.59.226.82): Your application has started successfully.
13:27:03.265     11/17/2019     Deployment     system     SYSTEM
Your application is started.
13:31:54.036     11/17/2019     Worker-0     [MuleRuntime].io.01: [aws-s3-sns-implementation].aws_s3_sns_implementationFlow.BLOCKING @6e910931     INFO
event:804c4430-0910-11ea-8b7e-0a58ad5bfff2 Sample data file being read from AWS




2. Bucket Name:  apisero-assessment-monil
3. Topic Name: monil-porwal-mule-notifier
4. Sample file name: sample_aws.txt
