AWS certified sysops administrator associate
============================================

Topics
1. Cloudwatch - Montior the resource
cloudwatch and ec2
host level metric consists of
CPU
Network
Disk I/O
Status check

Cloudwatch alarms

Metrics granularity
 1 minute for detaild monitoring
 5 minute for statndarad monitoring

RAM untilization can't be done via host level metircs
can be done via custom metrics

EBS - Different volumes
IOPS - Input output per second
4 Different types of EBS storage
 1. General purpose(SSD)(Solid state drive)-gp2 - Recommended for most workloads - till 3,000IOPS is better
 2. Provisional IOPS(SSD)-io1 - Critical business applications that requires sustained IOPS performance
    or more than 10,000 IOPS or 160MiB/s of throughput per volume - Above 10,000IOPS
 3. Throughput Optimized(HDD)-st1 - Streaming workload requiring consistent,fast throughput at low price
    low price, Cannot be boot volume
 4. Cold(HDD)(Hard disk  drives)-sc1 - Throughput oriented storage for large volumes of data that id infrequently accessed.
    low price, Cannot be boot volume

Pre-warming EBS volume
----------------------

EBS Cloud watch metrics
VolumeReadOps
VolumeWriteOps
VolumeQueuelength

Monitoring ELB(Elastic load balancer)
ELB types
1. Application load balancer
2. Network load balancer
3. Classic load balancer

Cloud watch vs cloud trails
Cloudwatch monitors performance - Number of request, cpu utilization
Cloudtrail watched API calls in the AWS platform - Auditing

ElasticCache
Monitoring our cache enines 4 important things
 1. CPU utilization
 2. swap usage
 3. Evictions
 4. Conccurent connections

Two type of cache
 1. Memcached- Scale up and scale out, increase nodes if memcached reaches 90% cpu
 2. Redis - Scale out % of cache/number of core


Cloudwatch dashboards are multi-region/ internationl and display widget any region.

AWS Oragnization
 1. Centrally Manage policies across multiple accounts
 2. Control access to AWS Services
 3. Automate AWS account creation and management
 4. Consolidate billing across multiple AWS accounts

AWS Resource Groups
 1. Classic resource groups
 2. AWS System Manager

Awd Resource Groups and Tagging
EC2 Pricing moels
AWS Config 101

AWS Config
AWS Config provides an inventory of your AWS resources and a history of configuration changes to these resources.
You can use AWS Config to define rules that evaluate these configurations for compliance.

Key for exam
What your environment looks like two weeks ago what serivce to use - AWS Config
EC2 Trail
cloud watch


Health Dashboard
Serivce Health dashboard
Personal Health dashboard



https://aws.amazon.com/ec2/faqs/
https://aws.amazon.com/s3/faqs/
https://aws.amazon.com/vpc/faqs/
https://aws.amazon.com/route53/faqs/
https://aws.amazon.com/rds/faqs/
https://aws.amazon.com/sqs/faqs/


https://aws.amazon.com/certification/certification-prep/
https://www.aws.training/certification?src=exam-prep
