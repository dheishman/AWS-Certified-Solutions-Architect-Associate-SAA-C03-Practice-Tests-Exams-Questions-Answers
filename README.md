### AWS SAA yea boi

### Question 1: Which set of Amazon S3 features helps to prevent and recover from accidental data loss?
1. Object lifecycle and service access logging.
2. Object versioning and Multi-factor authentication.
3. Access controls and server-side encryption.
4. Website hosting and Amazon S3 policies.
<details>
	<summary>Answer</summary>

	2. Object versioning and Multi-factor authentication.
</details>

### Question 2: What is the minimum time Interval for the data that Amazon CloudWatch receives and aggregates?
1. One second.
2. Five seconds.
3. One minute.
4. Three minutes.
5. Five minutes.
<details>
	<summary>Answer</summary>

	3. One minute.

</details>

### Question 3: A user has launched an EC2 instance. The instance got terminated as soon as it was launched. Which of the below mentioned options is not a possible reason for this?
1. The user account has reached the maximum volume limit.
2. The AMI is missing. It is the required part.
3. The snapshot is corrupt.
4. The user account has reached the maximum EC2 instance limit.
<details>
	<summary>Answer</summary>

	4. The user account has reached the maximum EC2 instance limit.

</details>

### Question 4: Your website is serving on-demand training videos to your workforce. Videos are uploaded monthly in high resolution MP4 format. Your workforce is distributed globally often on the move and using company-provided tablets that require the HTTP Live Streaming (HLS) protocol to watch a video. Your company has no video transcoding expertise and it required you may need to pay for a consultant. How do you implement the most cost-efficient architecture without compromising high availability and quality of video delivery'?
1. A video transcoding pipeline running on EC2 using SQS to distribute tasks and Auto Scaling to adjust the number of nodes depending on the length of the queue. EBS volumes to host videos and EBS snapshots to incrementally backup original files after a few days. CloudFront to serve HLS transcoded videos from EC2.
2. Elastic Transcoder to transcode original high-resolution MP4 videos to HL.
3. EBS volumes to host videos and EBS snapshots to incrementally backup original files after a few days. CloudFront to serve HLS transcoded videos from EC2.
4. Elastic Transcoder to transcode original high-resolution MP4 videos to HL.
5. Amazon S3 to host videos with Lifecycle Management to archive original files to Glacier after a few days. CloudFront to serve HLStranscoded videos from S3.
6. A video transcoding pipeline running on EC2 using SQS to distribute tasks and Auto Scaling to adjust the number of nodes depending on the length of the queue. S3 to host videos with Lifecycle Management to archive all files to Glacier after a few days. CloudFront to serve HLS transcoded videos from Glacier.
<details>
	<summary>Answer</summary>

	5. Amazon S3 to host videos with Lifecycle Management to archive original files to Glacier after a few days. CloudFront to serve HLStranscoded videos from S3.

</details>

### Question 5: You are designing an intrusion detection prevention (IDS/IPS) solution for a customer web application in a single VPC. You are considering the options for implementing IOS IPS protection for traffic coming from the Internet. Which of the following options would you consider? (Choose 2 answers)
1. Implement IDS/IPS agents on each Instance running in VPC.
2. Configure an instance in each subnet to switch its network interface card to promiscuous mode and analyze network traffic.
3. Implement Elastic Load Balancing with SSL listeners in front of the web applications.
4. Implement a reverse proxy layer in front of web servers and configure IDS/ IPS agents on each reverse proxy server.
<details>
	<summary>Answer</summary>

	1. Implement IDS/IPS agents on each Instance running in VPC.
	4. Implement a reverse proxy layer in front of web servers and configure IDS/ IPS agents on each reverse proxy server.

</details>

### Question 6: Which of the following are valid statements about Amazon S3? (Choose 2 answers)
1. Amazon S3 provides read-after-write consistency for any type of PUT or DELETE.
2. Consistency is not guaranteed for any type of PUT or DELETE.
3. A successful response to a PUT request only occurs when a complete object is saved.
4. Partially saved objects are immediately readable with a GET after an overwrite PU.
5. S3 provides eventual consistency for overwrite PUTS and DELETE.
<details>
	<summary>Answer</summary>

	3. A successful response to a PUT request only occurs when a complete object is saved.
	5. S3 provides eventual consistency for overwrite PUTS and DELETE.

</details>

### Question 7: How can the domain's zone apex, for example, 'myzoneapexdomain.com', be pointed towards an Elastic Load Balancer?
1. By using an Amazon Route 53 Alias record.
2. By using an AAAA record.
3. By using an Amazon Route 53 CNAME record.
4. By using an A record.
<details>
	<summary>Answer</summary>

	1. By using an Amazon Route 53 Alias record.

</details>

### Question 8: When should I choose Provisioned IOPS over Standard RDS storage?
1. If you have batch-oriented workloads.
2. If you use production online transaction processing (OLTP) workloads.
3. If you have workloads that are not sensitive to consistent performance.
<details>
	<summary>Answer</summary>

	1. If you have batch-oriented workloads.

</details>

### Question 9: Your department creates regular analytics reports from your company's log files All log data is collected in Amazon S3 and processed by daily Amazon Elastic MapReduce (EMR) jobs that generate daily PDF reports and aggregated tables in CSV format for an Amazon Redshift data warehouse. Which of the following alternatives will lower costs without compromising average performance of the system or data integrity for the raw data?
1. Use reduced redundancy storage (RRS) for all data in S3. Use a combination of Spot Instances and Reserved Instances for Amazon EMR jobs. Use Reserved Instances for Amazon Redshift.
2. Use reduced redundancy storage (RRS) for PDF and .csv data in S3. Add Spot Instances to EMR jobs. Use Spot Instances for Amazon Redshift.
3. Use reduced redundancy storage (RRS) for PDF and .csv data in Amazon S3. Add Spot Instances to Amazon EMR jobs. Use Reserved Instances for Amazon Redshift.
4. Use reduced redundancy storage (RRS) for all data in Amazon S3. Add Spot Instances to Amazon EMR jobs. Use Reserved Instances for Amazon Redshift.
<details>
	<summary>Answer</summary>

	3. Use reduced redundancy storage (RRS) for PDF and .csv data in Amazon S3. Add Spot Instances to Amazon EMR jobs. Use Reserved Instances for Amazon Redshift.

</details>

### Question 10: Because of the extensibility limitations of striped storage attached to Windows Server, Amazon RDS does not currently support increasing storage on a [...] DB Instance.
1. SQL Server.
2. MySQL.
3. Oracle.
<details>
	<summary>Answer</summary>

	1. SQL Server.

</details>

### Question 11: In regards to IAM you can edit user properties later, but you cannot use the console to change the [...].
1. user name.
2. password.
3. default group.
<details>
	<summary>Answer</summary>

	1. user name.

</details>

### Question 12: In Amazon EC2 Container Service, are other container types supported?
1. Yes, EC2 Container Service supports any container service you need.
2. Yes, EC2 Container Service also supports Microsoft container service.
3. No, Docker is the only container platform supported by EC2 Container Service presently.
4. Yes, EC2 Container Service supports Microsoft container service and Openstack.
<details>
	<summary>Answer</summary>

	3. No, Docker is the only container platform supported by EC2 Container Service presently.

</details>

### Question 13: Content and Media Server is the latest requirement that you need to meet for a client. The client has been very specific about his requirements such as low latency, high availability, durability, and access control. Potentially there will be millions of views on this server and because of 'spiky' usage patterns, operations teams will need to provision static hardware, network, and management resources to support the maximum expected need. The Customer base will be initially low but is expected to grow and become more geographically distributed. Which of the following would be a good solution for content distribution?
1. Amazon S3 as both the origin server and for caching.
2. AWS Storage Gateway as the origin server and Amazon EC2 for caching.
3. AWS CloudFront as both the origin server and for caching.
4. Amazon S3 as the origin server and Amazon CloudFront for caching.
<details>
	<summary>Answer</summary>

	4. Amazon S3 as the origin server and Amazon CloudFront for caching.

</details>

### Question 14: Name the disk storage supported by Amazon Elastic Compute Cloud (EC2)
1. None of these.
2. Amazon AppStream store.
3. Amazon SNS store.
4. Amazon Instance Store.
<details>
	<summary>Answer</summary>

	4. Amazon Instance Store.

</details>

### Question 15: After an Amazon VPC instance is launched, can I change the VPC security groups it belongs to?
1. Only if the tag 'VPC_Change_Group' is true.
2. Yes. You can.
3. No. You cannot.
4. Only if the tag 'VPC Change Group' is true.
<details>
	<summary>Answer</summary>

	2. Yes. You can.

</details>

### Question 16: If I want an instance to have a public IP address, which IP address should I use?
1. Elastic IP Address.
2. Class B IP Address.
3. Class A IP Address.
4. Dynamic IP Address.
<details>
	<summary>Answer</summary>

	1. Elastic IP Address.

</details>

### Question 17: Amazon RDS supports SOAP only through [...].
1. HTTP or HTTPS.
2. TCP/IP.
3. HTTP.
4. HTTPS.
<details>
	<summary>Answer</summary>

	4. HTTPS.

</details>

### Question 18: Which of the following services natively encrypts data at rest within an AWS region? (Choose 2 answers)
1. AWS Storage Gateway.
2. Amazon DynamoDB.
3. Amazon CloudFront.
4. Amazon Glacier.
5. Amazon Simple Queue Service.
<details>
	<summary>Answer</summary>

	1. AWS Storage Gateway.
	4. Amazon Glacier.

</details>

### Question 19: Which one of the following can't be used as an origin server with Amazon CloudFront?
1. A web server running in your infrastructure.
2. Amazon S3.
3. Amazon Glacier.
4. A web server running on Amazon EC2 instances.
<details>
	<summary>Answer</summary>

	3. Amazon Glacier.

</details>

### Question 20: Select the most correct The device name /dev/sdal (within Amazon EC2) is [...].
1. possible for EBS volumes.
2. reserved for the root device.
3. recommended for EBS volumes.
4. recommended for instance store volumes.
<details>
	<summary>Answer</summary>

	2. reserved for the root device.

</details>

### Question 21: How can I change the security group membership for interfaces owned by other AWS, such as Elastic Load Balancing?
1. By using the service specific console or APICLI commands.
2. None of these.
3. Using Amazon EC2 API/CLI.
4. Using all these methods.
<details>
	<summary>Answer</summary>

	1. By using the service specific console or APICLI commands.

</details>

### Question 22: You have created a Route 53 latency record set from your domain to a machine in Northern Virginia and a similar record to a machine in Sydney. When a user located in US visits your domain he will be routed to
1. Northern Virginia.
2. Sydney.
3. Both, Northern Virginia and Sydney.
4. Depends on the Weighted Resource Record Sets.
<details>
	<summary>Answer</summary>

	1. Northern Virginia.

</details>

### Question 23: In the context of MySQL, version numbers are organized as MySQL version = X.Y.Z. What does X denote here?
1. Release level.
2. Minor version.
3. Version number.
4. Major version.
<details>
	<summary>Answer</summary>

	4. Major version.

</details>

### Question 24: Which one of the below doesn't affect Amazon CloudFront billing?
1. Distribution Type.
2. Data Transfer Out.
3. Dedicated IP SSL Certificates.
4. Requests.
<details>
	<summary>Answer</summary>

	1. Distribution Type.

</details>

### Question 25: Just when you thought you knew every possible storage option on AWS you hear someone mention Reduced Redundancy Storage (RRS) within Amazon S3. What is the ideal scenario to use Reduced Redundancy Storage (RRS)?
1. Huge volumes of data.
2. Sensitive data.
3. Non-critical or reproducible data.
4. Critical data.
<details>
	<summary>Answer</summary>

	3. Non-critical or reproducible data.

</details>

### Question 26: $ aws sqs receive-message –queue-url <https://queue.amazonaws.com/546419318123/Test>
1. 3.
2. 4.
3. 2.
4. 1.
<details>
	<summary>Answer</summary>

	1. 3.

</details>

### Question 27: When running my DB Instance as a Multi-AZ deployment, can I use the standby for read or write operations?
1. Yes.
2. Only with MSSQL based RDS.
3. Only for Oracle RDS instances.
4. No.
<details>
	<summary>Answer</summary>

	4. No.

</details>

### Question 28: In the Launch Db Instance Wizard, where can I select the backup and maintenance options?
1. Under DB INSTANCE DETAILS.
2. Under REVI EW.
3. Under MANAGEMENT OPTIONS.
4. Under ENGINE SELECTION.
<details>
	<summary>Answer</summary>

	3. Under MANAGEMENT OPTIONS.

</details>

### Question 29: What is the network performance offered by the c4.8xlarge instance in Amazon EC2?
1. 20 Gigabit.
2. 10 Gigabit.
3. Very High but variable.
4. 5 Gigabit.
<details>
	<summary>Answer</summary>

	2. 10 Gigabit.

</details>

### Question 30: In Amazon EC2, if your EBS volume stays in the detaching state, you can force the detachment by clicking [...].
1. Force Detach.
2. Detach Instance.
3. AttachVolume.
4. AttachInstance.
<details>
	<summary>Answer</summary>

	1. Force Detach.

</details>

### Question 31: What does Amazon DynamoDB provide?
1. A predictable and scalable MySQL database.
2. A fast and reliable PL/SQL database cluster.
3. A standalone Cassandra database, managed by Amazon Web Services.
4. A fast, highly scalable managed NoSQL database service.
<details>
	<summary>Answer</summary>

	4. A fast, highly scalable managed NoSQL database service.

</details>

### Question 32: Security groups act like a firewall at the instance level, whereas [...] are an additional layer of security that act at the subnet level.
1. DB Security Groups.
2. VPC Security Groups.
3. network ACLs.
<details>
	<summary>Answer</summary>

	3. network ACLs.

</details>

### Question 33: You have been asked to tighten up the password policies in your organization after a serious security breach, so you need to consider every possible security measure. Which of the following is not an account password policy for IAM Users that can be set?
1. Force IAM users to contact an account administrator when the user has allowed his or her password to expire.
2. A minimum password length.
3. Force IAM users to contact an account administrator when the user has entered his password incorrectly.
4. Prevent IAM users from reusing previous passwords.
<details>
	<summary>Answer</summary>

	3. Force IAM users to contact an account administrator when the user has entered his password incorrectly.

</details>

### Question 34: Multi-AZ deployment [...] supported for Microsoft SQL Server DB Instances.
1. is not currently.
2. is as of 2013.
3. is planned to be in 2014.
4. will never be.
<details>
	<summary>Answer</summary>

	1. is not currently.

</details>

### Question 35: What does Amazon Elastic Beanstalk provide?
1. A scalable storage appliance on top of Amazon Web Services.
2. An application container on top of Amazon Web Services.
3. A service by this name doesn't exist.
4. A scalable cluster of EC2 instances.
<details>
	<summary>Answer</summary>

	2. An application container on top of Amazon Web Services.

</details>

### Question 36: You need to quickly set up an email-sending service because a client needs to start using it in the next hour. Amazon Simple Email Service (Amazon SES) seems to be the logical choice but there are several options available to set it up. Which of the following options to set up SES would best meet the needs of the client?
1. Amazon SES console.
2. AWS CloudFormation.
3. SMTP Interface.
4. AWS Elastic Beanstalk.
<details>
	<summary>Answer</summary>

	1. Amazon SES console.

</details>

### Question 37: A user is observing the EC2 CPU utilization metric on CloudWatch. The user has observed some interesting patterns while filtering over the 1 week period for a particular hour. The user wants to zoom that data point to a more granular period. How can the user do that easily with CloudWatch?
1. The user can zoom a particular period by selecting that period with the mouse and then releasing the mouse.
2. The user can zoom a particular period by specifying the aggregation data for that period.
3. The user can zoom a particular period by double clicking on that period with the mouse.
4. The user can zoom a particular period by specifying the period in the Time Range.
<details>
	<summary>Answer</summary>

	1. The user can zoom a particular period by selecting that period with the mouse and then releasing the mouse.

</details>

### Question 38: A company is running a batch analysis every hour on their main transactional DB. running on an RDS MySQL instance to populate their central Data Warehouse running on Redshift During the execution of the batch their transactional applications are very slow When the batch completes they need to update the top management dashboard with the new data The dashboard is produced by another system running on-premises that is currently started when a manually-sent email notifies that an update is required The on-premises system cannot be modified because is managed by another team. How would you optimize this scenario to solve performance issues and automate the process as much as possible? How would you optimize this scenario to solve performance issues and automate the process as much as possible?
1. Replace RDS with Redshift for the batch analysis and SNS to notify the on-premises system to update the dashboard.
2. Replace ROS with Redshift for the oaten analysis and SQS to send a message to the on-premises system to update the dashboard.
3. Create an RDS Read Replica for the batch analysis and SNS to notify me on-premises system to update the dashboard.
4. Create an RDS Read Replica for the batch analysis and SQS to send a message to the on-premises system to update the dashboard.
<details>
	<summary>Answer</summary>

	1. Replace RDS with Redshift for the batch analysis and SNS to notify the on-premises system to update the dashboard.

</details>

### Question 39: You are configuring a new VPC for one of your clients for a cloud migration project, and only a public VPN will be in place. After you created your VPC, you created a new subnet, a new internet gateway, and attached your internet gateway to your VPC. When you launched your first instance into your VPC, you realized that you aren't able to connect to the instance, even if it is configured with an elastic IP. What should be done to access the instance?
1. A route should be created as 0.0.0.0/0 and your internet gateway as target.
2. Attach another ENI to the instance and connect via new EN.
3. A NAT instance should be created and all traffic should be forwarded to NAT instance.
4. A NACL should be created that allows all outbound traffic.
<details>
	<summary>Answer</summary>

	1. A route should be created as 0.0.0.0/0 and your internet gateway as target.

</details>

### Question 40: You have been asked to build a database warehouse using Amazon Redshift. You know a little about it, including that it is a SQL data warehouse solution, and uses industry standard ODBC and JDBCconnections and PostgreSQL drivers. However you are not sure about what sort of storage it uses for database tables. What sort of storage does Amazon Redshift use for database tables?
1. InnoDB Tables.
2. NDB data storage.
3. Columnar data storage.
4. NDB CLUSTER Storage.
<details>
	<summary>Answer</summary>

	3. Columnar data storage.

</details>

### Question 41: A user has attached 1 EBS volume to a VPC instance. The user wants to achieve the best fault tolerance of data possible. Which of the below mentioned options can help achieve fault tolerance?
1. Attach one more volume with RAID 1 configuration.
2. Attach one more volume with RAID 0 configuration.
3. Connect multiple volumes and stripe them with RAI.
4. Use the EBS volume as a root device.
<details>
	<summary>Answer</summary>

	1. Attach one more volume with RAID 1 configuration.

</details>

### Question 42: Which features can be used to restrict access to data in S3? (Choose 2 answers)
1. Set an S3 ACL on the bucket or the object.
2. Create a CloudFront distribution for the bucket.
3. Set an S3 bucket policy.
4. Enable IAM Identity Federation.
5. Use S3 Virtual l Hosting.
<details>
	<summary>Answer</summary>

	1. Set an S3 ACL on the bucket or the object.
	3. Set an S3 bucket policy.

</details>

### Question 43: You are in the process of creating a Route 53 DNS failover to direct traffic to two EC2 zones. Obviously, if one fails, you would like Route 53 to direct traffic to the other region. Each region has an ELB with some instances being distributed. What is the best way for you to configure the Route 53 health check?
1. Route 53 doesn't support ELB with an internal health check.You need to create your own Route 53 health check of the ELB.
2. Route 53 natively supports ELB with an internal health check. Turn 'Evaluate target health' off and 'Associate with Health Check' on and R53 will use the ELB's internal health check.
3. Route 53 doesn't support ELB with an internal health check. You need to associate your resource record set for the ELB with your own health check.
4. Route 53 natively supports ELB with an internal health check. Turn 'Evaluate target health' on and 'Associate with Health Check' off and R53 will use the ELB's internal health check.
<details>
	<summary>Answer</summary>

	4. Route 53 natively supports ELB with an internal health check. Turn 'Evaluate target health' on and 'Associate with Health Check' off and R53 will use the ELB's internal health check.

</details>

### Question 44: For each DB Instance class, what is the maximum size of associated storage capacity?
1. 5GB.
2. 1TB.
3. 2TB.
4. 500GB.
<details>
	<summary>Answer</summary>

	2. 1TB.

</details>

### Question 45: A user is planning a highly available application deployment with EC2. Which of the below mentioned options will not help to achieve HA?
1. Elastic IP address.
2. PIOPS.
3. AMI.
4. Availability Zones.
<details>
	<summary>Answer</summary>

	2. PIOPS.

</details>

### Question 46: What does specifying the mapping /dev/sdc=none when launching an instance do?
1. Prevents /dev/sdc from creating the instance.
2. Prevents /dev/sdc from deleting the instance.
3. Set the value of /dev/sdc to 'zero'.
4. Prevents /dev/sdc from attaching to the instance.
<details>
	<summary>Answer</summary>

	4. Prevents /dev/sdc from attaching to the instance.

</details>

### Question 47: Which of the following statements is true of tagging an Amazon EC2 resource?
1. You don't need to specify the resource identifier while terminating a resource.
2. You can terminate, stop, or delete a resource based solely on its tags.
3. You can't terminate, stop, or delete a resource based solely on its tags.
4. You don't need to specify the resource identifier while stopping a resource.
<details>
	<summary>Answer</summary>

	3. You can't terminate, stop, or delete a resource based solely on its tags.

</details>

### Question 48: You are deploying an application to collect votes for a very popular television show. Millions of users will submit votes using mobile devices. The votes must be collected into a durable, scalable, and highly available data store for real-time public tabulation. Which service should you use?
1. Amazon DynamoDB.
2. Amazon Redshift.
3. Amazon Kinesis.
4. Amazon Simple Queue Service.
<details>
	<summary>Answer</summary>

	3. Amazon Kinesis.

</details>

### Question 49: Are Reserved Instances available for Multi-AZ Deployments?
1. Only for Cluster Compute instances.
2. Yes for all instance types.
3. Only for M3 instance types.
4. No.
<details>
	<summary>Answer</summary>

	2. Yes for all instance types.

</details>

### Question 50: A [...] for a VPC is a collection of subnets (typically private) that you may want to designate for your backend RDS DB Instances.
1. DB Subnet Set.
2. RDS Subnet Group.
3. DB Subnet Group.
4. DB Subnet Collection.
<details>
	<summary>Answer</summary>

	3. DB Subnet Group.

</details>

### Question 51: An instance is launched into a VPC subnet with the network ACL configured to al low all inbound traffic and deny all outbound traffic. The instance's security group is configured to allow SSH from any IPaddress and deny all outbound traffic. What changes need to be made to allow SSH access to the instance?
1. The out bound security group needs to be modified to allow out bound traffic.
2. The outbound network ACL needs to be modified to allow outbound traffic.
3. Nothing, it can be accessed from any IP address using SS.
4. Both the outbound security group and outbound network ACL need to be modified to allow outbound traffic.
<details>
	<summary>Answer</summary>

	2. The outbound network ACL needs to be modified to allow outbound traffic.

</details>

### Question 52: You can modify the backup retention period; valid values are 0 (for no backup retention) to a maximum of [...] days.
1. 45.
2. 35.
3. 15.
4. 5.
<details>
	<summary>Answer</summary>

	2. 35.

</details>

### Question 53: To serve Web traffic for a popular product your chief financial officer and IT director have purchased 10 ml large heavy utilization Reserved Instances (RIs) evenly spread across two Availability Zones: Route 53 is used to deliver the traffic to an Elastic Load Balancer (ELB). After several months, the product grows even more popular and you need additional capacity As a result, your company purchases two C3.2xlarge medium utilization RIs You register the two c3 2xlarge instances with your ELB and quickly find that the ml large instances are at 100% of capacity and the c3 2xlarge instances have significant capacity that's unused Which option is the most cost effective and uses EC2 capacity most effectively?
1. Use a separate ELB for each instance type and distribute load to ELBs with Route 53 weighted round robin.
2. Configure Autoscaning group and Launch Configuration with ELB to add up to 10 more on-demand ml large instances when triggered by Cloudwatch shut off c3 2xlarge instances.
3. Route traffic to EC2 ml large and c3 2xlarge instances directly using Route 53 latency based routing and health checks shut off ELB.
4. Configure ELB with two c3 2xiarge Instances and use on-demand Autoscaling group for up to two additional c3.2xlarge instances Shut on mi .large instances.
<details>
	<summary>Answer</summary>

	4. Configure ELB with two c3 2xiarge Instances and use on-demand Autoscaling group for up to two additional c3.2xlarge instances Shut on mi .large instances.

</details>

### Question 54: An existing application stores sensitive information on a non-boot Amazon EBS data volume attached to an Amazon Elastic Compute Cloud instance. Which of the following approaches would protect the sensitive data on an Amazon EBS volume?
1. Upload your customer keys to AWS CloudHS.
2. Associate the Amazon EBS volume with AWS CloudHS.
3. Re-mount the Amazon EBS volume.
4. Create and mount a new, encrypted Amazon EBS volume. Move the data to the new volume. Delete the old Amazon EBS volume.
5. Unmount the EBS volume. Toggle the encryption attribute to True. Re-mount the Amazon EBS volume.
6. Snapshot the current Amazon EBS volume. Restore the snapshot to a new, encrypted Amazon EBS volume. Mount the Amazon EBS volume.
<details>
	<summary>Answer</summary>

	4. Create and mount a new, encrypted Amazon EBS volume. Move the data to the new volume. Delete the old Amazon EBS volume.

</details>

### Question 55: A user has launched one EC2 instance in the US West region. The user wants to access the RDS instance launched in the US East region from that EC2 instance. How can the user configure the access for that EC2 instance?
1. Configure the IP range of the US West region instance as the ingress security rule of RDS.
2. It is not possible to access RDS of the US East region from the US West region.
3. Open the security group of the US West region in the RDS security group's ingress rule.
4. Create an IAM role which has access to RDS and launch an instance in the US West region with it.
<details>
	<summary>Answer</summary>

	1. Configure the IP range of the US West region instance as the ingress security rule of RDS.

</details>

### Question 56: You have been asked to build AWS infrastructure for disaster recovery for your local applications and within that you should use an AWS Storage Gateway as part of the solution. Which of the following best describes the function of an AWS Storage Gateway?
1. Accelerates transferring large amounts of data between the AWS cloud and portable storage devices .
2. A web service that speeds up distribution of your static and dynamic web content.
3. Connects an on-premises software appliance with cloud-based storage to provide seamless and secure integration between your on-premises IT environment and AWS's storage infrastructure.
4. Is a storage service optimized for infrequently used data, or 'cold data'.
<details>
	<summary>Answer</summary>

	3. Connects an on-premises software appliance with cloud-based storage to provide seamless and secure integration between your on-premises IT environment and AWS's storage infrastructure.

</details>

### Question 57: While creating an Amazon RDS DB, your first task is to set up a DB [...] that controls which IP address or EC2 instance can access your DB Instance.
1. security token pool.
2. security token.
3. security pool.
4. security group.
<details>
	<summary>Answer</summary>

	4. security group.

</details>

### Question 58: You need to import several hundred megabytes of data from a local Oracle database to an Amazon RDS DB instance. What does AWS recommend you use to accomplish this?
1. Oracle export/import utilities.
2. Oracle SQL Developer.
3. Oracle Data Pump.
4. DBMS_FILE_TRANSFER.
<details>
	<summary>Answer</summary>

	3. Oracle Data Pump.

</details>

### Question 59: In the context of AWS support, why must an EC2 instance be unreachable for 20 minutes rather than allowing customers to open tickets immediately?
1. Because most reachability issues are resolved by automated processes in less than 20 minutes.
2. Because all EC2 instances are unreachable for 20 minutes every day when AWS does routine maintenance.
3. Because all EC2 instances are unreachable for 20 minutes when first launched.
4. Because of all the reasons listed here.
<details>
	<summary>Answer</summary>

	1. Because most reachability issues are resolved by automated processes in less than 20 minutes.

</details>

### Question 60: HTTP Query-based requests are HTTP requests that use the HTTP verb GET or POST and a Query parameter named [...].
1. Action.
2. Value.
3. Reset.
4. Retrieve.
<details>
	<summary>Answer</summary>

	1. Action.

</details>

### Question 61: A friend tells you he is being charged $100 a month to host his WordPress website, and you tell him you can move it to AWS for him and he will only pay a fraction of that, which makes him very happy. He then tells you he is being charged $50 a month for the domain, which is registered with the same people that set it up, and he asks if it's possible to move that to AWS as well. You tell him you aren't sure, but will look into it. Which of the following statements is true in regards to transferring domain names to AWS?
1. You can't transfer existing domains to AW.
2. You can transfer existing domains into Amazon Route 53's management.
3. You can transfer existing domains via AWS Direct Connect.
4. You can transfer existing domains via AWS Import/Export.
<details>
	<summary>Answer</summary>

	2. You can transfer existing domains into Amazon Route 53's management.

</details>

### Question 62: While creating the snapshots using the command line tools, which command should I be using?
1. ec2-deploy-snapshot.
2. ec2-fresh-snapshot.
3. ec2-create-snapshot.
4. ec2-new-snapshot.
<details>
	<summary>Answer</summary>

	3. ec2-create-snapshot.

</details>

### Question 63: All Amazon EC2 instances are assigned two IP addresses at launch, out of which one can only be reached from within the Amazon EC2 network?
1. Multiple IP address.
2. Public IP address.
3. Private IP address.
4. Elastic IP Address.
<details>
	<summary>Answer</summary>

	3. Private IP address.

</details>

### Question 64: When an EC2 instance that is backed by an S3-based AMI is terminated, what happens to the data on the root volume?
1. Data is automatically saved as an EBS snapshot.
2. Data is automatically saved as an EBS volume.
3. Data is unavailable until the instance is restarted.
4. Data is automatically deleted.
<details>
	<summary>Answer</summary>

	4. Data is automatically deleted.

</details>

### Question 65: You've created your first load balancer and have registered your EC2 instances with the load balancer. Elastic Load Balancing routinely performs health checks on all the registered EC2 instances and automatically distributes all incoming requests to the DNS name of your load balancer across your registered, healthy EC2 instances. By default, the load balancer uses the [...] protocol for checking the health of your instances.
1. HTTPS.
2. HTTP.
3. ICMP.
4. IPv6.
<details>
	<summary>Answer</summary>

	2. HTTP.

</details>

### Question 66: Amazon Elastic Load Balancing is used to manage traffic on a fleet of Amazon EC2 instances, distributing traffic to instances across all Availability Zones within a region. Elastic Load Balancing has all the advantages of an on-premises load balancer, plus several security benefits. Which of the following is not an advantage of ELB over an on-premise load balancer?
1. ELB uses a four-tier, key-based architecture for encryption.
2. ELB offers clients a single point of contact, and can also serve as the first line of defense against attacks on your network.
3. ELB takes over the encryption and decryption work from the Amazon EC2 instances and manages it centrally on the load balancer.
4. ELB supports end-to-end traffic encryption using TLS (previously SSL) on those networks that use secure HTTP (HTTPS) connections.
<details>
	<summary>Answer</summary>

	1. ELB uses a four-tier, key-based architecture for encryption.

</details>

### Question 67: A web company is looking to implement an external payment service into their highly available application deployed in a VPC Their application EC2 instances are behind a public lacing ELB Auto scaling is used to add additional instances as traffic increases under normal load the application runs 2 instances in the Auto Scaling group but at peak it can scale 3x in size. The application instances need to communicate with the payment service over the Internet which requires whitelisting of all public IP addresses used to communicate with it. A maximum of 4 whitelisting IP addresses are allowed at a time and can be added through an API. How should they architect their solution?
1. Route payment requests through two NAT instances setup for High Availability and whitelist the Elastic IP addresses attached to the MAT instances.
2. Whitelist the VPC Internet Gateway Public IP and route payment requests through the Internet Gateway.
3. Whitelist the ELB IP addresses and route payment requests from the Application servers through the EL.
4. Automatically assign public IP addresses to the application instances in the Auto Scaling group and run a script on boot that adds each instances public IP address to the payment validation whitelist AP.
<details>
	<summary>Answer</summary>

	4. Automatically assign public IP addresses to the application instances in the Auto Scaling group and run a script on boot that adds each instances public IP address to the payment validation whitelist AP.

</details>

### Question 68: You are using Amazon SES as an email solution but are unsure of what its limitations are. Which statement below is correct in regards to that?
1. New Amazon SES users who have received production access can send up to 1,000 emails per 24-hour period, at a maximum rate of 10 emails per second.
2. Every Amazon SES sender has a the same set of sending limits.
3. Sending limits are based on messages rather than on recipients.
4. Every Amazon SES sender has a unique set of sending limits.
<details>
	<summary>Answer</summary>

	4. Every Amazon SES sender has a unique set of sending limits.

</details>

### Question 69: Your company is getting ready to do a major public announcement of a social media site on AWS. The website is running on EC2 instances deployed across multiple Availability Zones with a Multi-AZ RDS MySQL Extra Large DB Instance. The site performs a high number of small reads and writes per second and relies on an eventual consistency model. After comprehensive tests you discover that there is read contention on RDS MySQL. Which are the best approaches to meet these requirements? (Choose 2 answers)
1. Deploy ElasticCache in-memory cache running in each Availability Zone.
2. Implement sharding to distribute load to multiple RDS MySQL instances.
3. Increase the RDS MySQL Instance size and Implement provisioned IOPS.
4. Add an RDS MySQL read replica in each Availability Zone.
<details>
	<summary>Answer</summary>

	1. Deploy ElasticCache in-memory cache running in each Availability Zone.
	4. Add an RDS MySQL read replica in each Availability Zone.

</details>

### Question 70: What does a 'Domain' refer to in Amazon SWF?
1. A security group in which only tasks inside can communicate with each other.
2. A special type of worker.
3. A collection of related Workflows.
4. The DNS record for the Amazon SWF service.
<details>
	<summary>Answer</summary>

	3. A collection of related Workflows.

</details>

### Question 71: The SQL Server [...] feature is an efficient means of copying data from a source database to your DB Instance. It writes the data that you specify to a data file, such as an ASCII file.
1. bulk copy.
2. group copy.
3. dual copy.
4. mass copy.
<details>
	<summary>Answer</summary>

	1. bulk copy.

</details>

### Question 72: Any person or application that interacts with AWS requires security credentials. AWS uses these credentials to identify who is making the call and whether to allow the requested access. You have just set up a VPC network for a client and you are now thinking about the best way to secure this network. You set up a security group called vpcsecuritygroup. Which following statement is true in respect to the initial settings that will be applied to this security group if you choose to use the default settings for this group?
1. Allow all inbound traffic and allow no outbound traffic.
2. Allow no inbound traffic and allow all outbound traffic.
3. Allow inbound traffic on port 80 only and allow all outbound traffic.
4. Allow all inbound traffic and allow all outbound traffic.
<details>
	<summary>Answer</summary>

	2. Allow no inbound traffic and allow all outbound traffic.

</details>

### Question 73: Which one of the below is not an AWS Storage Service?
1. Amazon S3.
2. Amazon Glacier.
3. Amazon CloudFront.
4. Amazon EBS.
<details>
	<summary>Answer</summary>

	3. Amazon CloudFront.

</details>

### Question 74: You are trying to launch an EC2 instance, however the instance seems to go into a terminated status immediately. What would probably not be a reason that this is happening?
1. The AMI is missing a required part.
2. The snapshot is corrupt.
3. You need to create storage in EBS first.
4. You've reached your volume limit.
<details>
	<summary>Answer</summary>

	3. You need to create storage in EBS first.

</details>

### Question 75: A company is building software on AWS that requires access to various AWS services. Which configuration should be used to ensure mat AWS credentials (i.e., Access Key ID/Secret Access Key combination) are not compromised?
1. Enable Multi-Factor Authentication for your AWS root account.
2. Assign an IAM role to the Amazon EC2 instance.
3. Store the AWS Access Key ID/Secret Access Key combination in software comments.
4. Assign an IAM user to the Amazon EC2 Instance.
<details>
	<summary>Answer</summary>

	1. Enable Multi-Factor Authentication for your AWS root account.

</details>

### Question 76: Can we attach an EBS volume to more than one EC2 instance at the same time?
1. Yes.
2. No.
3. Only EC2-optimized EBS volumes.
4. Only in read mode.
<details>
	<summary>Answer</summary>

	2. No.

</details>

### Question 77: You need to measure the performance of your EBS volumes as they seem to be under performing. You have come up with a measurement of 1,024 KB I/O but your colleague tells you that EBS volume performance is measured in IOPS. How many IOPS is equal to 1,024 KB I/O?
1. 16.
2. 256.
3. 8.
4. 4.
<details>
	<summary>Answer</summary>

	4. 4.

</details>

### Question 78: Your company produces customer commissioned one-of-a-kind skiing helmets combining nigh fashion with custom technical enhancements Customers can show off their Individuality on the ski slopes and have access to head-up-displays. GPS rear-view cams and any other technical innovation they wish to embed in the helmet. The current manufacturing process is data rich and complex including assessments to ensure that the custom electronics and materials used to assemble the helmets are to the highest standards Assessments are a mixture of human and automated assessments you need to add a new set of assessment to model the failure modes of the custom electronics using GPUs with CUDA, across a cluster of servers with low latency networking. What architecture would allow you to automate the existing process using a hybrid approach and ensure that the architecture can support the evolution of processes over time?
1. Use AWS Data Pipeline to manage movement of data & meta-data and assessments Use an autoscaling group of G2 instances in a placement group.
2. Use Amazon Simple Workflow (SWF) to manages assessments, movement of data & meta-data Use an auto-scaling group of G2 instances in a placement group.
3. Use Amazon Simple Workflow (SWF) to manages assessments movement of data & meta-data Use an auto-scaling group of C3 instances with SR-IOV (Single Root 1/0 Virtualization).
4. Use AWS data Pipeline to manage movement of data & meta-data and assessments use autoscaling group of C3 with SR-IOV (Single Root 1/0 virtualization).
<details>
	<summary>Answer</summary>

	2. Use Amazon Simple Workflow (SWF) to manages assessments, movement of data & meta-data Use an auto-scaling group of G2 instances in a placement group.

</details>

### Question 79: You are designing Internet connectivity for your VPC. The Web servers must be available on the Internet. The application must have a highly available architecture. Which alternatives should you consider? (Choose 2 answers)
1. Configure a NAT instance in your VPC Create a default route via the NAT instance and associate it with all subnets Configure a DNS A record that points to the NAT instance public IP address.
2. Configure a CloudFront distribution and configure the origin to point to the private IP addresses of your Web servers Configure a Route 53 CNAME record to your CloudFront distribution.
3. Place all your web servers behind EL8 Configure a Route 53 CNAME to point to the ELB DNS name.
4. Assign EIPs to all web servers. Configure a Route 53 record set with all EIPs. With health checks and DNS failover.
5. Configure ELB with an EIP Place all your Web servers behind ELB Configure a Route 53 A record that points to the EIP.
<details>
	<summary>Answer</summary>

	3. Place all your web servers behind EL8 Configure a Route 53 CNAME to point to the ELB DNS name.
	4. Assign EIPs to all web servers. Configure a Route 53 record set with all EIPs. With health checks and DNS failover.

</details>

### Question 80: You need to configure an Amazon S3 bucket to serve static assets for your public-facing web application. Which methods ensure that all objects uploaded to the bucket are set to public read? (Choose 2 answers)
1. Set permissions on the object to public read during upload.
2. Configure the bucket ACL to set all objects to public read.
3. Configure the bucket policy to set all objects to public read.
4. Use AWS Identity and Access Management roles to set the bucket to public read.
5. Amazon S3 objects default to public read, so no action is needed.
<details>
	<summary>Answer</summary>

	1. Set permissions on the object to public read during upload.
	3. Configure the bucket policy to set all objects to public read.

</details>

### Question 81: A major customer has asked you to set up his AWS infrastructure so that it will be easy to recover in the case of a disaster of some sort. Which of the following is important when thinking about being able to quickly launch resources in AWS to ensure business continuity in case of a disaster?
1. Create and maintain AMIs of key servers where fast recovery is required.
2. Regularly run your servers, test them, and apply any software updates and configuration changes.
3. All items listed here are important when thinking about disaster recovery.
4. Ensure that you have all supporting custom software packages available in AW.
<details>
	<summary>Answer</summary>

	3. All items listed here are important when thinking about disaster recovery.

</details>

### Question 82: You are developing a new mobile application and are considering storing user preferences in AWS.2w This would provide a more uniform cross-device experience to users using multiple mobile devices to access the application. The preference data for each user is estimated to be SOKB in size Additionally 5 million customers are expected to use the application on a regular basis. The solution needs to be cost-effective, highly available, scalable and secure, how would you design a solution to meet the above requirements?
1. Setup an RDS MySQL instance in 2 Availability Zones to store the user preference data. Deploy a public facing application on a server in front of the database to manage security and access credentials.
2. Setup a DynamoDB table with an item for each user having the necessary attributes to hold the user preferences. The mobile application will query the user preferences directly from the DynamoDB table. Utilize ST.
3. Web Identity Federation, and DynamoDB Fine Grained Access Control to authenticate and authorize access.
4. Setup an RDS MySQL instance with multiple read replicas in 2 Availability Zones to store the user preference data. The mobile application will query the user preferences from the read replicas. Leverage the MySQL user management and access privilege system to manage security and access credentials.
5. Store the user preference data in S3 Setup a DynamoDB table with an item for each user and an item attribute pointing to the user' S3 object. The mobile application will retrieve the S3 URL from DynamoDB and then access the S3 object directly utilize STS, Web identity Federation, and S3 ACLs to authenticate and authorize access.
<details>
	<summary>Answer</summary>

	2. Setup a DynamoDB table with an item for each user having the necessary attributes to hold the user preferences. The mobile application will query the user preferences directly from the DynamoDB table. Utilize ST.

</details>

### Question 83: In the Amazon RDS which uses the SQL Server engine, what is the maximum size for a Microsoft SQL Server DB Instance with SQL Server Express edition?
1. 10GB per DB.
2. 100GB per DB.
3. 2TB per DB.
4. 1TB per DB.
<details>
	<summary>Answer</summary>

	1. 10GB per DB.

</details>

### Question 84: You have deployed a web application targeting a global audience across multiple AWS Regions under the domain name.example.com. You decide to use Route 53 Latency-Based Routing to serve web requests to users from the region closest to the user. To provide business continuity in the event of server downtime you configure weighted record sets associated with two web servers in separate Availability Zones per region. Dunning a DR test you notice that when you disable all web servers in one of the regions Route 53 does not automatically direct all users to the other region. What could be happening? (Choose 2 answers)
1. Latency resource record sets cannot be used in combination with weighted resource record sets.
2. You did not setup an HTTP health check tor one or more of the weighted resource record sets associated with me disabled web servers.
3. The value of the weight associated with the latency alias resource record set in the region with the disabled servers is higher than the weight for the other region.
4. One of the two working web servers in the other region did not pass its HTTP health check.
5. You did not set 'Evaluate Target Health' to 'Yes' on the latency alias resource record set associated with example com in the region where you disabled the servers.
<details>
	<summary>Answer</summary>

	2. You did not setup an HTTP health check tor one or more of the weighted resource record sets associated with me disabled web servers.
	5. You did not set 'Evaluate Target Health' to 'Yes' on the latency alias resource record set associated with example com in the region where you disabled the servers.

</details>

### Question 85: Amazon EBS provides the ability to create backups of any Amazon EC2 volume into what is known as [...].
1. snapshots.
2. images.
3. instance backups.
4. mirrors.
<details>
	<summary>Answer</summary>

	1. snapshots.

</details>

### Question 86: You've been hired to enhance the overall security posture for a very large e-commerce site They have a well architected multi-tier application running in a VPC that uses ELBs in front of both the web and the app tier with static assets served directly from S3 They are using a combination of RDS and DynamoOB for their dynamic data and then archiving nightly into S3 for further processing with EMR They are concerned because they found questionable log entries and suspect someone is attempting to gain unauthorized access. Which approach provides a cost effective scalable mitigation to this kind of attack?
1. Recommend that they lease space at a DirectConnect partner location and establish a lG DirectConnect connection to their vPC they would then establish Internet connectivity into their space, filter the traffic in hardware Web Application Firewall (WAF). And then pass the traffic through the DirectConnect connection into their application running in their VPC,
2. Add previously identified hostile source IPs as an explicit INBOUND DENY NACL to the web tier sub net.
3. Add a WAF tier by creating a new ELB and an AutoScaling group of EC2 Instances running a host based WAF They would redirect Route 53 to resolve to the new WAF tier ELB The WAF tier wouldthier pass the traffic to the current web tier The web tier Security Groups would be updated to only allow traffic from the WAF tier Security Group
4. Remove all but TLS 1 2 from the web tier ELB and enable Advanced Protocol Filtering This will enable the ELB itself to perform WAF functionality.
<details>
	<summary>Answer</summary>

	3. Add a WAF tier by creating a new ELB and an AutoScaling group of EC2 Instances running a host based WAF They would redirect Route 53 to resolve to the new WAF tier ELB The WAF tier wouldthier pass the traffic to the current web tier The web tier Security Groups would be updated to only allow traffic from the WAF tier Security Group

</details>

### Question 87: You are designing the network infrastructure for an application server in Amazon VPC Users will access all the application instances from the Internet as well as from an on-premises network The on-premises network is connected to your VPC over an AWS Direct Connect link. How would you design routing to meet the above requirements?
1. Configure a single routing Table with a default route via the Internet gateway Propagate a default route via BGP on the AWS Direct Connect customer router. Associate the routing table with all VPCsubnets.
2. Configure a single routing table with a default route via the internet gateway Propagate specific routes for the on-premises networks via BGP on the AWS Direct Connect customer router Associatethe routing table with all VPC subnets.
3. Configure a single routing table with two default routes: one to the internet via an Internet gateway the other to the on-premises network via the VPN gateway use this routing table across all subnets in your VPC.
4. Configure two routing tables one that has a default route via the Internet gateway and another that has a default route via the VPN gateway Associate both routing tables with each VPC subnet.
<details>
	<summary>Answer</summary>

	1. Configure a single routing Table with a default route via the Internet gateway Propagate a default route via BGP on the AWS Direct Connect customer router. Associate the routing table with all VPCsubnets.

</details>

### Question 88: You have multiple VPN connections and want to provide secure communication between sites using the AWS VPN CloudHub. Which statement is the most accurate in describing what you must do to set this up correctly?
1. Create a virtual private gateway with multiple customer gateways, each with unique Border Gateway Protocol (BGP) Autonomous System Numbers (ASNs).
2. Create a virtual private gateway with multiple customer gateways, each with a unique set of keys.
3. Create a virtual public gateway with multiple customer gateways, each with a unique Private subnet.
4. Create a virtual private gateway with multiple customer gateways, each with unique subnet id.
<details>
	<summary>Answer</summary>

	1. Create a virtual private gateway with multiple customer gateways, each with unique Border Gateway Protocol (BGP) Autonomous System Numbers (ASNs).

</details>

### Question 89: A user is aware that a huge download is occurring on his instance. He has already set the Auto Scaling policy to increase the instance count when the network I/O increases beyond a certain limit. How can the user ensure that this temporary event does not result in scaling?
1. The network I/O are not affected during data download.
2. The policy cannot be set on the network I/O.
3. There is no way the user can stop scaling as it is already configured.
4. Suspend scaling.
<details>
	<summary>Answer</summary>

	4. Suspend scaling.

</details>

### Question 90: The Amazon EC2 web service can be accessed using the [...] web services messaging protocol. This interface is described by a Web Services Description Language (WSDL) document.
1. SOAP.
2. DCOM.
3. CORBA.
4. XML-RPC.
<details>
	<summary>Answer</summary>

	1. SOAP.

</details>

### Question 91: Which of the following are true regarding encrypted Amazon Elastic Block Store (EBS) volumes? (Choose 2 answers)
1. Supported on all Amazon EBS volume types.
2. Snapshots are automatically encrypted.
3. Available to all instance types.
4. Existing volumes can be encrypted.
5. Shared volumes can be encrypted.
<details>
	<summary>Answer</summary>

	1. Supported on all Amazon EBS volume types.
	2. Snapshots are automatically encrypted.

</details>

### Question 92: Is Federated Storage Engine currently supported by Amazon RDS for MySQL?
1. Only for Oracle RDS instances.
2. Yes.
3. No.
4. Only in VPC.
<details>
	<summary>Answer</summary>

	3. No.

</details>

### Question 93: While creating the snapshots using the API, which Action should I be using?
1. MakeSnapShot.
2. FreshSnapshot.
3. DeploySnapshot.
4. CreateSnapshot.
<details>
	<summary>Answer</summary>

	4. CreateSnapshot.

</details>

### Question 94: A customer needs to capture all client connection information from their load balancer every five minutes. The company wants to use this data for analyzing traffic patterns and troubleshooting their applications. Which of the following options meets the customer requirements?
1. Enable AWS CloudTrail for the load balancer.
2. Enable access logs on the load balancer.
3. Install the Amazon CloudWatch Logs agent on the load balancer.
4. Enable Amazon CloudWatch metrics on the load balancer.
<details>
	<summary>Answer</summary>

	1. Enable AWS CloudTrail for the load balancer.

</details>

### Question 95: Will my standby RDS instance be in the same Region as my primary?
1. Only for Oracle RDS types.
2. Yes.
3. Only if configured at launch.
4. No.
<details>
	<summary>Answer</summary>

	2. Yes.

</details>

### Question 96: If I want my instance to run on a single-tenant hardware, which value do I have to set the instance's tenancy attribute to?
1. Dedicated.
2. Isolated.
3. One.
4. Reserved.
<details>
	<summary>Answer</summary>

	1. Dedicated.

</details>

### Question 97: Can the string value of 'Key' be prefixed with :aws:'?
1. Only in GovCloud.
2. Only for S3 not EC2.
3. Yes.
4. No.
<details>
	<summary>Answer</summary>

	4. No.

</details>

### Question 98: A user wants to increase the durability and availability of the EBS volume. Which of the below mentioned actions should he perform?
1. Take regular snapshots.
2. Create an AM.
3. Create EBS with higher capacity.
4. Access EBS regularly.
<details>
	<summary>Answer</summary>

	1. Take regular snapshots.

</details>

### Question 99: What does Amazon RDS stand for?
1. Regional Data Server.
2. Relational Database Service.
3. Nothing.
4. Regional Database Service.
<details>
	<summary>Answer</summary>

	2. Relational Database Service.

</details>

### Question 100: You have been asked to set up monitoring of your network and you have decided that Cloudwatch would be the best service to use. Amazon CloudWatch monitors your Amazon Web Services (AWS) resources and the applications you run on AWS in real-time. You can use CloudWatch to collect and track metrics, which are the variables you want to measure for your resources and applications. Which of the following items listed can AWS Cloudwatch monitor?
1. Log files your applications generate.
2. All of the items listed on this page.
3. System-wide visibility into resource utilization, application performance, and operational health.
4. Custom metrics generated by your applications and services.
<details>
	<summary>Answer</summary>

	2. All of the items listed on this page.

</details>

### Question 101: What is the maximum write throughput I can provision for a single Dynamic DB table?
1. 1,000 write capacity units.
2. 100,000 write capacity units.
3. Dynamic DB is designed to scale without limits, but if you go beyond 10,000 you have to contact AWS first.
4. 10,000 write capacity units.
<details>
	<summary>Answer</summary>

	3. Dynamic DB is designed to scale without limits, but if you go beyond 10,000 you have to contact AWS first.

</details>

### Question 102: Do Amazon EBS volumes persist independently from the running life of an Amazon EC2 instance?
1. Yes, they do but only if they are detached from the instance.
2. No, you cannot attach EBS volumes to an instance.
3. No, they are dependent.
4. Yes, they do.
<details>
	<summary>Answer</summary>

	4. Yes, they do.

</details>

### Question 103: What is a Security Group?
1. None of these.
2. A list of users that can access Amazon EC2 instances.
3. An Access Control List (ACL) for AWS resources.
4. A firewall for inbound traffic, built-in around every Amazon EC2 instance.
<details>
	<summary>Answer</summary>

	4. A firewall for inbound traffic, built-in around every Amazon EC2 instance.

</details>

### Question 104: You need to set up a high level of security for an Amazon Relational Database Service (RDS) you have just built in order to protect the confidential information stored in it. What are all the possible security groups that RDS uses?
1. DB security groups, VPC security groups, and EC2 security groups.
2. DB security groups only.
3. EC2 security groups only.
4. VPC security groups, and EC2 security groups.
<details>
	<summary>Answer</summary>

	1. DB security groups, VPC security groups, and EC2 security groups.

</details>

### Question 105: In the 'Detailed' monitoring data available for your Amazon EBS volumes, Provisioned IOPS volumes automatically send [...] minute metrics to Amazon CloudWatch.
1. 3.
2. 1.
3. 5.
4. 2.
<details>
	<summary>Answer</summary>

	2. 1.

</details>

### Question 106: You are looking at ways to improve some existing infrastructure as it seems a lot of engineering resources are being taken up with basic management and monitoring tasks and the costs seem to be excessive. You are thinking of deploying Amazon ElasticCache to help. Which of the following statements is true in regards to ElasticCache?
1. You can improve load and response times to user actions and queries however the cost associated with scaling web applications will be more.
2. You can't improve load and response times to user actions and queries but you can reduce the cost associated with scaling web applications.
3. You can improve load and response times to user actions and queries however the cost associated with scaling web applications will remain the same.
4. You can improve load and response times to user actions and queries and also reduce the cost associated with scaling web applications.
<details>
	<summary>Answer</summary>

	4. You can improve load and response times to user actions and queries and also reduce the cost associated with scaling web applications.

</details>

### Question 107: A customer needs corporate IT governance and cost oversight of all AWS resources consumed by its divisions. The divisions want to maintain administrative control of the discrete AWS resources they consume and keep those resources separate from the resources of other divisions. Which of the following options, when used together will support the autonomy/control of divisions while enabling corporate IT to maintain governance and cost oversight? (Choose 2 answers)
1. Use AWS Consolidated Billing and disable AWS root account access for the child accounts.
2. Enable IAM cross-account access for all corporate IT administrators in each child account.
3. Create separate VPCs for each division within the corporate IT AWS account.
4. Use AWS Consolidated Billing to link the divisions' accounts to a parent corporate account.
5. Write all child AWS CloudTrail and Amazon CloudWatch logs to each child account's Amazon S3 'Log' bucket.
<details>
	<summary>Answer</summary>

	4. Use AWS Consolidated Billing to link the divisions' accounts to a parent corporate account.
	5. Write all child AWS CloudTrail and Amazon CloudWatch logs to each child account's Amazon S3 'Log' bucket.

</details>

### Question 108: After creating a new IAM user which of the following must be done before they can successfully make API calls?
1. Add a password to the user.
2. Enable Multi-Factor Authentication for the user.
3. Assign a Password Policy to the user.
4. Create a set of Access Keys for the user.
<details>
	<summary>Answer</summary>

	4. Create a set of Access Keys for the user.

</details>

### Question 109: A friend wants you to set up a small BitTorrent storage area for him on Amazon S3. You tell him it is highly unlikely that AWS would allow such a thing in their infrastructure. However you decide to investigate. Which of the following statements best describes using BitTorrent with Amazon S3?
1. Amazon S3 does not support the BitTorrent protocol because it is used for pirated software.
2. You can use the BitTorrent protocol but only for objects that are less than 100 GB in size.
3. You can use the BitTorrent protocol but you need to ask AWS for specific permissions first.
4. You can use the BitTorrent protocol but only for objects that are less than 5 GB in size.
<details>
	<summary>Answer</summary>

	4. You can use the BitTorrent protocol but only for objects that are less than 5 GB in size.

</details>

### Question 110: IAM's Policy Evaluation Logic always starts with a default [...] for every request, except for those that use the AWS account's root security credentials?
1. Permit.
2. Deny.
3. Cancel.
<details>
	<summary>Answer</summary>

	2. Deny.

</details>

### Question 111: You have been given a scope to deploy some AWS infrastructure for a large organization. The requirements are that you will have a lot of EC2 instances but may need to add more when the average utilization of your Amazon EC2 fleet is high and conversely remove them when CPU utilization is low. Which AWS services would be best to use to accomplish this?
1. Auto Scaling, Amazon CloudWatch and AWS Elastic Beanstalk.
2. Auto Scaling, Amazon CloudWatch and Elastic Load Balancing.
3. Amazon CloudFront, Amazon CloudWatch and Elastic Load Balancing.
4. AWS Elastic Beanstalk, Amazon CloudWatch and Elastic Load Balancing.
<details>
	<summary>Answer</summary>

	2. Auto Scaling, Amazon CloudWatch and Elastic Load Balancing.

</details>

### Question 112: When does the billing of an Amazon EC2 system begin?
1. It starts when the Status column for your distribution changes from Creating to Deployed.
2. It starts as soon as you click the create instance option on the main EC2 console.
3. It starts when your instance reaches 720 instance hours.
4. It starts when Amazon EC2 initiates the boot sequence of an AMI instance.
<details>
	<summary>Answer</summary>

	4. It starts when Amazon EC2 initiates the boot sequence of an AMI instance.

</details>

### Question 113: A user is storing a large number of objects on AWS S3. The user wants to implement the search functionality among the objects. How can the user achieve this?
1. Use the indexing feature of S3.
2. Tag the objects with the metadata to search on that.
3. Use the query functionality of S3.
4. Make your own DB system which stores the S3 metadata for the search functionality.
<details>
	<summary>Answer</summary>

	4. Make your own DB system which stores the S3 metadata for the search functionality.

</details>

### Question 114: A corporate web application is deployed within an Amazon Virtual Private Cloud (VPC) and is connected to the corporate data center via an IPsec VPN. The application must authenticate against the on-premises LDAP server. After authentication, each logged-in user can only access an Amazon Simple Storage Space (S3) keyspace specific to that user. Which two approaches can satisfy these objectives? (Choose 2 answers)
1. Develop an identity broker that authenticates against IAM security Token service to assume a Lam role in order to get temporary AWS security credentials The application calls the identity broker toget AWS temporary security credentials with access to the appropriate S3 bucket.
2. The application authenticates against LDAP and retrieves the name of an IAM role associated with the user. The application then ca lls the IAM Security Token Service to assume that IAM role The application can use the temporary credentials to access the appropriate S3 bucket.
3. Develop an identity broker that authenticates against LDAP and then calls IAM Security To ken Service to get IAM federated user credentials The application calls the identity broker to get IAMfederated user credentials with access to the appropriate S3 bucket.
4. The application authenticates against LDAP the application then calls the AWS identity and Access Management (IAM) Security service to log in to IAM using the LDAP credentials the application can use the IAM temporary credentials to access the appropriate S3 bucket.
5. The application authenticates against IAM Security Token Service using the LDAP credentials the application uses those temporary AWS security credentials to access the appropriate S3 bucket.
<details>
	<summary>Answer</summary>

	2. The application authenticates against LDAP and retrieves the name of an IAM role associated with the user. The application then ca lls the IAM Security Token Service to assume that IAM role The application can use the temporary credentials to access the appropriate S3 bucket.
	3. Develop an identity broker that authenticates against LDAP and then calls IAM Security To ken Service to get IAM federated user credentials The application calls the identity broker to get IAMfederated user credentials with access to the appropriate S3 bucket.

</details>

### Question 115: A group can contain many users. Can a user belong to multiple groups?
1. Yes always.
2. No.
3. Yes but only if they are using two factor authentication.
4. Yes but only in VPC.
<details>
	<summary>Answer</summary>

	1. Yes always.

</details>

### Question 116: Does Dynamic DB support in-place atomic updates?
1. It is not defined.
2. Yes.
3. It does support in-place non-atomic updates.
<details>
	<summary>Answer</summary>

	2. Yes.

</details>

### Question 117: Can you move a Reserved Instance from one Availability Zone to another?
1. Yes, but each Reserved Instance is associated with a specific Region that cannot be changed.
2. Yes, only in US-West-2.
3. Yes, only in US-East-1.
4. No.
<details>
	<summary>Answer</summary>

	1. Yes, but each Reserved Instance is associated with a specific Region that cannot be changed.

</details>

### Question 118: You want to establish a dedicated network connection from your premises to AWS in order to save money by transferring data directly to AWS rather than through your internet service provider. You are sure there must be some other benefits beyond cost savings. Which of the following statements would be the best choice to put your client's mind at rest?
1. Different instances running on the same physical machine are isolated from each other via a 256-bit Advanced Encryption Standard (AES-256).
2. Different instances running on the same physical machine are isolated from each other via the Xen hypervisor and via a 256-bit Advanced Encryption Standard (AES-256).
3. Different instances running on the same physical machine are isolated from each other via the Xen hypervisor.
4. Different instances running on the same physical machine are isolated from each other via IAM permissions.
<details>
	<summary>Answer</summary>

	3. Different instances running on the same physical machine are isolated from each other via the Xen hypervisor.

</details>

### Question 119: Can I detach the primary (ethO) network interface when the instance is running or stopped?
1. Yes, You can.
2. No. You cannot.
<details>
	<summary>Answer</summary>

	2. No. You cannot.

</details>

### Question 120: You have launched an Amazon Elastic Compute Cloud (EC2) instance into a public subnet with a primary private I P address assigned, an internet gateway is attached to the VPC, and the public route table is configured to send all Internet-based traffic to the Internet gateway. The instance security group is set to allow all outbound traffic but cannot access the internet. Why is the Internet unreachable from this instance?
1. The instance does not have a public IP address.
2. The internet gateway security group must allow all outbound traffic.
3. The instance security group must allow all inbound traffic.
4. The instance 'Source/Destination check' property must be enabled.
<details>
	<summary>Answer</summary>

	1. The instance does not have a public IP address.

</details>

### Question 121: Which of the following statements best describes the differences between Elastic Beanstalk and CloudFormation?
1. Elastic Beanstalk uses Elastic load balancing and CloudFormation doesn't.
2. CloudFormation is faster in deploying applications than Elastic Beanstalk.
3. Elastic Beanstalk is faster in deploying applications than CloudFormation.
4. CloudFormation is much more powerful than Elastic Beanstalk, because you can actually design and script custom resources.
<details>
	<summary>Answer</summary>

	4. CloudFormation is much more powerful than Elastic Beanstalk, because you can actually design and script custom resources.

</details>

### Question 122: It is advised that you watch the Amazon CloudWatch [...] metric (available via the AWS Management Console or Amazon Cloud Watch APIs) carefully and recreate the Read Replica should it fall behind due to replication errors.
1. Write Lag.
2. Read Replica.
3. Replica Lag.
4. Single Replica.
<details>
	<summary>Answer</summary>

	3. Replica Lag.

</details>

### Question 123: Your application provides data transformation services. Files containing data to be transformed are first uploaded to Amazon S3 and then transformed by a fleet of spot EC2 instances. Fi les submitted by your premium customers must be transformed with the highest priority. How should you implement such a system?
1. Use a DynamoDB table with an attribute defining the priority level. Transformation instances will scan the table for tasks, sorting the results by priority level.
2. Use Route 53 latency based-routing to send high priority tasks to the closest transformation instances.
3. Use two SQS queues, one for high priority messages, the other for default priority. Transformation instances first poll the high priority queue; if there is no message, they poll the default priority queue.
4. Use a single SQS queue. Each message contains the priority level. Transformation instances poll high-priority messages first.
<details>
	<summary>Answer</summary>

	3. Use two SQS queues, one for high priority messages, the other for default priority. Transformation instances first poll the high priority queue; if there is no message, they poll the default priority queue.

</details>

### Question 124: True or False: When you view the block device mapping for your instance, you can see only the EBS volumes, not the instance store volumes.
1. Depends on the instance type.
2. False.
3. Depends on whether you use API call.
4. True.
<details>
	<summary>Answer</summary>

	4. True.

</details>

### Question 125: Does AWS CloudFormation support Amazon EC2 tagging?
1. Yes, AWS CloudFormation supports Amazon EC2 tagging.
2. No, CloudFormation doesn't support any tagging.
3. No, it doesn't support Amazon EC2 tagging.
4. It depends if the Amazon EC2 tagging has been defined in the template.
<details>
	<summary>Answer</summary>

	1. Yes, AWS CloudFormation supports Amazon EC2 tagging.

</details>

### Question 126: If I modify a DB Instance or the DB parameter group associated with the instance, should I reboot the instance for the changes to take effect?
1. Yes.
2. No.
<details>
	<summary>Answer</summary>

	1. Yes.

</details>

### Question 127: If you are using Amazon RDS Provisioned IOPS storage with MySQL and Oracle database engines, you can scale the throughput of your database Instance by specifying the IOPS rate from [...].
1. 1,000 to 100,000.
2. 100 to 1,000.
3. 10,000 to 100,000.
4. 1,000 to 10,000.
<details>
	<summary>Answer</summary>

	4. 1,000 to 10,000.

</details>

### Question 128: To specify a resource in a policy statement, in Amazon EC2, can you use its Amazon Resource Name (ARN)?
1. Yes, you can.
2. No, you can't because EC2 is not related to AR
3. No, you can't because you can't specify a particular Amazon EC2 resource in an IAM policy.
4. Yes, you can but only for the resources that are not affected by the action.
<details>
	<summary>Answer</summary>

	1. Yes, you can.

</details>

### Question 129: An enterprise wants to use a third-party SaaS application. The SaaS application needs to have access to issue several API commands to discover Amazon EC2 resources running within the enterprise's account The enterprise has internal security policies that require any outside access to their environment must conform to the principles of least privilege and there must be controls in place to ensure that the credentials used by the 5aa5 vendor cannot be used by any other third party. Which of the following would meet all of these conditions?
1. From the AWS Management Console, navigate to the Security Credentials page and retrieve the access and secret key for your account.
2. Create an IAM user within the enterprise account assign a user policy to the IAM user that allows only the actions required by the SaaS application create a new access and secret key for the user and provide these credentials to the 5aa5 provider.
3. Create an IAM role for cross-account access allows the SaaS provider's account to assume the role and assign it a policy that allows only the actions required by the SaaS application.
4. Create an IAM role for EC2 instances, assign it a policy that allows only the actions required tor the Saas application to work, provide the role ARM to the SaaS provider to use when launching their application instances.
<details>
	<summary>Answer</summary>

	3. Create an IAM role for cross-account access allows the SaaS provider's account to assume the role and assign it a policy that allows only the actions required by the SaaS application.

</details>

### Question 130: By default what are ENIs that are automatically created and attached to instances using the EC2 console set to do when the attached instance terminates?
1. Remain as is.
2. Terminate.
3. Hibernate.
4. Pause.
<details>
	<summary>Answer</summary>

	2. Terminate.

</details>

### Question 131: In EC2, what happens to the data in an instance store if an instance reboots (either intentionally or unintentionally)?
1. Data is deleted from the instance store for security reasons.
2. Data persists in the instance store.
3. Data is partially present in the instance store.
4. Data in the instance store will be lost.
<details>
	<summary>Answer</summary>

	2. Data persists in the instance store.

</details>

### Question 132: You are designing a social media site and are considering how to mitigate distributed denial-of service (DDoS) attacks. Which of the below are viable mitigation techniques? (Choose 3 answers)
1. Add multiple elastic network interfaces (ENis) to each EC2 instance to increase the network bandwidth.
2. Use dedicated instances to ensure that each instance has the maximum performance possible.
3. Use an Amazon CloudFront distribution for both static and dynamic content.
4. Use an Elastic Load Balancer with auto scaling groups at the web. App and Amazon Relational Database Service (RDS) tiers.
5. Add alert Amazon CloudWatch to look for high Network in and CPU utilization.
6. Create processes and capabilities to quickly add and remove rules to the instance OS firewall.
<details>
	<summary>Answer</summary>

	3. Use an Amazon CloudFront distribution for both static and dynamic content.
	4. Use an Elastic Load Balancer with auto scaling groups at the web. App and Amazon Relational Database Service (RDS) tiers.
	5. Add alert Amazon CloudWatch to look for high Network in and CPU utilization.

</details>

### Question 133: In Amazon CloudFront, if you use Amazon EC2 instances and other custom origins with CloudFront, it is recommended to [...].
1. not use Elastic Load Balancing.
2. restrict Internet communication to private instances while allowing outgoing traffic.
3. enable access key rotation for CloudWatch metrics.
4. specify the URL of the load balancer for the domain name of your origin server.
<details>
	<summary>Answer</summary>

	4. specify the URL of the load balancer for the domain name of your origin server.

</details>

### Question 134: Which of the following statements is true regarding attaching network interfaces to your instances in your VPC?
1. You can attach 5 ENIs per instance type.
2. You can attach as many ENIs as you want.
3. The number of ENIs you can attach varies by instance type.
4. You can attach 100 ENIs total regardless of instance type.
<details>
	<summary>Answer</summary>

	3. The number of ENIs you can attach varies by instance type.

</details>

### Question 135: What is the reason for this?
1. For security reasons.
2. Hardware restrictions.
3. Public (IPV4) internet addresses are a scarce resource.
4. There are only 5 network interfaces per instance.
<details>
	<summary>Answer</summary>

	3. Public (IPV4) internet addresses are a scarce resource.

</details>

### Question 136: Can a 'user' be associated with multiple AWS accounts?
1. Yes.
2. No.
<details>
	<summary>Answer</summary>

	2. No.

</details>

### Question 137: You have an application running on an Amazon Elastic Compute Cloud instance, that uploads 5 GB video objects to Amazon Simple Storage Service (S3). Video uploads are taking longer than expected, resulting in poor application performance. Which method will help improve performance of your application?
1. Enable enhanced networking.
2. Use Amazon S3 multipart upload.
3. Leveraging Amazon CloudFront, use the HTTP POST method to reduce latency.
4. Use Amazon Elastic Block Store Provisioned IOPs and use an Amazon EBS-optimized instance.
<details>
	<summary>Answer</summary>

	2. Use Amazon S3 multipart upload.

</details>

### Question 138: You have been given a scope to set up an AWS Media Sharing Framework for a new start up photo sharing company similar to flickr. The first thing that comes to mind about this is that it will obviously need a huge amount of persistent data storage for this framework. Which of the following storage options would be appropriate for persistent storage?
1. Amazon Glacier or Amazon S3.
2. Amazon Glacier or AWS Import/Export.
3. AWS Import/Export or Amazon CloudFront.
4. Amazon EBS volumes or Amazon S3.
<details>
	<summary>Answer</summary>

	4. Amazon EBS volumes or Amazon S3.

</details>

### Question 139: You need a persistent and durable storage to trace call activity of an IVR (Interactive Voice Response) system. Call duration is mostly in the 2-3 minutes timeframe. Each traced call can be either active or terminated. An external application needs to know each minute the list of currently active calls, which are usually a few calls/second. Put once per month there is a periodic peak up to 1000 calls/second for a few hours. The system is open 24/7 and any downtime should be avoided. Historical data is periodically archived to files. Cost saving is a priority for this project. What database implementation would better fit this scenario, keeping costs as low as possible?
1. Use RDS Multi-AZ with two tables, one for 'Active calls' and one for 'Terminated calls'. in this way the 'Active calls' table is always small and effective to access.
2. Use DynamoDB with a 'Calls' table and a Global Secondary Index on a 'lsActive' attribute that is present for active calls only in this way the Global Secondary index is sparse and more effective.
3. Use DynamoDB with a 'Calls' table and a Global secondary index on a 'State' attribute that can equal to 'active' or 'terminated' in this way the Global Secondary index can be used for all Items in the table.
4. Use RDS Multi-AZ with a 'CALLS' table and an Indexed 'STATE* field that can be equal to 'ACTIVE' or 'TERMINATED' in this way the SOL query Is optimized by the use of the Index.
<details>
	<summary>Answer</summary>

	1. Use RDS Multi-AZ with two tables, one for 'Active calls' and one for 'Terminated calls'. in this way the 'Active calls' table is always small and effective to access.

</details>

### Question 140: If you have chosen Multi-AZ deployment, in the event of a planned or unplanned outage of your primary DB Instance, Amazon RDS automatically switches to the standby replica. The automatic failover mechanism simply changes the record of the main DB Instance to point to the standby DB Instance.
1. DNAME.
2. CNAME.
3. TXT.
4. MX.
<details>
	<summary>Answer</summary>

	2. CNAME.

</details>

### Question 141: All Amazon EC2 instances are assigned two IP addresses at launch. Which are those?
1. 2 Elastic IP addresses.
2. A private IP address and an Elastic IP address.
3. A public IP address and an Elastic IP address.
4. A private IP address and a public IP address.
<details>
	<summary>Answer</summary>

	4. A private IP address and a public IP address.

</details>

### Question 142: You need to pass a custom script to new Amazon Linux instances created in your Auto Scaling group. Which feature allows you to accomplish this?
1. User data.
2. EC2Config service.
3. IAM roles.
4. AWS Config.
<details>
	<summary>Answer</summary>

	2. EC2Config service.

</details>

### Question 143: A customer wants to track access to their Amazon Simple Storage Service (S3) buckets and also use this information for their internal security and access audits. Which of the following will meet the Customer requirement?
1. Enable AWS CloudTrail to audit all Amazon S3 bucket access.
2. Enable server access logging for all required Amazon S3 buckets.
3. Enable the Requester Pays option to track access via AWS Billing.
4. Enable Amazon S3 event notifications for Put and Post.
<details>
	<summary>Answer</summary>

	1. Enable AWS CloudTrail to audit all Amazon S3 bucket access.

</details>

### Question 144: Which DNS name can only be resolved within Amazon EC2?
1. Public DNS name.
2. Internal DNS name.
3. External DNS name.
4. Global DNS name.
<details>
	<summary>Answer</summary>

	2. Internal DNS name.

</details>

### Question 145: An AWS customer is deploying an application mat is composed of an AutoScaling group of EC2 Instances. The customers security policy requires that every outbound connection from these instances to any other service within the customers Virtual Private Cloud must be authenticated using a unique x 509 certificate that contains the specific instance-id. In addition an x 509 certificates must Designed by the customer's Key management service in order to be trusted for authentication. Which of the following configurations will support these requirements?
1. Configure an IAM Role that grants access to an Amazon S3 object containing a signed certificate and configure me Auto Scaling group to launch instances with this role Have the instances bootstrap get the certificate from Amazon S3 upon first boot.
2. Embed a certificate into the Amazon Machine Image that is used by the Auto Scaling group Have the launched instances generate a certificate signature request with the instance's assigned instance- id to the Key management service for signature.
3. Configure the Auto Scaling group to send an SNS notification of the launch of a new instance to the trusted key management service. Have the Key management service generate a signed certificate and send it directly to the newly launched instance.
4. Configure the launched instances to generate a new certificate upon first boot Have the Key management service poll the AutoScaling group for associated instances and send new instances a certificate signature (hat contains the specific instance-id.
<details>
	<summary>Answer</summary>

	1. Configure an IAM Role that grants access to an Amazon S3 object containing a signed certificate and configure me Auto Scaling group to launch instances with this role Have the instances bootstrap get the certificate from Amazon S3 upon first boot.

</details>

### Question 146: A company is storing data on Amazon Simple Storage Service (S3). The company’s security policy mandates that data is encrypted at rest. Which of the following methods can achieve this? (Choose 3 answers)
1. Use Amazon S3 server-side encryption with AWS Key Management Service managed keys.
2. Use Amazon S3 server-side encryption with customer-provided keys.
3. Use Amazon S3 server-side encryption with EC2 key pair.
4. Use Amazon S3 bucket policies to restrict access to the data at rest.
5. Encrypt the data on the client-side before ingesting to Amazon S3 using their own master key.
6. Use SSL to encrypt the data while in transit to Amazon S3.
<details>
	<summary>Answer</summary>

	1. Use Amazon S3 server-side encryption with AWS Key Management Service managed keys.
	2. Use Amazon S3 server-side encryption with customer-provided keys.
	5. Encrypt the data on the client-side before ingesting to Amazon S3 using their own master key.

</details>

### Question 147: In Amazon EC2, you are billed instance-hours when [...].
1. your EC2 instance is in a running state.
2. the instance exits from Amazon S3 console.
3. your instance still exits the EC2 console.
4. EC2 instances stop.
<details>
	<summary>Answer</summary>

	1. your EC2 instance is in a running state.

</details>

### Question 148: Which of the below mentioned options is a possible solution to avoid any security threat?
1. Use the IAM based single sign between the AWS resources and the organization application.
2. Use the IAM role and assign it to the instance.
3. Since the application is hosted on EC2, it does not need credentials to access S3.
4. Use the 509 certificates instead of the access and the secret access keys.
<details>
	<summary>Answer</summary>

	2. Use the IAM role and assign it to the instance.

</details>

### Question 149: In Amazon EC2 Container Service components, what is the name of a logical grouping of container instances on which you can place tasks?
1. A cluster.
2. A container instance.
3. A container.
4. A task definition.
<details>
	<summary>Answer</summary>

	1. A cluster.

</details>

### Question 150: You are looking to migrate your Development (Dev) and Test environments to AWS. You have decided to use separate AWS accounts to host each environment. You plan to link each accounts bill to a Master AWS account using Consolidated Billing. To make sure you Keep within budget you would like to implement a way for administrators in the Master account to have access to stop, delete and/or terminate resources in both the Dev and Test accounts. Identify which option will allow you to achieve this goal.
1. Create IAM users in the Master account with full Admin permissions. Create cross-account roles in the Dev and Test accounts that grant the Master account access to the resources in the account by inheriting permissions from the Master account.
2. Create IAM users and a cross-account role in the Master account that grants full Admin permissions to the Dev and Test accounts.
3. Create IAM users in the Master account Create cross-account roles in the Dev and Test accounts that have full Admin permissions and grant the Master.
4. Link the accounts using Consolidated Billing. This will give IAM users in the Master account access to resources in the Dev and Test accounts.
<details>
	<summary>Answer</summary>

	3. Create IAM users in the Master account Create cross-account roles in the Dev and Test accounts that have full Admin permissions and grant the Master.

</details>

### Question 151: What will be the status of the snapshot until the snapshot is complete?
1. Running.
2. Working.
3. Progressing.
4. Pending.
<details>
	<summary>Answer</summary>

	4. Pending.

</details>

### Question 152: A customer is running a multi-tier web application farm in a virtual private cloud (VPC) that is not connected to their corporate network. They are connecting to the VPC over the Internet to manage all of their Amazon EC2 instances running in both the public and private subnets. They have only authorized the bastion-security-group with Microsoft Remote Desktop Protocol (RDP) access to the application instance security groups, but the company wants to further limit administrative access to all of the instances in the VPC. Which of the following Bastion deployment scenarios will meet this requirement?
1. Deploy a Windows Bastion host on the corporate network that has RDP access to all instances in the VP.
2. Deploy a Windows Bastion host with an Elastic IP address in the public subnet and allow SSH access to the bastion from anywhere.
3. Deploy a Windows Bastion host with an Elastic IP address in the private subnet, and restrict RDP access to the bastion from only the corporate public IP addresses.
4. Deploy a Windows Bastion host with an auto-assigned Public IP address in the public subnet, and allow RDP access to the bastion from only the corporate public IP addresses.
<details>
	<summary>Answer</summary>

	3. Deploy a Windows Bastion host with an Elastic IP address in the private subnet, and restrict RDP access to the bastion from only the corporate public IP addresses.

</details>

### Question 153: True or False: Common points of failures like generators and cooling equipment are shared across Availability Zones.
1. True.
2. False.
<details>
	<summary>Answer</summary>

	2. False.

</details>

### Question 154: A company is building a voting system for a popular TV show, viewers win watch the performances then visit the show's website to vote for their favorite performer. It is expected that in a short period of time after the show has finished the site will receive millions of visitors. The visitors will first login to the site using their Amazon.com credentials and then submit their vote. After the voting is completed the page will display the vote totals. The company needs to build the site such that can handle the rapid influx of traffic while maintaining good performance but also wants to keep costs to a minimum. Which of the design patterns below should they use?
1. Use CloudFront and an Elastic Load balancer in front of an auto-scaled set of web servers, the web servers will first can the Login With Amazon service to authenticate the user then process the users vote and store the result into a multi-AZ Relational Database Service instance.
2. Use CloudFront and the static website hosting feature of S3 with the Javascript SDK to call the Login With Amazon service to authenticate the user, use IAM Roles to gain permissions to a DynamoDB table to store the users vote.
3. Use CloudFront and an Elastic Load Balancer in front of an auto-scaled set of web servers, the web servers will first call the Login with Amazon service to authenticate the user, the web servers will process the users vote and store the result into a DynamoDB table using IAM Roles for EC2 instances to gain permissions to the DynamoDB table.
4. Use CloudFront and an Elastic Load Balancer in front of an auto-scaled set of web servers, the web servers will first call the Login. With Amazon service to authenticate the user, the web servers win process the users vote and store the result into an SQS queue using IAM Roles for EC2 Instances to gain permissions to the SQS queue. A set of application servers will then retrieve the items from the queue and store the result into a DynamoDB table.
<details>
	<summary>Answer</summary>

	4. Use CloudFront and an Elastic Load Balancer in front of an auto-scaled set of web servers, the web servers will first call the Login. With Amazon service to authenticate the user, the web servers win process the users vote and store the result into an SQS queue using IAM Roles for EC2 Instances to gain permissions to the SQS queue. A set of application servers will then retrieve the items from the queue and store the result into a DynamoDB table.

</details>

### Question 155: You are designing a photo sharing mobile app the application will store all pictures in a single Amazon S3 bucket. Users will upload pictures from their mobile device directly to Amazon S3 and will be able to view and download their own pictures directly from Amazon S3. You want to configure security to handle potentially millions of users in the most secure manner possible. What should your server-side application do when a new user registers on the photo sharing mobile application?
1. Create a set of long-term credentials using AWS Security Token Service with appropriate permissions Store these credentials in the mobile app and use them to access Amazon S3.
2. Record the user's Information in Amazon RDS and create a role in IAM with appropriate permissions. When the user uses their mobile app create temporary credentials using the AWS Security Token Service 'Assume Role' function Store these credentials in the mobile app's memory and use them to access Amazon S3 Generate new credentials the next time the user runs the mobile app.
3. Record the user's Information in Amazon DynamoDB.
4. When the user uses their mobile app create temporary credentials using AWS Security Token Service with appropriate permissions Store these credentials in the mobile app's memory and use them to access Amazon S3 Generate new credentials the next time the user runs the mobile app.
5. Create IAM user. Assign appropriate permissions to the IAM user Generate an access key and secret key for the IAM user, store them in the mobile app and use these credentials to access Amazon S3.
6. Create an IAM user. Update the bucket policy with appropriate permissions for the IAM user Generate an access Key and secret Key for the IAM user, store them in the mobile app and use these credentials to access Amazon S3.
<details>
	<summary>Answer</summary>

	2. Record the user's Information in Amazon RDS and create a role in IAM with appropriate permissions. When the user uses their mobile app create temporary credentials using the AWS Security Token Service 'Assume Role' function Store these credentials in the mobile app's memory and use them to access Amazon S3 Generate new credentials the next time the user runs the mobile app.

</details>

### Question 156: Is there a limit to how many groups a user can be in?
1. Yes for all users.
2. Yes for all users except root.
3. No.
4. Yes unless special permission granted.
<details>
	<summary>Answer</summary>

	1. Yes for all users.

</details>

### Question 157: Which is the default region in AWS?
1. eu-west-1.
2. us-east-1.
3. us-east-2.
4. ap-southeast-1.
<details>
	<summary>Answer</summary>

	2. us-east-1.

</details>

### Question 158: Your company hosts a social media site supporting users in multiple countries. You have been asked to provide a highly available design tor the application that leverages multiple regions tor the most recently accessed content and latency sensitive portions of the wet) site The most latency sensitive component of the application involves reading user preferences to support web site personalization and ad selection. In addition to running your application in multiple regions, which option will support this application's requirements?
1. Serve user content from S3. CloudFront and use Route 53 latency-based routing between ELBs in each region Retrieve user preferences from a local DynamoDB table in each region and leverage SQS to capture changes to user preferences with 505 workers for propagating updates to each table.
2. Use the 53 Copy API to copy recently accessed content to multiple regions and serve user content from S3. CloudFront with dynamic content and an ELB in each region Retrieve user preferences from an ElasticCache cluster in each region and leverage SNS notifications to propagate user preference changes to a worker node in each region.
3. Use the 53 Copy API to copy recently accessed content to multiple regions and serve user content from S3 CloudFront and Route 53 latency-based routing Between ELBs in each region Retrieve user preferences from a DynamoDB table and leverage SQS to capture changes to user preferences with 505 workers for propagating DynamoDB updates.
4. Serve user content from S3. CloudFront with dynamic content, and an ELB in each region Retrieve user preferences from an ElastiCache cluster in each region and leverage Simple Workflow (SWF) to manage the propagation of user preferences from a centralized OB to each ElastiCache cluster.
<details>
	<summary>Answer</summary>

	1. Serve user content from S3. CloudFront and use Route 53 latency-based routing between ELBs in each region Retrieve user preferences from a local DynamoDB table in each region and leverage SQS to capture changes to user preferences with 505 workers for propagating updates to each table.

</details>

### Question 159: A [...] is a document that provides a formal statement of one or more permissions.
1. policy.
2. permission.
3. role.
4. resource.
<details>
	<summary>Answer</summary>

	1. policy.

</details>

### Question 160: A company wants to implement their website in a virtual private cloud (VPC). The web tier will use an Auto Scaling group across multiple Availability Zones (AZs). The database will use Multi-AZ RDSMySQL and should not be publicly accessible. What is the minimum number of subnets that need to be configured in the VPC?
1. 1.
2. 2.
3. 3.
4. 4.
<details>
	<summary>Answer</summary>

	2. 2.

</details>

### Question 161: Is there a limit to the number of groups you can have?
1. Yes for all users except root.
2. No.
3. Yes unless special permission granted.
4. Yes for all users.
<details>
	<summary>Answer</summary>

	4. Yes for all users.

</details>

### Question 162: True or False: Automated backups are enabled by default for a new DB Instance
1. True.
2. False.
<details>
	<summary>Answer</summary>

	1. True.

</details>

### Question 163: What is one key difference between an Amazon EBS-backed and an instance-store backed instance?
1. Amazon EBS-backed instances can be stopped and restarted.
2. Instance-store backed instances can be stopped and restarted.
3. Auto scaling requires using Amazon EBS-backed instances.
4. Virtual Private Cloud requires EBS backed instances.
<details>
	<summary>Answer</summary>

	1. Amazon EBS-backed instances can be stopped and restarted.

</details>

### Question 164: A major customer has asked you to set up his AWS infrastructure so that it will be easy to recover in the case of a disaster of some sort. Which of the following statements is true of Amazon EC2 security groups?
1. Create and maintain AMIs of key servers where fast recovery is required.
2. Regularly run your servers, test them, and apply any software updates and configuration changes.
3. Ensure that you have all supporting custom software packages available in AW.
4. All items listed here are important when thinking about disaster recovery.
<details>
	<summary>Answer</summary>

	4. All items listed here are important when thinking about disaster recovery.

</details>

### Question 165: Select a true statement about Amazon EC2 Security Groups (EC2-Classic).
1. After you launch an instance in EC2-Classic, you can't change its security groups.
2. After you launch an instance in EC2-Classic, you can change its security groups only once.
3. After you launch an instance in EC2-Classic, you can only add rules to a security group.
4. After you launch an instance in EC2-Classic, you cannot add or remove rules from a security group.
<details>
	<summary>Answer</summary>

	1. After you launch an instance in EC2-Classic, you can't change its security groups.

</details>

### Question 166: To view information about an Amazon EBS volume, open the Amazon EC2 console at <https://console.aws.amazon.com/ec2/>, click in the Navigation panel.
1. EBS.
2. Describe.
3. Details.
4. Volumes.
<details>
	<summary>Answer</summary>

	4. Volumes.

</details>

### Question 167: True or False: Provisioned IOPS Costs - you are charged for the IOPS and storage whether or not you use them in a given month.
1. True.
2. False.
<details>
	<summary>Answer</summary>

	1. True.

</details>

### Question 168: You have an EC2 Security Group with several running EC2 instances. You change the Security Group rules to allow inbound traffic on a new port and protocol, and launch several new instances in the same Security Group. The new rules apply:
1. Immediately to all instances in the security group.
2. Immediately to the new instances only.
3. Immediately to the new instances, but old instances must be stopped and restarted before the new rules apply.
4. To all instances, but it may take several minutes for old instances to see the changes.
<details>
	<summary>Answer</summary>

	1. Immediately to all instances in the security group.

</details>

### Question 169: An edge location refers to which Amazon Web Service?
1. An edge location is referred to the network configured within a Zone or Region.
2. An edge location is an AWS Region.
3. An edge location is the location of the data center used for Amazon CloudFront.
4. An edge location is a Zone within an AWS Region.
<details>
	<summary>Answer</summary>

	3. An edge location is the location of the data center used for Amazon CloudFront.

</details>

### Question 170: If I want to run a database in an Amazon instance, which is the most recommended Amazon storage option?
1. Amazon Instance Storage.
2. Amazon EBS.
3. You can't run a database inside an Amazon instance.
4. Amazon S3.
<details>
	<summary>Answer</summary>

	2. Amazon EBS.

</details>

### Question 171: A customer is leveraging Amazon Simple Storage Service in eu-west-1 to store static content for a web-based property. The customer is storing objects using the Standard Storage class. Where are the customers objects replicated?
1. A single facility in eu-west-1 and a single facility in eu-central-1.
2. A single facility in eu-west-1 and a single facility in us-east-1.
3. Multiple facilities in eu-west-1.
4. A single facility in eu-west-1.
<details>
	<summary>Answer</summary>

	3. Multiple facilities in eu-west-1.

</details>

### Question 172: You have set up an S3 bucket with a number of images in it and you have decided that you want anybody to be able to access these images, even anonymous users. To accomplish this you create a bucket policy. You will need to use an Amazon S3 bucket policy that specifies a [...] in the principal element, which means anyone can access the bucket.
1. hash tag (#).
2. anonymous user.
3. wildcard (*).
4. S3 user.
<details>
	<summary>Answer</summary>

	3. wildcard (*).

</details>

### Question 173: You try to connect via SSH to a newly created Amazon EC2 instance and get one of the following error messages: 'Network error: Connection timed out' or 'Error connecting to [instance], reason: -> Connection timed out: connect,' You have confirmed that the network and security group rules are configured correctly and the instance is passing status checks. What steps should you take to identify the source of the behavior? (Choose 2 answers)
1. Verify that the private key file corresponds to the Amazon EC2 key pair assigned at launch.
2. Verify that your IAM user policy has permission to launch Amazon EC2 instances.
3. Verify that you are connecting with the appropriate user name for your AMI.
4. Verify that the Amazon EC2 Instance was launched with the proper IAM role.
5. Verify that your federation trust to AWS has been established.
<details>
	<summary>Answer</summary>

	1. Verify that the private key file corresponds to the Amazon EC2 key pair assigned at launch.
	3. Verify that you are connecting with the appropriate user name for your AMI.

</details>

### Question 174: An Auto-Scaling group spans 3 AZs and currently has 4 running EC2 instances. When Auto Scaling needs to terminate an EC2 instance by default, AutoScaling will: (Choose 2 answers)
1. Allow at least five minutes for Windows/Linux shutdown scripts to complete, before terminating the instance.
2. Terminate the instance with the least active network connections. If multiple instances meet this criterion, one will be randomly selected.
3. Send an SNS notification, if configured to do so.
4. Terminate an instance in the AZ which currently has 2 running EC2 instances.
5. Randomly select one of the 3 AZs, and then terminate an instance in that A.
<details>
	<summary>Answer</summary>

	3. Send an SNS notification, if configured to do so.
	4. Terminate an instance in the AZ which currently has 2 running EC2 instances.

</details>

### Question 175: A photo-sharing service stores pictures in Amazon Simple Storage Service (S3) and allows application sign-in using an OpenID Connect-compatible identity provider. Which AWS Security Token Service approach to temporary access should you use for the Amazon S3 operations?
1. SAML-based Identity Federation.
2. Cross-Account Access.
3. AWS Identity and Access Management roles.
4. Web Identity Federation.
<details>
	<summary>Answer</summary>

	4. Web Identity Federation.

</details>

### Question 176: What is the maximum key length of a tag?
1. 512 Unicode characters.
2. 64 Unicode characters.
3. 256 Unicode characters.
4. 128 Unicode characters.
<details>
	<summary>Answer</summary>

	4. 128 Unicode characters.

</details>

### Question 177: Does Amazon RDS allow direct host access via Telnet, Secure Shell (SSH), or Windows Remote Desktop Connection?
1. Yes.
2. No.
<details>
	<summary>Answer</summary>

	2. No.

</details>

### Question 178: A user wants to achieve High Availability with PostgreSQL DB. Which of the below mentioned functionalities helps achieve HA?
1. Multi-AZ.
2. Read Replica.
3. Multi region.
4. PostgreSQL does not support HA.
<details>
	<summary>Answer</summary>

	1. Multi-AZ.

</details>

### Question 179: Are penetration tests allowed as long as they are limited to the customer's instances?
1. Yes, they are allowed but only for selected regions.
2. No, they are never allowed.
3. Yes, they are allowed without any permission.
4. Yes, they are allowed but only with approval.
<details>
	<summary>Answer</summary>

	4. Yes, they are allowed but only with approval.

</details>

### Question 180: You are building a system to distribute confidential documents to employees. Using CloudFront, what method could be used to serve content that is stored in S3, but not publically accessible from S3 directly?
1. Add the CloudFront account security group 'amazon-cf/amazon-cf-sg' to the appropriate S3 bucket policy.
2. Create a S3 bucket policy that lists the CloudFront distribution ID as the Principal and the target bucket as the Amazon Resource Name (ARN).
3. Create an Identity and Access Management (IAM) User for CloudFront and grant access to the objects in your S3 bucket to that IAM User.
4. Create an Origin Access Identity (OAI) for CloudFront and grant access to the objects in your S3 bucket to that OA.
<details>
	<summary>Answer</summary>

	4. Create an Origin Access Identity (OAI) for CloudFront and grant access to the objects in your S3 bucket to that OA.

</details>

### Question 181: You require the ability to analyze a large amount of data, which is stored on Amazon S3 using Amazon Elastic MapReduce. You are using the cc2 8x large Instance type, whose CPUs are mostly idle during processing. Which of the below would be the most cost efficient way to reduce the runtime of the job?
1. Create more smaller flies on Amazon S3.
2. Add additional cc2 8x large instances by introducing a task group.
3. Use smaller instances that have higher aggregate 1/0 performance.
4. Create fewer, larger fi les on Amazon S3.
<details>
	<summary>Answer</summary>

	3. Use smaller instances that have higher aggregate 1/0 performance.

</details>

### Question 182: What is the name of licensing model in which I can use your existing Oracle Database licenses to run Oracle deployments on Amazon RDS?
1. Bring Your Own License.
2. Role Bases License.
3. Enterprise License.
4. License Included.
<details>
	<summary>Answer</summary>

	1. Bring Your Own License.

</details>

### Question 183: Which of the following statements are true about Amazon Route 53 resource records? (Choose 2 answers)
1. An Alias record can map one DNS name to another Amazon Route 53 DNS name.
2. A CNAME record can be created for your zone apex.
3. An Amazon Route 53 CNAME record can point to any DNS record hosted anywhere.
4. TIL can be set for an Alias record in Amazon Route 53.
5. An Amazon Route 53 Alias record can point to any DNS record hosted anywhere.
<details>
	<summary>Answer</summary>

	1. An Alias record can map one DNS name to another Amazon Route 53 DNS name.
	3. An Amazon Route 53 CNAME record can point to any DNS record hosted anywhere.

</details>

### Question 184: Do you need to shutdown your EC2 instance when you create a snapshot of EBS volumes that serve as root devices?
1. No, you only need to shutdown an instance before deleting it.
2. Yes.
3. No, the snapshot would turn off your instance automatically.
4. No.
<details>
	<summary>Answer</summary>

	2. Yes.

</details>

### Question 185: Can I initiate a 'forced failover' for my Oracle Multi-AZ DB Instance deployment?
1. Yes.
2. Only in certain regions.
3. Only in VPC.
4. No.
<details>
	<summary>Answer</summary>

	1. Yes.

</details>

### Question 186: Amazon RDS provides high availability and failover support for DB instances using [...].
1. customized deployments.
2. AppStream customizations.
3. log events.
4. Multi-AZ deployments.
<details>
	<summary>Answer</summary>

	4. Multi-AZ deployments.

</details>

### Question 187: True or False: Amazon EC2 has no Amazon Resource Names (ARNs) because you can't specify a particular Amazon EC2 resource in an IAM policy.
1. True.
2. False.
<details>
	<summary>Answer</summary>

	1. True.

</details>

### Question 188: A major client who has been spending a lot of money on his internet service provider asks you to set up an AWS Direct Connection to try and save him some money. You know he needs high-speed connectivity. Which connection port speeds are available on AWS Direct Connect?
1. 500Mbps and 1Gbps.
2. 1Gbps and 10Gbps.
3. 100Mbps and 1Gbps.
4. 1Gbps.
<details>
	<summary>Answer</summary>

	2. 1Gbps and 10Gbps.

</details>

### Question 189: What will be the state of the alarm at the end of 90 minutes, if the CPU utilization is constant at 80%?
1. ALERT.
2. ALARM.
3. OK.
4. INSUFFICIENT_DATA.
<details>
	<summary>Answer</summary>

	2. ALARM.

</details>

### Question 190: A 3-tier e-commerce web application is current deployed on-premises and will be migrated to AWS for greater scalability and elasticity The web server currently shares read-only data using a network distributed file system The app server tier uses a clustering mechanism for discovery and shared session state that depends on I P multicast The database tier uses shared-storage clustering to provide database fail over capability, and uses several read slaves for scaling Data on all servers and the distributed file system directory is backed up weekly to off-site tapes. Which AWS storage and database architecture meets the requirements of the application?
1. Web servers: store read-only data in S3, and copy from S3 to root volume at boot time. App servers: share state using a combination of DynamoDB and IP unicast. Database: use RDS with multi-AZdeployment and one or more read replicas. Backup: web servers, app servers, and database backed up weekly to Glacier using snapshots.
2. Web servers: store read-only data in an EC2 NFS server, mount to each web server at boot time. App servers: share state using a combination of DynamoDB and IP multicast. Database: use RDS with multi-AZ deployment and one or more Read Replicas. Backup: web and app servers backed up weekly via AMIs, database backed up via DB snapshots.
3. Web servers: store read-only data in S3, and copy from S3 to root volume at boot time. App servers: share state using a combination of DynamoDB and IP unicast. Database: use RDS with multi-AZ deployment and one or more Read Replicas. Backup: web and app servers backed up weekly via AMIs, database backed up via DB snapshots.
4. Web servers: store read-only data in S3, and copy from S3 to root volume at boot time. App servers: share state using a combination of DynamoDB and IP unicast. Database: use RDS with multi-AZdeployment. Backup: web and app servers backed up weekly via AMIs, database backed up via DB snapshots.
<details>
	<summary>Answer</summary>

	3. Web servers: store read-only data in S3, and copy from S3 to root volume at boot time. App servers: share state using a combination of DynamoDB and IP unicast. Database: use RDS with multi-AZ deployment and one or more Read Replicas. Backup: web and app servers backed up weekly via AMIs, database backed up via DB snapshots.

</details>

### Question 191: What are the four levels of AWS Premium Support?
1. Basic, Developer, Business, Enterprise.
2. Basic, Startup, Business, Enterprise.
3. Free, Bronze, Silver, Gold.
4. All support is free.
<details>
	<summary>Answer</summary>

	1. Basic, Developer, Business, Enterprise.

</details>

### Question 192: What is the default maximum number of Access Keys per user?
1. 10.
2. 15.
3. 2.
4. 20.
<details>
	<summary>Answer</summary>

	3. 2.

</details>

### Question 193: In the most recent company meeting, your CEO focused on the fact that everyone in the organization needs to make sure that all of the infrastructure that is built is truly scalable. Which of the following statements is incorrect in reference to scalable architecture?
1. A scalable service is capable of handling heterogeneity.
2. A scalable service is resilient.
3. A scalable architecture won't be cost effective as it grows.
4. Increasing resources results in a proportional increase in performance.
<details>
	<summary>Answer</summary>

	3. A scalable architecture won't be cost effective as it grows.

</details>

### Question 194: What does Amazon S3 stand for?
1. Simple Storage Solution.
2. Storage Storage Storage (triple redundancy Storage).
3. Storage Server Solution.
4. Simple Storage Service.
<details>
	<summary>Answer</summary>

	4. Simple Storage Service.

</details>

### Question 195: A company needs to monitor the read and write IOPs metrics for their AWS MySQL RDS instance and send real-time alerts to their operations team. Which AWS services can accomplish this? (Choose 2 answers)
1. Amazon Simple Email Service.
2. Amazon CloudWatch.
3. Amazon Simple Queue Service.
4. Amazon Route 53.
5. Amazon Simple Notification Service.
<details>
	<summary>Answer</summary>

	2. Amazon CloudWatch.
	5. Amazon Simple Notification Service.

</details>

### Question 196: A user has configured ELB with two EBS backed EC2 instances. The user is trying to understand the DNS access and IP support for ELB. Which of the below mentioned statements may not help the user understand the IP mechanism supported by ELB?
1. The client can connect over IPV4 or IPV6 using Dualstack.
2. Communication between the load balancer and back-end instances is always through IPV4.
3. ELB DNS supports both IPV4 and IPV6.
4. The ELB supports either IPV4 or IPV6 but not both.
<details>
	<summary>Answer</summary>

	4. The ELB supports either IPV4 or IPV6 but not both.

</details>

### Question 197: What is Oracle SQL Developer?
1. An AWS developer who is an expert in Amazon RDS using both the Oracle and SQL Server DB engines.
2. A graphical Java tool distributed without cost by Oracle.
3. It is a variant of the SQL Server Management Studio designed by Microsoft to support Oracle DBMS functionalities.
4. A different DBMS released by Microsoft free of cost.
<details>
	<summary>Answer</summary>

	2. A graphical Java tool distributed without cost by Oracle.

</details>

### Question 198: You can use [...] to help secure the instances in your VPC.
1. security groups and multi-factor authentication.
2. security groups and 2-Factor authentication.
3. security groups and biometric authentication.
4. security groups and network ACLs.
<details>
	<summary>Answer</summary>

	4. security groups and network ACLs.

</details>

### Question 199: What is the type of monitoring data (for Amazon EBS volumes) which is available automatically in 5- minute periods at no charge called?
1. Basic.
2. Primary.
3. Detailed.
4. Local.
<details>
	<summary>Answer</summary>

	1. Basic.

</details>

### Question 200: A user comes to you and wants access to Amazon CloudWatch but only wants to monitor a specific LoadBalancer. Is it possible to give him access to a specific set of instances or a specific LoadBalancer?
1. No because you can't use IAM to control access to CloudWatch data for specific resources.
2. Yes. You can use IAM to control access to CloudWatch data for specific resources.
3. No because you need to be Sysadmin to access CloudWatch data.
4. Yes. Any user can see all CloudWatch data and needs no access rights.
<details>
	<summary>Answer</summary>

	1. No because you can't use IAM to control access to CloudWatch data for specific resources.

</details>

### Question 201: Which Amazon Elastic Compute Cloud feature can you query from within the instance to access instance properties?
1. Instance user data.
2. Resource tags.
3. Instance metadata.
4. Amazon Machine Image.
<details>
	<summary>Answer</summary>

	3. Instance metadata.

</details>

### Question 202: Making your snapshot public shares all snapshot data with everyone. Can the snapshots with AWS Market place product codes be made public?
1. Yes.
2. No.
<details>
	<summary>Answer</summary>

	1. Yes.

</details>

### Question 203: Which service enables AWS customers to manage users and permissions in AWS?
1. AWS Access Control Service (ACS).
2. AWS Identity and Access Management (IAM).
<details>
	<summary>Answer</summary>

	2. AWS Identity and Access Management (IAM).

</details>

### Question 204: You have launched an EC2 instance with four (4) 500 GB EBS Provisioned IOPS volumes attached. The EC2 instance is EBS-Optimized and supports 500 Mbps throughput between EC2 and EBS. The four EBS volumes are configured as a single RAID 0 device, and each Provisioned IOPS volume is provisioned with 4,000IOPS (4,000 16KB reads or writes), for a total of 16,000 random IOPS on the instance. The EC2 instance initially delivers the expected 16,000 IOPS random read and write performance. Sometime later, in order to increase the total random I/O performance of the instance, you add an additional two 500 GB EBS Provisioned IOPS volumes to the RAID. Each volume is provisioned to 4,000 IOPs like the original four, for a total of 24,000 IOPS on the EC2 instance. Monitoring shows that the EC2 instance CPU utilization increased from 50% to 70%, but the total random IOPS measured at the instance level does not increase at all. What is the problem and a valid solution?
1. Larger storage volumes support higher Provisioned IOPS rates; increase the provisioned volume storage of each of the 6 EBS volumes to 1TB.
2. The EBS-Optimized throughput limits the total IOPS that can be utilized; use an EBS Optimized instance that provides larger throughput. Mo
3. Small block sizes cause performance degradation, limiting the I/O throughput; configure the instance device driver and filesystem to use 64KB blocks to increase throughput.
4. The standard EBS Instance root volume limits the total IOPS rate; change the instance root volume to also be a 500GB 4,000 Provisioned IOPS volume.
5. RAID 0 only scales linearly to about 4 devices; use RAID 0 with 4 EBS Provisioned IOPS volumes, but increase each Provisioned IOPS EBS volume to 6,000 IOPS.
<details>
	<summary>Answer</summary>

	2. The EBS-Optimized throughput limits the total IOPS that can be utilized; use an EBS Optimized instance that provides larger throughput. Mo

</details>

### Question 205: A user has configured a website and launched it using the Apache web server on port 80. The user is using ELB with the EC2 instances for Load Balancing. What should the user do to ensure that the EC2 instances accept requests only from ELB?
1. Configure the security group of EC2, which allows access to the ELB source security group.
2. Configure the EC2 instance so that it only listens on the ELB port.
3. Open the port for an ELB static IP in the EC2 security group.
4. Configure the security group of EC2, which allows access only to the ELB listener.
<details>
	<summary>Answer</summary>

	1. Configure the security group of EC2, which allows access to the ELB source security group.

</details>

### Question 206: You're trying to delete an SSL certificate from the IAM certificate store, and you're getting the message 'Certificate: <certificate< span=''>-id> is being used by CloudFront.' Which of the following statements is probably the reason why you are getting this error?
1. Before you can delete an SSL certificate, you need to either rotate SSL certificates or revert from using a custom SSL certificate to using the default CloudFront certificate.
2. You can't delete SSL certificates. You need to request it from AW.
3. Before you can delete an SSL certificate, you need to set up the appropriate access level in IAM. Before you can delete an SSL certificate you need to set up https on your server.
4. Before you can delete an SSL certificate you need to set up https on your server.
<details>
	<summary>Answer</summary>

	1. Before you can delete an SSL certificate, you need to either rotate SSL certificates or revert from using a custom SSL certificate to using the default CloudFront certificate.

</details>

### Question 207: Which of the following is correct in regards to those security groups?
1. A security group that has port 22 (for SSH) or port 3389 (for RDP) open to your network.
2. A security group that has no ports open to your network.
3. A security group that has only port 3389 (for RDP) open to your network.
4. A security group that has only port 22 (for SSH) open to your network.
<details>
	<summary>Answer</summary>

	1. A security group that has port 22 (for SSH) or port 3389 (for RDP) open to your network.

</details>

### Question 208: How should they architect their solution to achieve these goals?
1. Configure an instance with monitoring software and the elastic network interface (ENI) set to promiscuous mode packet sniffing to see an traffic across the VPC. Configure servers running in the VPC using the host-based 'route' commands to send all traffic through the platform to a scalable virtualized IDS/IP.
2. Create a second VPC and route all traffic from the primary application VPC through the second VPC where the scalable virtualized IDS/IPS platform resides.
3. Configure servers running in the VPC using the host-based 'route' commands to send all traffic through the platform to a scalable virtualized IDS/IP.
4. Configure each host with an agent that collects all network traffic and sends that traffic to the IDS/IPS platform for inspection.
<details>
	<summary>Answer</summary>

	3. Configure servers running in the VPC using the host-based 'route' commands to send all traffic through the platform to a scalable virtualized IDS/IP.

</details>

### Question 209: What is an effective method to mitigate this?
1. Remove public read access and use signed URLs with expiry dates.
2. Use CloudFront distributions for static content.
3. Block the IPs of the offending websites in Security Groups.
4. Store photos on an EBS volume of the web server.
<details>
	<summary>Answer</summary>

	1. Remove public read access and use signed URLs with expiry dates.

</details>

### Question 210: Which of the following is not a true statement relating to the performance of your EBS volumes?
1. Frequent snapshots provide a higher level of data durability and they will not degrade the performance of your application while the snapshot is in progress.
2. General Purpose (SSD) and Provisioned IOPS (SSD) volumes have a throughput limit of 128 MB/s per volume.
3. There is a relationship between the maximum performance of your EBS volumes, the amount of I/O you are driving to them, and the amount of time it takes for each transaction to complete.
4. There is a 5 to 50 percent reduction in IOPS when you first access each block of data on a newly created or restored EBS volume.
<details>
	<summary>Answer</summary>

	1. Frequent snapshots provide a higher level of data durability and they will not degrade the performance of your application while the snapshot is in progress.

</details>

### Question 211: Changes to the backup window take effect [...].
1. from the next billing cycle.
2. after 30 minutes.
3. immediately.
4. after 24 hours.
<details>
	<summary>Answer</summary>

	3. immediately.

</details>

### Question 212: Location of Instances are [...].
1. regional.
2. based on Availability Zone.
3. global.
<details>
	<summary>Answer</summary>

	2. based on Availability Zone.

</details>

### Question 213: You log in to IAM on your AWS console and notice the following message. 'Delete your root access keys.' Why do you think IAM is requesting this?
1. Because the root access keys will expire as soon as you log out.
2. Because the root access keys expire after 1 week.
3. Because the root access keys are the same for all users.
4. Because they provide unrestricted access to your AWS resources.
<details>
	<summary>Answer</summary>

	4. Because they provide unrestricted access to your AWS resources.

</details>

### Question 214: What is the minimum charge for the data transferred between Amazon RDS and Amazon EC2 Instances in the same Availability Zone?
1. USD 0.10 per GB.
2. No charge. It is free.
3. USD 0.02 per GB
4. USD 0.01 per GB.
<details>
	<summary>Answer</summary>

	2. No charge. It is free.

</details>

### Question 215: In DynamoDB, could you use IAM to grant access to Amazon DynamoDB resources and API actions?
1. In DynamoDB there is no need to grant access.
2. Depended to the type of access.
3. Yes.
4. No.
<details>
	<summary>Answer</summary>

	3. Yes.

</details>

### Question 216: The common use cases for DynamoDB Fine-Grained Access Control (FGAC) are cases in which the end user wants [...].
1. to change the hash keys of the table directly.
2. to check if an IAM policy requires the hash keys of the tables directly.
3. to read or modify any code commit key of the table directly, without a middle-tier service.
4. to read or modify the table directly, without a middle-tier service.
<details>
	<summary>Answer</summary>

	4. to read or modify the table directly, without a middle-tier service.

</details>

### Question 217: What are the initial settings of an user created security group?
1. Allow all inbound traffic and Allow no outbound traffic.
2. Al low no inbound traffic and Al low no outbound traffic.
3. Al low no inbound traffic and Al low all outbound traffic.
4. Allow all inbound traffic and Allow all outbound traffic.
<details>
	<summary>Answer</summary>

	3. Al low no inbound traffic and Al low all outbound traffic.

</details>

### Question 218: Which one of the following answers is not a possible state of Amazon CloudWatch Alarm?
1. INSUFFICIENT_DATA.
2. ALARM.
3. OK.
4. STATUS_CHECK_FAILED.
<details>
	<summary>Answer</summary>

	4. STATUS_CHECK_FAILED.

</details>

### Question 219: [...] let you categorize your EC2 resources in different ways, for example, by purpose, owner, or environment.
1. wildcards.
2. pointers.
3. tags.
4. special filters.
<details>
	<summary>Answer</summary>

	3. tags.

</details>

### Question 220: Which of the below mentioned options is not available when an instance is launched by Auto Scaling with EC2 Classic?
1. Public IP.
2. Elastic IP.
3. Private DNS.
4. Private IP.
<details>
	<summary>Answer</summary>

	2. Elastic IP.

</details>

### Question 221: You have a lot of data stored in the AWS Storage Gateway and your manager has come to you asking about how the billing is calculated, specifically the Virtual Tape Shelf usage. What would be a correct response to this?
1. You are billed for the virtual tape data you store in Amazon Glacier and are billed for the size of the virtual tape.
2. You are billed for the virtual tape data you store in Amazon Glacier and billed for the portion of virtual tape capacity that you use, not for the size of the virtual tape.
3. You are billed for the virtual tape data you store in Amazon S3 and billed for the portion of virtual tape capacity that you use, not for the size of the virtual tape.
4. You are billed for the virtual tape data you store in Amazon S3 and are billed for the size of the virtual tape.
<details>
	<summary>Answer</summary>

	2. You are billed for the virtual tape data you store in Amazon Glacier and billed for the portion of virtual tape capacity that you use, not for the size of the virtual tape.

</details>

### Question 222: True or False: The new DB Instance that is created when you promote a Read Replica retains the backup window period.
1. True.
2. False.
<details>
	<summary>Answer</summary>

	1. True.

</details>

### Question 223: [...] is a fast, flexible, fully managed push messaging service.
1. Amazon SNS.
2. Amazon SES.
3. Amazon SQS.
4. Amazon FPS.
<details>
	<summary>Answer</summary>

	1. Amazon SNS.

</details>

### Question 224: You are tasked with setting up a Linux bastion host for access to Amazon EC2 instances running in your VPC. Only clients connecting from the corporate external public IP address 72.34.51.100 should have SSH access to the host. Which option will meet the customer requirement?
1. Security Group Inbound Rule: Protocol – TCP.
2. Port Range- 22, Source 72.34.51. 100/32.
3. Security Group Inbound Rule: Protocol – UDP, Port Range- 22, Source 72.34.51.100/32.
4. Network ACL Inbound Rule: Protocol – UDP, Port Range- 22, Source 72.34.51.100/32.
5. Network ACL Inbound Rule: Protocol – TCP, Port Range-22, Source 72.34.51.100/0.
<details>
	<summary>Answer</summary>

	1. Security Group Inbound Rule: Protocol – TCP.

</details>

### Question 225: How can you secure data at rest on an EBS volume?
1. Attach the volume to an instance using EC2's SSL interface.
2. Write the data randomly instead of sequentially.
3. Encrypt the volume using the S3 server-side encryption service.
4. Create an IAM policy that restricts read and write access to the volume.
5. Use an encrypted file system on top of the EBS volume.
<details>
	<summary>Answer</summary>

	5. Use an encrypted file system on top of the EBS volume.

</details>

### Question 226: Is there a method in the IAM system to allow or deny access to a specific instance?
1. Only for VPC based instances.
2. Yes.
3. No.
<details>
	<summary>Answer</summary>

	2. Yes.

</details>

### Question 227: Using Amazon IAM, can I give permission based on organizational groups?
1. Yes but only in certain cases.
2. Yes.
3. No.
<details>
	<summary>Answer</summary>

	2. Yes.

</details>

### Question 228: Which services allow the customer to retain full administrative privileges of the underlying EC2 instances? (Choose 2 answers)
1. Amazon Relational Database Service.
2. Amazon Elastic MapReduce.
3. Amazon ElastiCache.
4. Amazon DynamoDB.
5. AWS Elastic Beanstalk.
<details>
	<summary>Answer</summary>

	2. Amazon Elastic MapReduce.
	5. AWS Elastic Beanstalk.

</details>

### Question 229: While launching an RDS DB instance, on which page I can select the Availability Zone?
1. REVIEW.
2. DB INSTANCE DETAILS.
3. MANAGEMENT OPTIONS.
4. ADDITIONAL CONFIGURATION.
<details>
	<summary>Answer</summary>

	4. ADDITIONAL CONFIGURATION.

</details>

### Question 230: You are responsible for a legacy web application whose server environment is approaching end of life. You would like to migrate this application to AWS as quickly as possible, since the application environment currently has the following limitations. The VM's single 10GB VMDK is almost full Me virtual network interface still uses the 10Mbps driver, which leaves your 100Mbps WAN connection completely underutilized. It is currently running on a highly customized. Windows VM within a VMware environment: You do not have me installation media. This is a mission critical application with an RTO (Recovery Time Objective) of 8 hours. RPO (Recovery Point Objective) of 1 hour. How could you best migrate this application to AWS while meeting your business continuity requirements?
1. Use the EC2 VM Import Connector for vCenter to import the VM into EC2.
2. Use Import/Export to import the VM as an ESS snapshot and attach to EC2.
3. Use S3 to create a backup of the VM and restore the data into EC2.
4. Use me ec2-bundle-instance API to Import an Image of the VM into EC2.
<details>
	<summary>Answer</summary>

	1. Use the EC2 VM Import Connector for vCenter to import the VM into EC2.

</details>

### Question 231: You are setting up some EBS volumes for a customer who has requested a setup which includes a RAID (redundant array of inexpensive disks). AWS has some recommendations for RAID setups. Which RAID setup is not recommended for Amazon EBS?
1. RAID 5 only.
2. RAID 5 and RAID 6.
3. RAID 1 only.
4. RAID 1 and RAID 6.
<details>
	<summary>Answer</summary>

	2. RAID 5 and RAID 6.

</details>

### Question 232: Much of your company's data does not need to be accessed often, and can take several hours for retrieval time, so it's stored on Amazon Glacier. However someone within your organization has expressed concerns that his data is more sensitive than the other data, and is wondering whether the high level of encryption that he knows is on S3 is also used on the much cheaper Glacier service. Which of the following statements would be most applicable in regards to this concern?
1. There is no encryption on Amazon Glacier, that's why it is cheaper.
2. Amazon Glacier automatically encrypts the data using AES-128 a lesser encryption method than Amazon S3 but you can change it to AES-256 if you are willing to pay more.
3. Amazon Glacier automatically encrypts the data using AES-256, the same as Amazon S3.
4. Amazon Glacier automatically encrypts the data using AES-128 a lesser encryption method than Amazon S3.
<details>
	<summary>Answer</summary>

	3. Amazon Glacier automatically encrypts the data using AES-256, the same as Amazon S3.

</details>

### Question 233: Can I use Provisioned IOPS with VPC?
1. Only Oracle based RDS.
2. No.
3. Only with MSSQL based RDS.
4. Yes for all RDS instances.
<details>
	<summary>Answer</summary>

	4. Yes for all RDS instances.

</details>

### Question 234: To ensure failover capabilities, consider using a [...] for incoming traffic on a network interface.
1. primary public IP.
2. secondary private IP.
3. secondary public IP.
4. add on secondary IP.
<details>
	<summary>Answer</summary>

	2. secondary private IP.

</details>

### Question 235: By default, EBS volumes that are created and attached to an instance at launch are deleted when that instance is terminated. You can modify this behavior by changing the value of the flag [...] to false when you launch the instance.
1. Delete On Termination.
2. Remove On Deletion.
3. Remove On Termination.
4. Terminate On Deletion.
<details>
	<summary>Answer</summary>

	1. Delete On Termination.

</details>

### Question 236: Which AWS service helps this functionality?
1. AWS Simple Queue Service.
2. AWS Simple Notification Service.
3. AWS Simple Workflow Service.
4. AWS Simple Email Service.
<details>
	<summary>Answer</summary>

	1. AWS Simple Queue Service.

</details>

### Question 237: Which of the below statements would be an incorrect response to your customers enquiry?
1. Amazon EMR customers can choose to send data to Amazon S3 using the HTTPS protocol for secure transmission.
2. Amazon S3 provides authentication mechanisms to ensure that stored data is secured against unauthorized access.
3. Every packet sent in the AWS network uses Internet Protocol Security (IPsec).
4. Customers may encrypt the input data before they upload it to Amazon S3.
<details>
	<summary>Answer</summary>

	3. Every packet sent in the AWS network uses Internet Protocol Security (IPsec).

</details>

### Question 238: The one-time payment for Reserved Instances is [...] refundable if the reservation is cancelled.
1. always.
2. in some circumstances.
3. never.
<details>
	<summary>Answer</summary>

	3. never.

</details>

### Question 239: Is it possible to get a history of all EC2 API calls made on your account for security analysis and operational troubleshooting purposes?
1. Yes, by default, the history of your API calls is logged.
2. Yes, you should turn on the CloudTrail in the AWS console.
3. No, you can only get a history of VPC API calls.
4. No, you cannot store history of EC2 API calls on Amazon.
<details>
	<summary>Answer</summary>

	2. Yes, you should turn on the CloudTrail in the AWS console.

</details>

### Question 240: The Trusted Advisor service provides insight regarding which four categories of an AWS account?
1. Security, fault tolerance, high availability, and connectivity.
2. Security, access control, high availability, and performance.
3. Performance, cost optimization, security, and fault tolerance.
4. Performance, cost optimization, access control, and connectivity.
<details>
	<summary>Answer</summary>

	3. Performance, cost optimization, security, and fault tolerance.

</details>

### Question 241: An AWS customer runs a public blogging website. The site users upload two million blog entries a month. The average blog entry size is 200 KB. The access rate to blog entries drops to negligible 6 months after publication and users rarely access a blog entry 1 year after publication. Additionally, blog entries have a high update rate during the first 3 months following publication, this drops to no updates after 6 months. The customer wants to use CloudFront to improve his user's load times. Which of the following recommendations would you make to the customer?
1. Duplicate entries into two different buckets and create two separate CloudFront distributions where S3 access is restricted only to CloudFront identity.
2. Create a CloudFront distribution with 'US' Europe price class for US/ Europe users and a different CloudFront distribution with Al l Edge Locations' for the remaining users.
3. Create a CloudFront distribution with S3 access restricted only to the CloudFront identity and partition the blog entry's location in S3 according to the month it was uploaded to be used withCloudFront behaviors.
4. Create a CloudFronl distribution with Restrict Viewer Access Forward Query string set to true and minimum TTL of 0.
<details>
	<summary>Answer</summary>

	3. Create a CloudFront distribution with S3 access restricted only to the CloudFront identity and partition the blog entry's location in S3 according to the month it was uploaded to be used withCloudFront behaviors.

</details>

### Question 242: Your supervisor has asked you to build a simple file synchronization service for your department. He doesn't want to spend too much money and he wants to be notified of any changes to files by email. What do you think would be the best Amazon service to use for the email solution?
1. Amazon SES.
2. Amazon CloudSearch.
3. Amazon SWF.
4. Amazon AppStream.
<details>
	<summary>Answer</summary>

	1. Amazon SES.

</details>

### Question 243: What are the Amazon EC2 API tools?
1. They don't exist. The Amazon EC2 AMI tools, instead, are used to manage permissions.
2. Command-line tools to the Amazon EC2 web service.
3. They are a set of graphical tools to manage EC2 instances.
4. They don't exist. The Amazon API tools are a client interface to Amazon Web Services.
<details>
	<summary>Answer</summary>

	2. Command-line tools to the Amazon EC2 web service.

</details>

### Question 244: Your customer wishes to deploy an enterprise application to AWS which will consist of several web servers, several application servers and a small (50GB) Oracle database information is stored, both in the database and the file systems of the various servers. The backup system must support database recovery whole server and whole disk restores, and individual file restores with a recovery time of no more than two hours. They have chosen to use RDS Oracle as the database. Which backup architecture will meet these requirements?
1. Backup RDS using automated daily DB backups Backup the EC2 instances using AMIs and supplement with file-level backup to S3 using traditional enterprise backup software to provide file level restore.
2. Backup RDS using a Multi-AZ Deployment Backup the EC2 instances using Amis, and supplement by copying file system data to S3 to provide file-level restore.
3. Backup RDS using automated daily DB backups Backup the EC2 instances using EBS snapshots and supplement with file-level backups to Amazon Glacier using traditional enterprise backup software to provide file-level restore.
4. Backup RDS database to S3 using Oracle RMAN Backup the EC2 instances using Amis, and supplement with EBS snapshots for individual volume restore.
<details>
	<summary>Answer</summary>

	1. Backup RDS using automated daily DB backups Backup the EC2 instances using AMIs and supplement with file-level backup to S3 using traditional enterprise backup software to provide file level restore.

</details>

### Question 245: You are architecting a highly-scalable and reliable web application which will have a huge amount of content. You have decided to use Cloudfront as you know it will speed up distribution of your static and dynamic web content and know that Amazon CloudFront integrates with Amazon CloudWatch metrics so that you can monitor your web application. Because you live in Sydney you have chosen the the Asia Pacific (Sydney) region in the AWS console. However you have set up this up but no CloudFront metrics seem to be appearing in the CloudWatch console. What is the most likely reason from the possible choices below for this?
1. Metrics for CloudWatch are available only when you choose the same region as the application you are monitoring.
2. You need to pay for CloudWatch for it to become active.
3. Metrics for CloudWatch are available only when you choose the US East (Virginia).
4. Metrics for CloudWatch are not available for the Asia Pacific region as yet.
<details>
	<summary>Answer</summary>

	3. Metrics for CloudWatch are available only when you choose the US East (Virginia).

</details>

### Question 246: Is the SQL Server Audit feature supported in the Amazon RDS SQL Server engine?
1. Yes.
2. No.
<details>
	<summary>Answer</summary>

	2. No.

</details>

### Question 247: What is the command line instruction for running the remote desktop client in Windows?
1. desk.cpl.
2. mstsc.
<details>
	<summary>Answer</summary>

	2. mstsc.

</details>

### Question 248: Which of the following cannot be used in Amazon EC2 to control who has access to specific Amazon EC2 instances?
1. Security Groups.
2. IAM System.
3. SSH keys.
4. Windows passwords.
<details>
	<summary>Answer</summary>

	2. IAM System.

</details>

### Question 249: What is the charge for the data transfer incurred in replicating data between your primary and standby?
1. Same as the standard data transfer charge.
2. Double the standard data transfer charge.
3. No charge. It is free.
4. Half of the standard data transfer charge.
<details>
	<summary>Answer</summary>

	3. No charge. It is free.

</details>

### Question 250: You have a load balancer configured for VPC, and all back-end Amazon EC2 instances are in service. However, your web browser times out when connecting to the load balancer's DNS name. Which options are probable causes of this behavior? (Choose 2 answers)
1. The load balancer was not configured to use a public subnet with an Internet gateway configured.
2. The Amazon EC2 instances do not have a dynamically allocated private IP address.
3. The security groups or network ACLs are not property configured for web traffic.
4. The load balancer is not configured in a private subnet with a NAT instance.
5. The VPC does not have a VGW configured.
<details>
	<summary>Answer</summary>

	1. The load balancer was not configured to use a public subnet with an Internet gateway configured.
	3. The security groups or network ACLs are not property configured for web traffic.

</details>

### Question 251: Resources that are created in AWS are identified by a unique identifier called an
1. Amazon Resource Number.
2. Amazon Resource Nametag.
3. Amazon Resource Name.
4. Amazon Resource Namespace.
<details>
	<summary>Answer</summary>

	3. Amazon Resource Name.

</details>

### Question 252: What are the two types of licensing options available for using Amazon RDS for Oracle?
1. BYOL and Enterprise License.
2. BYOL and License Included.
3. Enterprise License and License Included.
4. Role based License and License Included.
<details>
	<summary>Answer</summary>

	2. BYOL and License Included.

</details>

### Question 253: In AWS, which security aspects are the customer's responsibility? (Choose 4 answers)
1. Security Group and ACL (Access Control List) settings.
2. Decommissioning storage devices.
3. Patch management on the EC2 instance's operating system.
4. Life-cycle management of IAM credentials.
5. Controlling physical access to compute resources.
6. Encryption of EBS (Elastic Block Storage) volumes.
<details>
	<summary>Answer</summary>

	1. Security Group and ACL (Access Control List) settings.
	3. Patch management on the EC2 instance's operating system.
	4. Life-cycle management of IAM credentials.
	6. Encryption of EBS (Elastic Block Storage) volumes.

</details>

### Question 254: You have a web application running on six Amazon EC2 instances, consuming about 45% of resources on each instance. You are using auto-scaling to make sure that six instances are running at all times. The number of requests this application processes is consistent and does not experience spikes. The application is critical to your business and you want high availability at all times. You want the load to be distributed evenly between all instances. You also want to use the same Amazon Machine Image (AMI) for all instances. Which of the following architectural choices should you make?
1. Deploy 6 EC2 instances in one Availability Zone and use Amazon Elastic Load Balancer.
2. Deploy 3 EC2 instances in one region and 3 in another region and use Amazon Elastic Load Balancer.
3. Deploy 3 EC2 instances in one Availability Zone and 3 in another Availability Zone and use Amazon Elastic Load Balancer.
4. Deploy 2 EC2 instances in three regions and use Amazon Elastic Load Balancer.
<details>
	<summary>Answer</summary>

	3. Deploy 3 EC2 instances in one Availability Zone and 3 in another Availability Zone and use Amazon Elastic Load Balancer.

</details>

### Question 255: An ERP application is deployed across multiple AZs in a single region. in the event of failure, the Recovery Time Objective (RTO) must be less than 3 hours, and the Recovery Point Objective (RPO) must be 15 minutes the customer realizes that data corruption occurred roughly 1.5 hours ago. What DR strategy could be used to achieve this RTO and RPO in the event of this kind of failure?
1. Take hourly DB backups to S3, with transaction logs stored in S3 every 5 minutes.
2. Use synchronous database master-slave replication between two Availability Zones.
3. Take hourly DB backups to EC2 Instance store volumes with transaction logs stored in S3 every 5 minutes.
4. Take 15 minute DB backups stored in Glacier with transaction logs stored in S3 every 5 minutes.
<details>
	<summary>Answer</summary>

	1. Take hourly DB backups to S3, with transaction logs stored in S3 every 5 minutes.

</details>

### Question 256: You have been setting up an Amazon Virtual Private Cloud (Amazon VPC) for your company, including setting up subnets. Security is a concern, and you are not sure which is the best security practice for securing subnets in your VPC. Which statement below is correct in describing the protection of AWS resources in each subnet?
1. You can use multiple layers of security, including security groups and network access control lists (ACL).
2. You can only use access control lists (ACL).
3. You don't need any security in subnets.
4. You can use multiple layers of security, including security groups, network access control lists (ACL) and CloudHS.
<details>
	<summary>Answer</summary>

	1. You can use multiple layers of security, including security groups and network access control lists (ACL).

</details>

### Question 257: Amazon EC2 provides a repository of public data sets that can be seamlessly integrated into AWS cloud-based applications. What is the monthly charge for using the public data sets?
1. A 1 time charge of 10$ for all the datasets.
2. 1$ per dataset per month.
3. 10$ per month for all the datasets.
4. There is no charge for using the public data sets.
<details>
	<summary>Answer</summary>

	4. There is no charge for using the public data sets.

</details>

### Question 258: [...] embodies the 'share-nothing' architecture and essentially involves breaking a large database into several smaller databases. Common ways to split a database include: 1. Splitting tables that are not joined in the same query onto different hosts or 2. Duplicating a table across multiple hosts and then using a hashing algorithm to determine which host receives a given update.
1. $harding.
2. Fai lure recovery.
3. Federation.
4. DOL operations.
<details>
	<summary>Answer</summary>

	1. $harding.

</details>

### Question 259: After deploying a new website for a client on AWS, he asks if you can set it up so that if it fails it can be automatically redirected to a backup website that he has stored on a dedicated server elsewhere. You are wondering whether Amazon Route 53 can do this. Which statement below is correct in regards to Amazon Route 53?
1. Amazon Route 53 can't help detect an outage. You need to use another service.
2. Amazon Route 53 can help detect an outage of your website and redirect your end users to alternate locations.
3. Amazon Route 53 can help detect an outage of your website but can't redirect your end users to alternate locations.
4. Amazon Route 53 can't help detect an outage of your website, but can redirect your end users to alternate locations.
<details>
	<summary>Answer</summary>

	2. Amazon Route 53 can help detect an outage of your website and redirect your end users to alternate locations.

</details>

### Question 260: Your company plans to host a large donation website on Amazon Web Services (AWS). You anticipate a large and undetermined amount of traffic that will create many database writes. To be certain that you do not drop any writes to a database hosted on AWS. Which service should you use?
1. Amazon RDS with provisioned IOPS up to the anticipated peak write throughput.
2. Amazon Simple Queue Service (SOS) for capturing the writes and draining the queue to write to the database.
3. Amazon ElastiCache to store the writes until the writes are committed to the database.
4. Amazon DynamoDB with provisioned write throughput up to the anticipated peak write throughput.
<details>
	<summary>Answer</summary>

	2. Amazon Simple Queue Service (SOS) for capturing the writes and draining the queue to write to the database.

</details>

### Question 261: You have set up an Auto Scaling group. The cool down period for the Auto Scaling group is 7 minutes. The first instance is launched after 3 minutes, while the second instance is launched after 4 minutes. How many minutes after the first instance is launched will Auto Scaling accept another scaling activity request?
1. 11 minutes.
2. 7 minutes.
3. 10 minutes.
4. 14 minutes.
<details>
	<summary>Answer</summary>

	1. 11 minutes.

</details>

### Question 262: You are migrating a legacy client-server application to AWS. The application responds to a specific DNS domain (e.g. <www.example.com>) and has a 2-tier architecture, with multiple application servers and a database server. Remote clients use TCP to connect to the application servers. The application servers need to know the IP address of the clients in order to function properly and are currently taking that information from the TCP socket. A Multi-AZ RDS MySQL instance will be used for the database. During the migration you can change the application code, but you have to file a change request. How would you implement the architecture on AWS in order to maximize scalability and high availability?
1. File a change request to implement Alias Resource support in the application. Use Route 53 Alias Resource Record to distribute load on two application servers in different AZs.
2. File a change request to implement Latency Based Routing support in the application. Use Route 53 with Latency Based Routing enabled to distribute load on two application servers in different AZs.
3. File a change request to implement Cross-Zone support in the application. Use an ELB with a TCP Listener and Cross-Zone Load Balancing enabled, two application servers in different AZs.
4. File a change request to implement Proxy Protocol support in the application. Use an ELB with a TCP Listener and Proxy Protocol enabled to distribute load on two application servers in different AZs.
<details>
	<summary>Answer</summary>

	4. File a change request to implement Proxy Protocol support in the application. Use an ELB with a TCP Listener and Proxy Protocol enabled to distribute load on two application servers in different AZs.

</details>

### Question 263: Can I test my DB Instance against a new version before upgrading?
1. Yes.
2. No.
3. Only in VPC.
<details>
	<summary>Answer</summary>

	1. Yes.

</details>

### Question 264: Your system recently experienced down time during the troubleshooting process. You found that a new administrator mistakenly terminated several production EC2 instances. Which of the following strategies will help prevent a similar situation in the future? The administrator still must be able to: Launch, start stop, and terminate development resources. Launch and start production instances.
1. Create an IAM user, which is not allowed to terminate instances by leveraging production EC2 termination protection.
2. Leverage resource based tagging along with an IAM user, which can prevent specific users from terminating production EC2 resources.
3. Leverage EC2 termination protection and multi-factor authentication, which together require users to authenticate before terminating EC2 instances.
4. Create an IAM user and apply an IAM role which prevents users from terminating production EC2 instances.
<details>
	<summary>Answer</summary>

	2. Leverage resource based tagging along with an IAM user, which can prevent specific users from terminating production EC2 resources.

</details>

### Question 265: You have just set up a large site for a client which involved a huge database which you set up with Amazon RDS to run as a Multi-AZ deployment. You now start to worry about what will happen if the database instance fails. Which statement best describes how this database will function if there is a database failure?
1. Updates to your DB Instance are synchronously replicated across Availability Zones to the standby in order to keep both in sync and protect your latest database updates against DB Instance failure.
2. Your database will not resume operation without manual administrative intervention.
3. Updates to your DB Instance are asynchronously replicated across Availability Zones to the standby in order to keep both in sync and protect your latest database updates against DB Instance failure.
4. Updates to your DB Instance are synchronously replicated across S3 to the standby in order to keep both in sync and protect your latest database updates against DB Instance failure.
<details>
	<summary>Answer</summary>

	1. Updates to your DB Instance are synchronously replicated across Availability Zones to the standby in order to keep both in sync and protect your latest database updates against DB Instance failure.

</details>

### Question 266: Your company has an on-premises multi-tier PHP web application, which recently experienced downtime due to a large burst in web traffic due to a company announcement Over the coming days, you are expecting similar announcements to drive similar unpredictable bursts, and are looking to find ways to quickly improve your infrastructures ability to handle unexpected increases in traffic. The application currently consists of 2 tiers a web tier which consists of a load balancer and several Linux Apache web servers as well as a database tier which hosts a Linux server hosting a MySQLdatabase. Which scenario below will provide full site functionality, while helping to improve the ability of your application in the short timeframe required?
1. Failover environment: Create an S3 bucket and configure it for website hosting. Migrate your DNS to Route 53 using zone file import, and leverage Route 53 DNS failover to failover to the S3 hosted website.
2. Hybrid environment: Create an AMI, which can be used to launch web servers in EC2. Create an Auto Scaling group, which uses the AMI to scale the web tier based on incoming traffic. LeverageElastic Load Balancing to balance traffic between on-premises web servers and those hosted in AWS.
3. Offload traffic from on-premises environment: Setup a CloudFront distribution, and configure CloudFront to cache objects from a custom origin. Choose to customize your object cache behavior, and select a TIL that objects should exist in cache.
4. Migrate to AWS: Use VM Import/Export to quickly convert an on-premises web server to an AMI.
5. Create an Auto Scaling group, which uses the imported AMI to scale the web tier based on incoming traffic. Create an RDS read replica and setup replication between the RDS instance and on-premises MySQL server to migrate the database.
<details>
	<summary>Answer</summary>

	3. Offload traffic from on-premises environment: Setup a CloudFront distribution, and configure CloudFront to cache objects from a custom origin. Choose to customize your object cache behavior, and select a TIL that objects should exist in cache.

</details>

### Question 267: When using consolidated billing there are two account types. What are they?
1. Paying account and Linked account.
2. Parent account and Child account.
3. Main account and Sub account.
4. Main account and Secondary account.
<details>
	<summary>Answer</summary>

	1. Paying account and Linked account.

</details>

### Question 268: You have a periodic Image analysis application that gets some files in Input analyzes them and tor each file writes some data in output to a ten file the number of files in input per day is high and concentrated in a few hours of the day. Currently you have a server on EC2 with a large EBS volume that hosts the input data and the results it takes almost 20 hours per day to complete the process What services could be used to reduce the elaboration time and improve the availability of the solution?
1. Amazon S3 to store 1/0 files. SQS to distribute elaboration commands to a group of hosts working in parallel. Auto scaling to dynamically size the group of hosts depending on the length of the SQS queue.
2. EBS with Provisioned IOPS (PIOPS) to store 1/0 files. SNS to distribute elaboration commands to a group of hosts working in parallel Auto Scaling to dynamically size the group of hosts depending on the number of SNS notifications.
3. Amazon S3 to store 1/0 files, SNS to distribute evaporation commands to a group of hosts working in parallel. Auto scaling to dynamically size the group of hosts depending on the number of SNS notifications.
4. EBS with Provisioned IOPS (PIOPS) to store 1/0 files SOS to distribute elaboration commands to a group of hosts working in parallel Auto Scaling to dynamically size the group ot hosts depending on the length of the SQS queue.
<details>
	<summary>Answer</summary>

	4. EBS with Provisioned IOPS (PIOPS) to store 1/0 files SOS to distribute elaboration commands to a group of hosts working in parallel Auto Scaling to dynamically size the group ot hosts depending on the length of the SQS queue.

</details>

### Question 269: While controlling access to Amazon EC2 resources, which of the following acts as a firewall that controls the traffic allowed to reach one or more instances?
1. A security group.
2. An instance type.
3. A storage cluster.
4. An object.
<details>
	<summary>Answer</summary>

	1. A security group.

</details>

### Question 270: The base URI for all requests for instance metadata is [...].
1. <http://254.169.169.254/latest/>.
2. <http://169.169.254.254/latest/>.
3. <http://127.0.0.1/latest/>.
4. <http://169.254.169.254/latest/>.
<details>
	<summary>Answer</summary>

	4. <http://169.254.169.254/latest/>.

</details>

### Question 271: While using the EC2 GET requests as URLs, the [...] is the URL that serves as the entry point for the web service.
1. token.
2. endpoint.
3. action.
4. None of these.
<details>
	<summary>Answer</summary>

	2. endpoint.

</details>

### Question 272: A user is planning to launch a scalable web application. Which of the below mentioned options will not affect the latency of the application?
1. Region.
2. Provisioned IOPS.
3. Availability Zone.
4. Instance size.
<details>
	<summary>Answer</summary>

	2. Provisioned IOPS.

</details>

### Question 273: Your firm has uploaded a large amount of aerial image data to S3 in the past, in your on-premises environment, you used a dedicated group of servers to oaten process this data and used Rabbit MQAnopen source messaging system to get job information to the servers. Once processed the data would go to tape and be shipped offsite. Your manager told you to stay with the current design, and leverage AWS archival storage and messaging services to minimize cost. Which is correct?
1. Use SQS for passing job messages use Cloud Watch alarms to terminate EC2 worker instances when they become idle. Once data is processed, change the storage class of the S3 objects to Reduced Redundancy Storage.
2. Setup Auto-Scaled workers triggered by queue depth that use spot instances to process messages in SOS Once data is processed,
3. Change the storage class of the S3 objects to Reduced Redundancy Storage. Setup Auto-Scaled workers triggered by queue depth that use spot instances to process messages in SQS Once data is processed, change the storage class of the S3 objects to Glacier.
4. Use SNS to pass job messages use Cloud Watch alarms to terminate spot worker instances when they become idle. Once data is processed, change the storage class of the S3 object to Glacier.
<details>
	<summary>Answer</summary>

	4. Use SNS to pass job messages use Cloud Watch alarms to terminate spot worker instances when they become idle. Once data is processed, change the storage class of the S3 object to Glacier.

</details>

### Question 274: A user has launched 10 EC2 instances inside a placement group. Which of the below mentioned statements is true with respect to the placement group?
1. All instances must be in the same AZ.
2. All instances can be across multiple regions.
3. The placement group cannot have more than 5 instances.
4. All instances must be in the same region.
<details>
	<summary>Answer</summary>

	1. All instances must be in the same AZ.

</details>

### Question 275: A user has created a CloudFormation stack. The stack creates AWS services, such as EC2 instances, ELB, AutoScaling, and RDS. While creating the stack it created EC2, ELB and AutoScaling but failed to create RDS. What will CloudFormation do in this scenario?
1. Rollback all the changes and terminate all the created services.
2. It will wait for the user's input about the error and correct the mistake after the input.
3. CloudFormation can never throw an error after launching a few services since it verifies all the steps before launching.
4. It will warn the user about the error and ask the user to manually create RDS.
<details>
	<summary>Answer</summary>

	1. Rollback all the changes and terminate all the created services.

</details>

### Question 276: You have been asked to design the storage layer for an application. The application requires disk performance of at least 100,000 IOPS. In addition, the storage layer must be able to survive the loss of an individual disk, EC2 instance, or Availability Zone without any data loss. The volume you provide must have a capacity of at least 3 TB. Which of the following designs will meet these objectives?
1. Instantiate a c3.8xlarge instance in us-east-1. Provision 4x1TB EBS volumes, attach them to the instance, and configure them as a single RAID 5 volume. Ensure that EBS snapshots are performed every 15 minutes.
2. Instantiate a c3.8xlarge instance in us-east-1. Provision 3xlTB EBS volumes, attach them to the Instance, and configure them as a single RAID 0 volume. Ensure that EBS snapshots are performed every 15 minutes.
3. Instantiate an i2.8xlarge instance in us-east-1a. Create a RAID 0 volume using the four 800GB SSD ephemeral disks provided with the instance. Provision 3x1TB EBS volumes, attach them to the instance, and configure them as a second RAID 0 volume. Configure synchronous, block-level replication from the ephemeral-backed volume to the EBS-backed volume.
4. Instantiate a c3.8xlarge instance in us-east-1. Provision an AWS Storage Gateway and configure it for 3 TB of storage and 100,000 IOPS. Attach the volume to the instance.
5. Instantiate an i2.8xlarge instance in us-east-1a. Create a RAID 0 volume using the four 800GB SSD ephemeral disks provided with the instance. Configure synchronous, block-level replication to an identically configured instance in us-east-1b.
<details>
	<summary>Answer</summary>

	5. Instantiate an i2.8xlarge instance in us-east-1a. Create a RAID 0 volume using the four 800GB SSD ephemeral disks provided with the instance. Configure synchronous, block-level replication to an identically configured instance in us-east-1b.

</details>

### Question 277: A company is preparing to give AWS Management Console access to developers Company policy mandates identity federation and role-based access control. Roles are currently assigned using groups in the corporate Active Directory. What combination of the following will give developers access to the AWS console? (Choose 2 answers)
1. AWS Directory Service AD Connector.
2. AWS Directory Service Simple AD.
3. AWS Identity and Access Management groups.
4. AWS identity and Access Management roles.
5. AWS identity and Access Management users.
<details>
	<summary>Answer</summary>

	1. AWS Directory Service AD Connector.
	4. AWS identity and Access Management roles.

</details>

### Question 278: Your startup wants to implement an order fulfillment process for selling a personalized gadget that needs an average of 3-4 days to produce with some orders taking up to 6 months you expect 10orders per day on your first day. 1000 orders per day after 6 months and 10,000 orders after 12 months. Orders coming in are checked for consistency men dispatched to your manufacturing plant for production quality control packaging shipment and payment processing If the product does not meet the quality standards at any stage of the process employees may force the process to repeat a step Customers are notified via email about order status and any critical issues with their orders such as payment failure. Your case architecture includes AWS Elastic Beanstalk for your website with an RDS MySQL instance for customer data and orders. How can you implement the order fulfillment process while making sure that the emails are delivered reliably?
1. Add a business process management application to your Elastic Beanstalk app servers and re-use the ROS database for tracking order status use one of the Elastic Beanstalk instances to send emails to customers.
2. Use SWF with an Auto Scaling group of activity workers and a decider instance in another Auto Scaling group with min/max=l Use the decider instance to send emails to customers.
3. Use SWF with an Auto Scaling group of activity workers and a decider instance in another Auto Scaling group with min/max=l use SES to send emails to customers.
4. Use an SQS queue to manage all process tasks Use an Auto Scaling group of EC2 Instances that poll the tasks and execute them. Use SES to send emails to customers.
<details>
	<summary>Answer</summary>

	3. Use SWF with an Auto Scaling group of activity workers and a decider instance in another Auto Scaling group with min/max=l use SES to send emails to customers.

</details>

### Question 279: A, [...] is an individual, system, or application that interacts with AWS programmatically.
1. user.
2. AWS Account.
3. group.
4. role.
<details>
	<summary>Answer</summary>

	1. user.

</details>

### Question 280: A user is accessing an EC2 instance on the SSH port for IP 10.20.30.40. Which one is a secure way to configure that the instance can be accessed only from this IP?
1. In the security group, open port 22 for IP 10.20.30.40.
2. In the security group, open port 22 for IP 10.20.30.40/32.
3. In the security group, open port 22 for IP 10.20.30.40/24.
4. In the security group, open port 22 for IP 10.20.30.40/0.
<details>
	<summary>Answer</summary>

	2. In the security group, open port 22 for IP 10.20.30.40/32.

</details>

### Question 281: Read Replicas require a transactional storage engine and are only supported for the [...] storage engine.
1. OracleISAM.
2. MSSQLDB.
3. InnoDB.
4. MyISAM.
<details>
	<summary>Answer</summary>

	3. InnoDB.

</details>

### Question 282: What is Amazon Glacier?
1. You mean Amazon 'Iceberg': it's a low-cost storage service.
2. A security tool that allows to 'freeze' an EBS volume and perform computer forensics on it.
3. A low-cost storage service that provides secure and durable storage for data archiving and backup.
4. It's a security tool that allows to 'freeze' an EC2 instance and perform computer forensics on it.
<details>
	<summary>Answer</summary>

	3. A low-cost storage service that provides secure and durable storage for data archiving and backup.

</details>

### Question 283: You have a content management system running on an Amazon EC2 instance that is approaching 100% CPU utilization. Which option will reduce load on the Amazon EC2 instance?
1. Create a load balancer, and register the Amazon EC2 instance with it.
2. Create a CloudFront distribution, and configure the Amazon EC2 instance as the origin.
3. Create an Auto Scaling group from the instance using the Create AutoScaling Group action.
4. Create a launch configuration from the instance using the Create launch Configuration action.
<details>
	<summary>Answer</summary>

	2. Create a CloudFront distribution, and configure the Amazon EC2 instance as the origin.

</details>

### Question 284: Can I initiate a 'forced failover' for my MySQL Multi-AZ DB Instance deployment?
1. Only in certain regions.
2. Only in VPC.
3. Yes.
4. No.
<details>
	<summary>Answer</summary>

	1. Only in certain regions.

</details>

### Question 285: When controlling access to Amazon EC2 resources, each Amazon EBS Snapshot has a [...] attribute that controls which AWS accounts can use the snapshot.
1. createVolumePermission.
2. LaunchPermission.
3. SharePermission.
4. RequestPermission.
<details>
	<summary>Answer</summary>

	1. createVolumePermission.

</details>

### Question 286: You have decided to change the instance type for instances running in your application tier that is using Auto Scaling. In which area below would you change the instance type definition?
1. Auto Scaling policy.
2. Auto Scaling group.
3. Auto Scaling tags.
4. Auto Scaling launch configuration.
<details>
	<summary>Answer</summary>

	4. Auto Scaling launch configuration.

</details>

### Question 287: Which of the following statements is true of creating a launch configuration using an EC2 instance?
1. The launch configuration can be created only using the Query APIs.
2. Auto Scaling automatically creates a launch configuration directly from an EC2 instance.
3. A user should manually create a launch configuration before creating an Auto Scaling group.
4. The launch configuration should be created manually from the AWS CL.
<details>
	<summary>Answer</summary>

	2. Auto Scaling automatically creates a launch configuration directly from an EC2 instance.

</details>

### Question 288: Your company has multiple IT departments, each with their own VPC. Some VPCs are located within the same AWS account, and others in a different AWS account. You want to peer together all VPCs to enable the IT departments to have full access to each others' resources. There are certain limitations placed on VPC peering. Which of the following statements is incorrect in relation to VPC peering?
1. Private DNS values cannot be resolved between instances in peered VPCs.
2. You can have up to 3 VPC peering connections between the same two VPCs at the same time.
3. You cannot create a VPC peering connection between VPCs in different regions.
4. You have a limit on the number active and pending VPC peering connections that you can have per VP.
<details>
	<summary>Answer</summary>

	2. You can have up to 3 VPC peering connections between the same two VPCs at the same time.

</details>

### Question 289: A gaming company comes to you and asks you to build them infrastructure for their site. They are not sure how big they will be as with all start ups they have limited money and big ideas. What they do tell you is that if the game becomes successful, like one of their previous games, it may rapidly grow to millions of users and generate tens (or even hundreds) of thousands of writes and reads per second. After considering all of this, you decide that they need a fully managed NoSQL database service that provides fast and predictable performance with seamless scalability. Which of the following databases do you think would best fit their needs?
1. Amazon DynamoDB.
2. Amazon Redshift.
3. Any non-relational database.
4. Amazon SimpleDB.
<details>
	<summary>Answer</summary>

	1. Amazon DynamoDB.

</details>

### Question 290: A/An [...] acts as a firewall that controls the traffic allowed to reach one or more instances.
1. security group.
2. ACL.
3. IAM.
4. private IP Addresses.
<details>
	<summary>Answer</summary>

	1. security group.

</details>

### Question 291: Your manager has just given you access to multiple VPN connections that someone else has recently set up between all your company's offices. She needs you to make sure that the communication between the VPNs is secure. Which of the following services would be best for providing a low-cost hub-and-spoke model for primary or backup connectivity between these remote offices?
1. Amazon CloudFront.
2. AWS Direct Connect.
3. AWS CloudHSM.
4. AWS VPN CloudHub.
<details>
	<summary>Answer</summary>

	4. AWS VPN CloudHub.

</details>

### Question 292: You need to create a management network using network interfaces for a virtual private cloud (VPC) network. Which of the following statements is incorrect pertaining to Best Practices for ConfiguringNetwork Interfaces.
1. You can detach secondary (ethN) network interfaces when the instance is running or stopped. However, you can't detach the primary (eth0) interface.
2. Launching an instance with multiple network interfaces automatically configures interfaces, private IP addresses, and route tables on the operating system of the instance.
3. You can attach a network interface in one subnet to an instance in another subnet in the same VPC, however, both the network interface and the instance must reside in the same Availability Zone.
4. Attaching another network interface to an instance is a valid method to increase or double the network bandwidth to or from the dual-homed instance.
<details>
	<summary>Answer</summary>

	4. Attaching another network interface to an instance is a valid method to increase or double the network bandwidth to or from the dual-homed instance.

</details>

### Question 293: A user has launched 10 EC2 instances inside a placement group. Which of the following statements is true in regards to what ability launching your instances into a VPC instead of EC2-Classic gives you?
1. All of the things listed here.
2. Change security group membership for your instances while they're running.
3. Assign static private IP addresses to your instances that persist across starts and stops.
4. Define network interfaces, and attach one or more network interfaces to your instances.
<details>
	<summary>Answer</summary>

	1. All of the things listed here.

</details>

### Question 294: In the HQ region you run an hourly batch process reading data from every region to compute cross regional reports that are sent by email to all offices this batch process must be completed as fast as possible to quickly optimize logistics how do you build the database architecture in order to meet the requirements'?
1. For each regional deployment, use RDS MySQL with a master in the region and a read replica in the HQ region.
2. For each regional deployment, use MySQL on EC2 with a master in the region and send hourly EBS snapshots to the HQ region.
3. For each regional deployment, use RDS MySQL with a master in the region and send hourly RDS snapshots to the HQ region.
4. For each regional deployment, use MySQL on EC2 with a master in the region and use S3 to copy data files hourly to the HQ region.
5. Use Direct Connect to connect all regional MySQL deployments to the HQ region and reduce network latency for the batch process.
<details>
	<summary>Answer</summary>

	1. For each regional deployment, use RDS MySQL with a master in the region and a read replica in the HQ region.

</details>

### Question 295: What is the average IOPS that the user will get for most of the year as per EC2 SLA if the instance is attached to the EBS optimized instance?
1. 950.
2. 990.
3. 1000.
4. 900.
<details>
	<summary>Answer</summary>

	4. 900.

</details>

### Question 296: You are working with a customer who has 10 TB of archival data that they want to migrate to Amazon Glacier. The customer has a 1-Mbps connection to the Internet. Which service or feature provides the fastest method of getting the data into Amazon Glacier?
1. Amazon Glacier multipart upload.
2. AWS Storage Gateway.
3. VM Import/Export.
4. AWS Import/Export.
<details>
	<summary>Answer</summary>

	1. Amazon Glacier multipart upload.

</details>

### Question 297: Your manager has asked you to set up a public subnet with instances that can send and receive internet traffic, and a private subnet that can't receive traffic directly from the internet, but can initiate traffic to the internet (and receive responses) through a NAT instance in the public subnet. Hence, the following 3 rules need to be allowed: Inbound SSH traffic. Web servers in the public subnet to read and write to MS SQL servers in the private subnet. Inbound RDP traffic from the Microsoft Terminal Services gateway in the public private subnet. What are the respective ports that need to be opened for this?
1. Ports 22, 1433, 3389.
2. Ports 21, 1433, 3389.
3. Ports 25, 1433, 3389.
4. Ports 22, 1343, 3999.
<details>
	<summary>Answer</summary>

	1. Ports 22, 1433, 3389.

</details>

### Question 298: An EC2 instance is connected to an ENI (Elastic Network Interface) in one subnet. What happens to the data on an instance if the instance reboots (intentionally or unintentionally)?
1. Data will be lost.
2. Data persists.
<details>
	<summary>Answer</summary>

	2. Data persists.

</details>

### Question 299: Please select the Amazon EC2 resource which can be tagged.
1. Key pairs.
2. Elastic IP addresses.
3. Placement groups.
4. Amazon EBS snapshots.
<details>
	<summary>Answer</summary>

	3. Placement groups.

</details>

### Question 300: Without [...] you must either create multiple AWS accounts-each with its own billing and subscriptions to AWS products-or your employees must share the security credentials of a single AWS account.
1. Amazon RDS.
2. Amazon Glacier.
3. Amazon EMR.
4. Amazon IAM.
<details>
	<summary>Answer</summary>

	4. Amazon IAM.

</details>

### Question 301: An EC2 instance is connected to an ENI (Elastic Network Interface) in one subnet. What happens when you attach an ENI of a different subnet to this EC2 instance?
1. The EC2 instance follows the rules of the older subnet.
2. The EC2 instance follows the rules of both the subnets.
3. Not possible, cannot be connected to 2 ENIs.
4. The EC2 instance follows the rules of the newer subnet.
<details>
	<summary>Answer</summary>

	2. The EC2 instance follows the rules of both the subnets.

</details>

### Question 302: You have deployed a three-tier web application in a VPC with a CIDR block of 10.0.0.0/28. You initially deploy two web servers, two application servers, two database servers and one NAT instance tor a total of seven EC2 instances. The web, application and database servers are deployed across two Availability Zones (AZs). You also deploy an ELB in front of the two web servers, and use Route 53 for DNS Web. Raffle gradually increases in the first few days following the deployment, so you attempt to double the number of instances in each tier of the application to handle the new load unfortunately some of these new instances fail to launch.Which of the following could be the root caused? (Choose 2 answers)
1. AWS reserves the first and the last private IP address in each subnet's CIDR block so you do not have enough addresses left to launch all of the new EC2 instances.
2. The Internet Gateway (IGW) of your VPC has scaled-up, adding more instances to handle the traffic spike, reducing the number of available private IP addresses for new instance launches.
3. The ELB has scaled-up, adding more instances to handle the traffic spike, reducing the number of available private IP addresses for new instance launches.
4. AWS reserves one IP address in each subnet's CIDR block for Route 53 so you do not have enough addresses left to launch all of the new EC2 instances.
5. AWS reserves the first four and the last IP address in each subnet's CIDR block so you do not have enough addresses left to launch all of the new EC2 instances.
<details>
	<summary>Answer</summary>

	3. The ELB has scaled-up, adding more instances to handle the traffic spike, reducing the number of available private IP addresses for new instance launches.
	5. AWS reserves the first four and the last IP address in each subnet's CIDR block so you do not have enough addresses left to launch all of the new EC2 instances.

</details>

### Question 303: Which of the following will cause an immediate DB instance reboot to occur?
1. You change storage type from standard to PIOPS, and Apply Immediately is set to true.
2. You change the DB instance class, and Apply Immediately is set to false.
3. You change a static parameter in a DB parameter group.
4. You change the backup retention period for a DB instance from 0 to a nonzero value or from a nonzero value to 0, and Apply Immediately is set to false.
<details>
	<summary>Answer</summary>

	1. You change storage type from standard to PIOPS, and Apply Immediately is set to true.

</details>

### Question 304: EBS Snapshots occur [...].
1. Asynchronously.
2. Synchronously.
<details>
	<summary>Answer</summary>

	1. Asynchronously.

</details>

### Question 305: You are tasked with moving a legacy application from a virtual machine running Inside your datacenter to an Amazon VPC Unfortunately this app requires access to a number of on-premises services and no one who configured the app still works for your company. Even worse there's no documentation for it. What will allow the application running inside the VPC to reach back and access its internal dependencies without being reconfigured? (Choose 3 answers)
1. An AWS Direct Connect link between the VPC and the network housing the internal services.
2. An Internet Gateway to allow a VPN connection.
3. An Elastic IP address on the VPC instance.
4. An IP address space that does not conflict with the one on-premises.
5. Entries in Amazon Route 53 that allow the Instance to resolve its dependencies' IP addresses.
6. A VM Import of the current virtual machine.
<details>
	<summary>Answer</summary>

	1. An AWS Direct Connect link between the VPC and the network housing the internal services.
	4. An IP address space that does not conflict with the one on-premises.
	6. A VM Import of the current virtual machine.

</details>

### Question 306: A company needs to deploy services to an AWS region which they have not previously used. The company currently has an AWS identity and Access Management (IAM) role for the Amazon EC2 instances, which permits the instance to have access to Amazon DynamoDB. The company wants their EC2 instances in the new region to have the same privileges. How should the company achieve this?
1. Create a new IAM role and associated policies within the new region.
2. Assign the existing IAM role to the Amazon EC2 instances in the new region.
3. Copy the IAM role and associated policies to the new region and attach it to the instances.
4. Create an Amazon Machine Image (AMI) of the instance and copy it to the desired region using the AMI Copy feature.
<details>
	<summary>Answer</summary>

	2. Assign the existing IAM role to the Amazon EC2 instances in the new region.

</details>

### Question 307: If you want to launch Amazon Elastic Compute Cloud (EC2) instances and assign each instance a predetermined private IP address you should:
1. Launch the instance from a private Amazon Machine Image (AMI).
2. Assign a group of sequential Elastic IP address to the instances.
3. Launch the instances in the Amazon Virtual Private Cloud (VPC).
4. Launch the instances in a Placement Group.
5. Use standard EC2 instances since each instance gets a private Domain Name Service (DNS) already.
<details>
	<summary>Answer</summary>

	2. Assign a group of sequential Elastic IP address to the instances.

</details>

### Question 308: When automatic failover occurs, Amazon RDS will emit a DB Instance event to inform you that automatic failover occurred. You can use the [...] to return information about events related to your DB Instance.
1. FetchFailure.
2. DescriveFailure.
3. DescribeEvents.
4. FetchEvents.
<details>
	<summary>Answer</summary>

	3. DescribeEvents.

</details>

### Question 309: You have a Business support plan with AWS. One of your EC2 instances is running Microsoft Windows Server 2008 R2 and you are having problems with the software. Can you receive support from AWS for this software?
1. Yes.
2. No, AWS does not support any third-party software.
3. No, Microsoft Windows Server 2008 R2 is not supported.
4. No, you need to be on the enterprise support plan.
<details>
	<summary>Answer</summary>

	1. Yes.

</details>

### Question 310: A newspaper organization has a on-premises application which allows the public to search its back catalogue and retrieve individual newspaper pages via a website written in Java They have scanned the old newspapers into JPEGs (approx 17TB) and used Optical Character Recognition (OCR) to populate a commercial search product. The hosting platform and software are now end of life and the organization wants to migrate Its archive to AWS and produce a cost efficient architecture and still be designed for availability and durability. Which is the most appropriate?
1. Use S3 with reduced redundancy to store and serve the scanned files, install the commercial search application on EC2 Instances and configure with auto-scaling and an Elastic Load Balancer.
2. Model the environment using CloudFormation use an EC2 instance running Apache webserver and an open source search application, stripe multiple standard EB5 volumes together to store the JPEGs and search index.
3. Use S3 with standard redundancy to store and serve the scanned files, use Cloud5earch for query processing, and use Elastic Beanstalk to host the website across multiple Availability Zones.
4. Use a single-AZ RD5 My5QL instance to store the search index 33d the JPEG images use an EC2 instance to serve the website and translate user queries into 5Q
5. Use a CloudFront download distribution to serve the JPEGs to the end users and Install the current commercial search product, along with a Java Container Tor the website on EC2 instances and use Route 53 with DNS round-robin.
<details>
	<summary>Answer</summary>

	3. Use S3 with standard redundancy to store and serve the scanned files, use Cloud5earch for query processing, and use Elastic Beanstalk to host the website across multiple Availability Zones.

</details>

### Question 311: A Provisioned IOPS volume must be at least [...] GB in size.
1. 1.
2. 50.
3. 20.
4. 10.
<details>
	<summary>Answer</summary>

	4. 10.

</details>

### Question 312: In Amazon EC2, while sharing an Amazon EBS snapshot, can the snapshots with AWS Marketplace product codes be public?
1. Yes, but only for US-based providers.
2. Yes, they can be public.
3. No, they cannot be made public.
4. Yes, they are automatically made public by the system.
<details>
	<summary>Answer</summary>

	3. No, they cannot be made public.

</details>

### Question 313: A company has an AWS account that contains three VPCs (Dev, Test, and Prod) in the same region. Test is peered to both Prod and Dev. All VPCs have non-overlapping CIDR blocks. The company wants to push minor code releases from Dev to Prod to speed up time to market. Which of the following options helps the company accomplish this?
1. Create a new peering connection Between Prod and Dev along with appropriate routes.
2. Create a new entry to Prod in the Dev route table using the peering connection as the target.
3. Attach a second gateway to Dev. Add a new entry in the Prod route table identifying the gateway as the target.
4. The VPCs have non-overlapping Cl DR blocks in the same account. The route tables contain local routes for all VPCs.
<details>
	<summary>Answer</summary>

	4. The VPCs have non-overlapping Cl DR blocks in the same account. The route tables contain local routes for all VPCs.

</details>

### Question 314: The [...] service is targeted at organizations with multiple users or systems that use AWS products such as Amazon EC2, Amazon SimpleDB, and the AWS Management Console.
1. Amazon RDS.
2. AWS Integrity Management.
3. AWS Identity and Access Management.
4. Amazon EMR.
<details>
	<summary>Answer</summary>

	3. AWS Identity and Access Management.

</details>

### Question 315: You have just been given a scope for a new client who has an enormous amount of data (petabytes) that he constantly needs analysed. Currently he is paying a huge amount of money for a data warehousing company to do this for him and is wondering if AWS can provide a cheaper solution. Do you think AWS has a solution for this?
1. Yes. Amazon SimpleDB.
2. No. Not presently.
3. Yes. Amazon Redshift.
4. Yes. Your choice of relational AMIs on Amazon EC2 and EBS.
<details>
	<summary>Answer</summary>

	3. Yes. Amazon Redshift.

</details>

### Question 316: You have set up an Elastic Load Balancer (ELB) with the usual default settings, which route each request independently to the application instance with the smallest load. However, someone has asked you to bind a user's session to a specific application instance so as to ensure that all requests coming from the user during the session will be sent to the same application instance. AWS has a feature to do this. What is it called?
1. Connection draining.
2. Proxy protocol.
3. Tagging.
4. Sticky session.
<details>
	<summary>Answer</summary>

	4. Sticky session.

</details>

### Question 317: You have written a CloudFormation template that creates 1 Elastic Load Balancer fronting 2 EC2 Instances. Which section of the template should you edit so that the DNS of the load balancer is returned upon creation of the stack?
1. Resources.
2. Outputs.
3. Parameters.
4. Mappings.
<details>
	<summary>Answer</summary>

	2. Outputs.

</details>

### Question 318: AWS CloudFormation is a service that helps you model and set up your Amazon Web Services resources so that you can spend less time managing those resources and more time focusing on your applications that run in AWS. You create a template that describes all the AWS resources that you want (like Amazon EC2 instances or Amazon RDS DB instances), and AWS CloudFormation takes care of provisioning and configuring those resources for you. What formatting is required for this template?
1. JSON-formatted document.
2. CSS-formatted document.
3. XML-formatted document.
4. HTML-formatted document.
<details>
	<summary>Answer</summary>

	1. JSON-formatted document.

</details>

### Question 319: A user has created an application which will be hosted on EC2. The application makes calls to DynamoDB to fetch certain data. The application is using the DynamoDB SDK to connect with from theEC2 instance. Which of the below mentioned statements is true with respect to the best practice for security in this scenario?
1. The user should create an IAM user with DynamoDB access and use its credentials within the application to connect with DynamoDB.
2. The user should attach an IAM role with DynamoDB access to the EC2 instance.
3. The user should create an IAM role, which has EC2 access so that it will allow deploying the application.
4. The user should create an IAM user with DynamoDB and EC2 access. Attach the user with the application so that it does not use the root account credentials.
<details>
	<summary>Answer</summary>

	2. The user should attach an IAM role with DynamoDB access to the EC2 instance.

</details>

### Question 320: After setting up an EC2 security group with a cluster of 20 EC2 instances, you find an error in the security group settings. You quickly make changes to the security group settings. When will the changes to the settings be effective?
1. The settings will be effective immediately for all the instances in the security group.
2. The settings will be effective only when all the instances are restarted.
3. The settings will be effective for all the instances only after 30 minutes.
4. The settings will be effective only for the new instances added to the security group.
<details>
	<summary>Answer</summary>

	1. The settings will be effective immediately for all the instances in the security group.

</details>

### Question 321: Can a user get a notification of each instance start / terminate configured with Auto Scaling?
1. Yes, if configured with the Launch Config.
2. Yes, always.
3. Yes, if configured with the Auto Scaling group.
4. No.
<details>
	<summary>Answer</summary>

	3. Yes, if configured with the Auto Scaling group.

</details>

### Question 322: Which Amazon storage do you think is the best for my database-style applications that frequently encounter many random reads and writes across the dataset?
1. None of these.
2. Amazon Instance Storage.
3. Any of these.
4. Amazon EBS.
<details>
	<summary>Answer</summary>

	4. Amazon EBS.

</details>

### Question 323: In the Amazon RDS Oracle DB engine, the Database Diagnostic Pack and the Database Tuning Pack are only available with [...].
1. Oracle Standard Edition.
2. Oracle Express Edition.
3. Oracle Enterprise Edition.
4. None of these.
<details>
	<summary>Answer</summary>

	3. Oracle Enterprise Edition.

</details>

### Question 324: Will my standby RDS instance be in the same Availability Zone as my primary?
1. Only for Oracle RDS types.
2. Yes.
3. Only if configured at launch.
4. No.
<details>
	<summary>Answer</summary>

	4. No.

</details>

### Question 325: An administrator is using Amazon CloudFormation to deploy a three tier web application that consists of a web tier and application tier that will utilize Amazon DynamoDB for storage when creating theCloudFormation template which of the following would allow the application instance access to the DynamoDB tables without exposing API credentials?
1. Create an Identity and Access Management Role that has the required permissions to read and write from the required DynamoDB table and associate the Role to the application instances by referencing an instance profile.
2. Use the Parameter section in the Cloud Formation template to nave the user input Access and Secret Keys from an already created IAM user that has me permissions required to read and write from the required DynamoDB table.
3. Create an Identity and Access Management Role that has the required permissions to read and write from the required DynamoDB table and reference the Role in the instance profile property of the application instance.
4. Create an identity and Access Management user in the CloudFormation template that has permissions to read and write from the required DynamoDB table, use the GetAtt function to retrieve the Access and secret keys and pass them to the application instance through user-data.
<details>
	<summary>Answer</summary>

	3. Create an Identity and Access Management Role that has the required permissions to read and write from the required DynamoDB table and reference the Role in the instance profile property of the application instance.

</details>

### Question 326: In an experiment, if the minimum size for an Auto Scaling group is 1 instance, which of the following statements holds true when you terminate the running instance?
1. Auto Scaling must launch a new instance to replace it.
2. Auto Scaling will raise an alarm and send a notification to the user for action.
3. Auto Scaling must configure the schedule activity that terminates the instance after 5 days.
4. Auto Scaling will terminate the experiment.
<details>
	<summary>Answer</summary>

	1. Auto Scaling must launch a new instance to replace it.

</details>

### Question 327: True or False: Manually created DB Snapshots are deleted after the DB Instance is deleted.
1. True.
2. False.
<details>
	<summary>Answer</summary>

	1. True.

</details>

### Question 328: Amazon S3 doesn't automatically give a user who creates [...] permission to perform other actions on that bucket or object.
1. a file.
2. a bucket or object.
3. a bucket or file.
4. a object or file.
<details>
	<summary>Answer</summary>

	2. a bucket or object.

</details>

### Question 329: A company wants to review the security requirements of Glacier. Which of the below mentioned statements is true with respect to the AWS Glacier data security?
1. All data stored on Glacier is protected with AES-256 serverside encryption.
2. All data stored on Glacier is protected with AES-128 serverside encryption.
3. The user can set the serverside encryption flag to encrypt the data stored on Glacier.
4. The data stored on Glacier is not encrypted by default.
<details>
	<summary>Answer</summary>

	1. All data stored on Glacier is protected with AES-256 serverside encryption.

</details>

### Question 330: What does Amazon EBS stand for?
1. Elastic Block Storage.
2. Elastic Business Server.
3. Elastic Blade Server.
4. Elastic Block Store.
<details>
	<summary>Answer</summary>

	4. Elastic Block Store.

</details>

### Question 331: You have a distributed application that periodically processes large volumes of data across multiple Amazon EC2 Instances. The application is designed to recover gracefully from Amazon EC2 instance failures. You are required to accomplish this task in the most cost-effective way. Which of the following will meet your requirements?
1. Spot Instances.
2. Reserved instances.
3. Dedicated instances.
4. On-Demand instances.
<details>
	<summary>Answer</summary>

	1. Spot Instances.

</details>

### Question 332: What does Amazon SWF stand for?
1. Simple Web Flow.
2. Simple Work Flow.
3. Simple Wireless Forms.
4. Simple Web Form.
<details>
	<summary>Answer</summary>

	2. Simple Work Flow.

</details>

### Question 333: Can you specify the security group that you created for a VPC when you launch an instance in EC2-Classic?
1. No, you can specify the security group created for EC2-Classic when you launch a VPC instance.
2. Yes.
3. No.
4. No, you can specify the security group created for EC2-Classic to a non-VPC based instance only.
<details>
	<summary>Answer</summary>

	3. No.

</details>

### Question 334: Which two methods increases the fault tolerance of the connection to VPC-1? (Choose 2 answers)
1. Establish a hardware VPN over the internet between VPC-2 and the on-premises network.
2. Establish a hardware VPN over the internet between VPC-1 and the on-premises network.
3. Establish a new AWS Direct Connect connection and private virtual interface in the same region as VPC-2.
4. Establish a new AWS Direct Connect connection and private virtual interface in a different AWS region than VPC-1.
5. Establish a new AWS Direct Connect connection and private virtual interface in the same AWS region as VPC-1.
<details>
	<summary>Answer</summary>

	2. Establish a hardware VPN over the internet between VPC-1 and the on-premises network.
	5. Establish a new AWS Direct Connect connection and private virtual interface in the same AWS region as VPC-1.

</details>

### Question 335: How would you improve page load times for your users? (Choose 3 answers)
1. Lower the scale up trigger of your Auto Scaling group to 30% so it scales more aggressively.
2. Add an Amazon ElastiCache caching layer to your application for storing sessions and frequent DB queries.
3. Configure Amazon CloudFront dynamic content support to enable caching of re-usable content from your site.
4. Switch Amazon RDS database to the high memory extra large Instance type.
5. Set up a second installation in another region, and use the Amazon Route 53 latency-based routing feature to select the right region.
<details>
	<summary>Answer</summary>

	2. Add an Amazon ElastiCache caching layer to your application for storing sessions and frequent DB queries.
	3. Configure Amazon CloudFront dynamic content support to enable caching of re-usable content from your site.
	4. Switch Amazon RDS database to the high memory extra large Instance type.

</details>

### Question 336: Typically, you want your application to check whether a request generated an error before you spend any time processing results. The easiest way to find out if an error occurred is to look for an [...] node in the response from the Amazon RDS API.
1. incorrect.
2. error.
<details>
	<summary>Answer</summary>

	2. error.

</details>

### Question 337: Through which of the following interfaces is AWS Identity and Access Management available? A. AWS Management Console. B. Command line interface (CLI). C. IAM Query API. D. Existing libraries.
1. Only through Command line interface (CLI).
2. A, B and C.
3. A and C.
4. All of the above.
<details>
	<summary>Answer</summary>

	4. All of the above.

</details>

### Question 338: A [...] is a storage device that moves data in sequences of bytes or bits (blocks).
1. block map.
2. storage block.
3. mapping device.
4. block device.
<details>
	<summary>Answer</summary>

	4. block device.

</details>

### Question 339: You have just finished setting up an advertisement server in which one of the obvious choices for a service was Amazon Elastic MapReduce( EMR) and are now troubleshooting some weird cluster states that you are seeing. Which of the below is not an Amazon EMR cluster state?
1. STARTING.
2. STOPPED.
3. RUNNING.
4. WAITING.
<details>
	<summary>Answer</summary>

	2. STOPPED.

</details>

### Question 340: A US-based company is expanding their web presence into Europe. The company wants to extend their AWS infrastructure from Northern Virginia (us-east-1) into the Dublin (eu-west-1) region. Which of the following options would enable an equivalent experience for users on both continents?
1. Use a public-facing load balancer per region to load-balance web traffic, and enable HTTP health checks.
2. Use a public-facing load balancer per region to load-balance web traffic, and enable sticky sessions.
3. Use Amazon Route 53, and apply a geolocation routing policy to distribute traffic across both regions.
4. Use Amazon Route 53, and apply a weighted routing policy to distribute traffic across both regions.
<details>
	<summary>Answer</summary>

	4. Use Amazon Route 53, and apply a weighted routing policy to distribute traffic across both regions.

</details>

### Question 341: You are building infrastructure for a data warehousing solution and an extra request has come through that there will be a lot of business reporting queries running all the time and you are not sure if your current DB instance will be able to handle it. What would be the best solution for this?
1. DB Parameter Groups.
2. Read Replicas.
3. Multi-AZ DB Instance deployment.
4. Database Snapshots.
<details>
	<summary>Answer</summary>

	2. Read Replicas.

</details>

### Question 342: One of the criteria for a new deployment is that the customer wants to use AWS Storage Gateway. However you are not sure whether you should use gateway-cached volumes or gateway-stored volumes or even what the differences are. Which statement below best describes those differences?
1. Gateway-cached lets you store your data in Amazon Simple Storage Service (Amazon S3) and retain a copy of frequently accessed data subsets locally. Gateway-stored enables you to configure your on-premises gateway to store all your data locally and then asynchronously back up point-in-time snapshots of this data to Amazon S3.
2. Gateway-cached is free whilst gateway-stored is not.
3. Gateway-cached is up to 10 times faster than gateway-stored.
4. Gateway-stored lets you store your data in Amazon Simple Storage Service (Amazon S3) and retain a copy of frequently accessed data subsets locally. Gateway-cached enables you to configure your on-premises gateway to store all your data locally and then asynchronously back up point-in-time snapshots of this data to Amazon S3.
<details>
	<summary>Answer</summary>

	1. Gateway-cached lets you store your data in Amazon Simple Storage Service (Amazon S3) and retain a copy of frequently accessed data subsets locally. Gateway-stored enables you to configure your on-premises gateway to store all your data locally and then asynchronously back up point-in-time snapshots of this data to Amazon S3.

</details>

### Question 343: In Amazon RDS, security groups are ideally used to:
1. Define maintenance period for database engines.
2. Launch Amazon RDS instances in a subnet.
3. Create, describe, modify, and delete DB instances.
4. Control what IP addresses or EC2 instances can connect to your databases on a DB instance.
<details>
	<summary>Answer</summary>

	4. Control what IP addresses or EC2 instances can connect to your databases on a DB instance.

</details>

### Question 344: How long does an AWS free usage tier EC2 last for?
1. Forever.
2. 12 Months upon signup.
3. 1 Month upon signup.
4. 6 Months upon signup.
<details>
	<summary>Answer</summary>

	2. 12 Months upon signup.

</details>

### Question 345: After you recommend Amazon Redshift to a client as an alternative solution to paying data warehouses to analyze his data, your client asks you to explain why you are recommending Redshift. Which of the following would be a reasonable response to his request?
1. It has high performance at scale as data and query complexity grows.
2. It prevents reporting and analytic processing from interfering with the performance of OLTP workloads.
3. You don't have the administrative burden of running your own data warehouse and dealing with setup, durability, monitoring, scaling, and patching.
4. All answers listed are a reasonable response to his question.
<details>
	<summary>Answer</summary>

	4. All answers listed are a reasonable response to his question.

</details>

### Question 346: You can seamlessly join an EC2 instance to your directory domain. What connectivity do you need to be able to connect remotely to this instance?
1. You must have IP connectivity to the instance from the network you are connecting from.
2. You must have the correct encryption keys to connect to the instance remotely.
3. You must have enough bandwidth to connect to the instance.
4. You must use MFA authentication to be able to connect to the instance remotely.
<details>
	<summary>Answer</summary>

	1. You must have IP connectivity to the instance from the network you are connecting from.

</details>

### Question 347: Does Amazon DynamoDB support both increment and decrement atomic operations?
1. Only increment, since decrement are inherently impossible with DynamoDB's data model.
2. No, neither increment nor decrement operations.
3. Yes, both increment and decrement operations.
4. Only decrement, since increment are inherently impossible with DynamoDB's data model.
<details>
	<summary>Answer</summary>

	3. Yes, both increment and decrement operations.

</details>

### Question 348: You nave multiple Amazon EC2 instances running in a cluster across multiple Availability Zones within the same region. What combination of the following should be used to ensure the highest network performance (packets per second), lowest latency, and lowest jitter? (Choose 3 answers)
1. Amazon EC2 placement groups.
2. Enhanced networking.
3. Amazon PV AMI.
4. Amazon HVM AMI.
5. Amazon Linux.
6. Amazon VPC.
<details>
	<summary>Answer</summary>

	1. Amazon EC2 placement groups.
	2. Enhanced networking.
	4. Amazon HVM AMI.

</details>

### Question 349: If an Amazon EBS volume is the root device of an instance, can I detach it without stopping the instance?
1. Yes but only if Windows instance.
2. Yes.
3. No.
4. Yes but only if a Linux instance.
<details>
	<summary>Answer</summary>

	3. No.

</details>

### Question 350: True or False: When you add a rule to a DB security group, you do not need to specify port number or protocol.
1. Depends on the ROMS used.
2. True.
3. False.
<details>
	<summary>Answer</summary>

	2. True.

</details>

### Question 351: Before I delete an EBS volume, what can I do if I want to recreate the volume later?
1. Create a copy of the EBS volume (not a snapshot).
2. Store a snapshot of the volume.
3. Download the content to an EC2 instance
4. Back up the data in to a physical disk.
<details>
	<summary>Answer</summary>

	2. Store a snapshot of the volume.

</details>

### Question 352: An accountant asks you to design a small VPC network for him and, due to the nature of his business, just needs something where the workload on the network will be low, and dynamic data will be accessed infrequently. Being an accountant, low cost is also a major factor. Which EBS volume type would best suit his requirements?
1. Magnetic.
2. Any, as they all perform the same and cost the same.
3. General Purpose (SSD).
4. Magnetic or Provisioned IOPS (SSD).
<details>
	<summary>Answer</summary>

	1. Magnetic.

</details>

### Question 353: Uur company currently has a 2-tier web application running in an on-premises data center. You have experienced several infrastructure failures in the past two months resulting in significant financial losses. Your CIO is strongly agreeing to move the application to AWS. While working on achieving buy-in from the other company executives, he asks you to develop a disaster recovery plan to help improve Business continuity in the short term. He specifies a target Recovery Time Objective (RTO) of 4 hours and a Recovery Point Objective (RPO) of 1 hour or less. He also asks you to implement the solution within 2 weeks. Your database is 200GB in size and you have a 20Mbps Internet connection. How would you do this while minimizing costs?
1. Create an EBS backed private AMI which includes a fresh install of your application. Develop a CloudFormation template which includes your AMI and the required EC2, AutoScaling, and ELBresources to support deploying the application across Multiple- Availability-Zones. Asynchronously replicate transactions from your on-premises database to a database instance in AWS across a secure VPN connection.
2. Deploy your application on EC2 instances within an Auto Scaling group across multiple availability zones. Asynchronously replicate transactions from your on-premises database to a database instance in AWS across a secure VPN connection.
3. Create an EBS backed private AMI which includes a fresh install of your application. Setup a script in your data center to backup the local database every 1 hour and to encrypt and copy the resulting file to an S3 bucket using multi-part upload.
4. Install your application on a compute-optimized EC2 instance capable of supporting the application's average load. Synchronously replicate transactions from your on-premises database to a database instance in AWS across a secure Direct Connect connection.
<details>
	<summary>Answer</summary>

	1. Create an EBS backed private AMI which includes a fresh install of your application. Develop a CloudFormation template which includes your AMI and the required EC2, AutoScaling, and ELBresources to support deploying the application across Multiple- Availability-Zones. Asynchronously replicate transactions from your on-premises database to a database instance in AWS across a secure VPN connection.

</details>

### Question 354: A customer implemented AWS Storage Gateway with a gateway-cached volume at their main office. An event takes the link between the main and branch office offline. Which methods will enable the branch office to access their data? (Choose 3 answers)
1. Use a HTTPS GET to the Amazon S3 bucket where the files are located.
2. Restore by implementing a lifecycle policy on the Amazon S3 bucket.
3. Make an Amazon Glacier Restore API ca ll to load the files into another Amazon S3 bucket within four to six hours.
4. Launch a new AWS Storage Gateway instance AMI in Amazon EC2, and restore from a gateway snapshot.
5. Create an Amazon EBS volume from a gateway snapshot, and mount it to an Amazon EC2 instance.
6. Launch an AWS Storage Gateway virtual iSCSI device at the branch office, and restore from a gateway snapshot.
<details>
	<summary>Answer</summary>

	4. Launch a new AWS Storage Gateway instance AMI in Amazon EC2, and restore from a gateway snapshot.
	5. Create an Amazon EBS volume from a gateway snapshot, and mount it to an Amazon EC2 instance.
	6. Launch an AWS Storage Gateway virtual iSCSI device at the branch office, and restore from a gateway snapshot.

</details>

### Question 355: Your customer is willing to consolidate their log streams (access logs application logs security logs etc.) in one single system. Once consolidated, the customer wants to analyze these logs in real time based on heuristics. From time to time, the customer needs to validate heuristics, which requires going back to data samples extracted from the last 12 hours. What is the best approach to meet your customer's requirements?
1. Send all the log events to Amazon SQS, setup an Auto Scaling group of EC2 servers to consume the logs and apply the heuristics.
2. Send all the log events to Amazon Kinesis develop a client process to apply heuristics on the logs.
3. Configure Amazon Cloud Trail to receive custom logs, use EMR to apply heuristics the logs.
4. Setup an Auto Scaling group of EC2 syslogd servers, store the logs on S3 use EMR to apply heuristics on the logs.
<details>
	<summary>Answer</summary>

	2. Send all the log events to Amazon Kinesis develop a client process to apply heuristics on the logs.

</details>

### Question 356: Can the string value of 'Key' be prefixed with laws?
1. No.
2. Only for EC2 not S3.
3. Yes.
4. Only for S3 not EC.
<details>
	<summary>Answer</summary>

	1. No.

</details>

### Question 357: You are configuring your company's application to use Auto Scaling and need to move user state information. Which of the following AWS services provides a shared data store with durability and lowlatency?
1. AWS ElastiCache Memcached.
2. Amazon Simple Storage Service.
3. Amazon EC2 instance storage.
4. Amazon DynamoDB.
<details>
	<summary>Answer</summary>

	2. Amazon Simple Storage Service.

</details>

### Question 358: Your company previously configured a heavily used, dynamically routed VPN connection between your on-premises data center and AWS. You recently provisioned a DirectConnect connection and would like to start using the new connection. After configuring DirectConnect settings in the AWS Console, which of the following options win provide the most seamless transition for your users?
1. Delete your existing VPN connection to avoid routing loops configure your DirectConnect router with the appropriate settings and verity network traffic is leveraging DirectConnect.
2. Configure your DirectConnect router with a higher 8GP priority man your VPN router, verify network traffic is leveraging Directconnect and then delete your existing VPN connection.
3. Update your VPC route tables to point to the DirectConnect connection configure your DirectConnect router with the appropriate settings verify network traffic is leveraging DirectConnect and then delete the VPN connection.
4. Configure your DirectConnect router, update your VPC route tables to point to the DirectConnect connection, configure your VPN connection with a higher BGP pointy. And verify network traffic is leveraging the DirectConnect connection.
<details>
	<summary>Answer</summary>

	4. Configure your DirectConnect router, update your VPC route tables to point to the DirectConnect connection, configure your VPN connection with a higher BGP pointy. And verify network traffic is leveraging the DirectConnect connection.

</details>

### Question 359: If I modify a DB Instance or the DB parameter group associated with the instance, should I reboot the instance for the changes to take effect?
1. Yes.
2. No.
<details>
	<summary>Answer</summary>

	1. Yes.

</details>

### Question 360: After setting up several database instances in Amazon Relational Database Service (Amazon RDS) you decide that you need to track the performance and health of your databases. How can you do this?
1. Subscribe to Amazon RDS events to be notified when changes occur with a DB instance, DB snapshot, DB parameter group, or DB security group.
2. Use the free Amazon CloudWatch service to monitor the performance and health of a DB instance.
3. All of the items listed will track the performance and health of a database.
4. View, download, or watch database log files using the Amazon RDS console or Amazon RDS APIs. You can also query some database log files that are loaded into database tables.
<details>
	<summary>Answer</summary>

	3. All of the items listed will track the performance and health of a database.

</details>

### Question 361: You deployed your company website using Elastic Beanstalk and you enabled log file rotation to S3. An Elastic MapReduce job is periodically analyzing the logs on S3 to build a usage dashboard that you share with your CIO. You recently improved overall performance of the website using CloudFront for dynamic content delivery and your website as the origin. After this architectural change, the usage dashboard shows that the traffic on your website dropped by an order of magnitude. How do you fix your usage dashboard?
1. Enable CloudFront to deliver access logs to S3 and use them as input of the Elastic MapReduce job.
2. Turn on Cloud Trail and use trail log tiles on S3 as input of the Elastic MapReduce job.
3. Change your log collection process to use Cloud Watch ELB metrics as input of the Elastic Map Reduce job.
4. Use Elastic Beanstalk 'Rebuild Environment' option to update log delivery to the Elastic Map Reduce job.
5. Use Elastic Beanstalk 'Restart App server(s)' option to update log delivery to the Elastic Map Reduce job.
<details>
	<summary>Answer</summary>

	1. Enable CloudFront to deliver access logs to S3 and use them as input of the Elastic MapReduce job.

</details>

### Question 362: A customer has a 10 GB AWS Direct Connect connection to an AWS region where they have a web application hosted on Amazon Elastic Computer Cloud (EC2). The application has dependencies on an on-premises mainframe database that uses a BASE (Basic Available. Sort stale Eventual consistency) rather than an ACID (Atomicity. Consistency isolation. Durability) consistency model. The application is exhibiting undesirable behavior because the database is not able to handle the volume of writes. How can you reduce the load on your on-premises database resources in the most cost-effective way?
1. Use an Amazon Elastic MapReduce (EMR) S3DistCp as a synchronization mechanism between the on-premises database and a Hadoop cluster on AWS.
2. Modify the application to write to an Amazon SQS queue and develop a worker process to flush the queue to the on-premises database.
3. Modify the application to use DynamoDB to feed an EMR cluster which uses a map function to write to the on-premises database.
4. Provision an RDS read-replica database on AWS to handle the writes and synchronize the two databases using Data Pipeline.
<details>
	<summary>Answer</summary>

	1. Use an Amazon Elastic MapReduce (EMR) S3DistCp as a synchronization mechanism between the on-premises database and a Hadoop cluster on AWS.

</details>

### Question 363: You are very concerned about security on your network because you have multiple programmers testing APIs and SDKs and you have no idea what is happening. You think CloudTrail may help but are not sure what it does. Which of the following statements best describes the AWS service CloudTrail?
1. With AWS CloudTrail you can get a history of AWS API calls and related events for your account.
2. With AWS CloudTrail you can get a history of IAM users for your account.
3. With AWS CloudTrail you can get a history of S3 logfiles for your account.
4. With AWS CloudTrail you can get a history of CloudFormation JSON scripts used for your account.
<details>
	<summary>Answer</summary>

	1. With AWS CloudTrail you can get a history of AWS API calls and related events for your account.

</details>

### Question 364: Every user you create in the IAM system starts with [...].
1. partial permissions.
2. full permissions.
3. no permissions.
<details>
	<summary>Answer</summary>

	3. no permissions.

</details>

### Question 365: Amazon S3 allows you to set per-file permissions to grant read and/or write access. However you have decided that you want an entire bucket with 100 files already in it to be accessible to the public. You don't want to go through 100 files individually and set permissions. What would be the best way to do this?
1. Move the bucket to a new region.
2. Add a bucket policy to the bucket.
3. Move the files to a new bucket.
4. Use Amazon EBS instead of S3.
<details>
	<summary>Answer</summary>

	2. Add a bucket policy to the bucket.

</details>

### Question 366: You are designing an SSUTLS solution that requires HTTPS clients to be authenticated by the Web server using client certificate authentication. The solution must be resilient. Which of the following options would you consider for configuring the web server infrastructure? (Choose 2 answers)
1. Configure ELB with TCP listeners on TCP/4d3. And place the Web servers behind it.
2. Configure your Web servers with EIPS Place the Web servers in a Route 53 Record Set and configure health checks against all Web servers.
3. Configure ELB with HTTPS listeners, and place the Web servers behind it.
4. Configure your web servers as the origins for a CloudFront distribution. Use custom SSL certificates on your CloudFront distribution.
<details>
	<summary>Answer</summary>

	1. Configure ELB with TCP listeners on TCP/4d3. And place the Web servers behind it.
	2. Configure your Web servers with EIPS Place the Web servers in a Route 53 Record Set and configure health checks against all Web servers.

</details>

### Question 367: Which of the following are use cases for Amazon DynamoDB? (Choose 3 answers)
1. Storing BLOB data.
2. Managing web sessions.
3. Storing JSON documents.
4. Storing metadata for Amazon S3 objects.
5. Running relational joins and complex updates.
6. Storing large amounts of infrequently accessed data.
<details>
	<summary>Answer</summary>

	3. Storing JSON documents.
	5. Running relational joins and complex updates.
	6. Storing large amounts of infrequently accessed data.

</details>

### Question 368: You have been asked to set up a database in AWS that will require frequent and granular updates. You know that you will require a reasonable amount of storage space but are not sure of the best option. What is the recommended storage option when you run a database on an instance with the above criteria?
1. Amazon S3.
2. Amazon EBS.
3. AWS Storage Gateway.
4. Amazon Glacier.
<details>
	<summary>Answer</summary>

	2. Amazon EBS.

</details>

### Question 369: An application hosted at the EC2 instance receives an HTTP request from ELB. The same request has an X-Forwarded-For header, which has three IP addresses. Which system's IP will be a part of this header?
1. Previous Request IP address.
2. Client IP address.
3. All of the answers listed here.
4. Load Balancer IP address.
<details>
	<summary>Answer</summary>

	3. All of the answers listed here.

</details>

### Question 370: An organization has developed a mobile application which allows end users to capture a photo on their mobile device, and store it inside an application. The application internally uploads the data to AWS S3. The organization wants each user to be able to directly upload data to S3 using their Google ID. How will the mobile app allow this?
1. Use the AWS Web identity federation for mobile applications, and use it to generate temporary security credentials for each user.
2. It is not possible to connect to AWS S3 with a Google I
3. Create an IAM user every time a user registers with their Google ID and use IAM to upload files to S3.
4. Create a bucket policy with a condition which allows everyone to upload if the login ID has a Google part to it.
<details>
	<summary>Answer</summary>

	1. Use the AWS Web identity federation for mobile applications, and use it to generate temporary security credentials for each user.

</details>

### Question 371: You must increase storage size in increments of at least [...].
1. 40.
2. 20.
3. 50.
4. 10.
<details>
	<summary>Answer</summary>

	4. 10.

</details>

### Question 372: You need to set up a security certificate for a client's e-commerce website as it will use the HTTPS protocol. Which of the below AWS services do you need to access to manage your SSL server certificate?
1. AWS Directory Service.
2. AWS Identity & Access Management.
3. AWS CloudFormation.
4. Amazon Route 53.
<details>
	<summary>Answer</summary>

	2. AWS Identity & Access Management.

</details>

### Question 373: After setting up a Virtual Private Cloud (VPC) network, a more experienced cloud engineer suggests that to achieve low network latency and high network throughput you should look into setting up a placement group. You know nothing about this, but begin to do some research about it and are especially curious about its limitations. Which of the below statements is wrong in describing the limitations of a placement group?
1. Although launching multiple instance types into a placement group is possible, this reduces the likelihood that the required capacity will be available for your launch to succeed.
2. A placement group can span multiple Availability Zones.
3. You can't move an existing instance into a placement group.
4. A placement group can span peered VPCs.
<details>
	<summary>Answer</summary>

	2. A placement group can span multiple Availability Zones.

</details>

### Question 374: True or False: When you perform a restore operation to a point in time or from a DB Snapshot, a new DB Instance is created with a new endpoint.
1. True.
2. False.
<details>
	<summary>Answer</summary>

	1. True.

</details>

### Question 375: What is the Reduced Redundancy option in Amazon S3?
1. Less redundancy for a lower cost.
2. It doesn't exist in Amazon S3, but in Amazon EBS.
3. It allows you to destroy any copy of your files outside a specific jurisdiction.
4. It doesn't exist at all.
<details>
	<summary>Answer</summary>

	1. Less redundancy for a lower cost.

</details>

### Question 376: You are setting up your first Amazon Virtual Private Cloud (Amazon VPC) so you decide to use the VPC wizard in the AWS console to help make it easier for you. Which of the following statements is correct regarding instances that you launch into a default subnet via the VPC wizard?
1. Instances that you launch into a default subnet receive a public IP address and 10 private IP addresses.
2. Instances that you launch into a default subnet receive both a public IP address and a private IP address.
3. Instances that you launch into a default subnet don't receive any ip addresses and you need to define them manually.
4. Instances that you launch into a default subnet receive a public IP address and 5 private IP addresses.
<details>
	<summary>Answer</summary>

	2. Instances that you launch into a default subnet receive both a public IP address and a private IP address.

</details>

### Question 377: For which of the following use cases are Simple Workflow Service (SWF) and Amazon EC2 an appropriate solution? (Choose 2 answers)
1. Using as an endpoint to collect thousands of data points per hour from a distributed fleet of sensors.
2. Managing a multi-step and multi-decision checkout process of an e-commerce website.
3. Orchestrating the execution of distributed and auditable business processes.
4. Using as an SNS (Simple Notification Service) endpoint to trigger execution of video transcoding jobs.
5. Using as a distributed session store for your web application.
<details>
	<summary>Answer</summary>

	2. Managing a multi-step and multi-decision checkout process of an e-commerce website.
	3. Orchestrating the execution of distributed and auditable business processes.

</details>

### Question 378: Which of the following instance types are available as Amazon EBS-backed only? (Choose 2 answers)
1. General purpose T2.
2. General purpose M3.
3. Compute-optimized C4.
4. Compute-optimized C3.
5. Storage-optimized 12.
<details>
	<summary>Answer</summary>

	1. General purpose T2.
	4. Compute-optimized C3.

</details>

### Question 379: True or False: Without IAM, you cannot control the tasks a particular user or system can do and what AWS resources they might use.
1. True.
2. False.
<details>
	<summary>Answer</summary>

	2. False.

</details>

### Question 380: What does Amazon ELB stand for?
1. Elastic Linux Box.
2. Encrypted Linux Box.
3. Encrypted Load Balancing.
4. Elastic Load Balancing.
<details>
	<summary>Answer</summary>

	4. Elastic Load Balancing.

</details>

### Question 381: A read only news reporting site with a combined web and application tier and a database tier that receives large and unpredictable traffic demands must be able to respond to these traffic fluctuations automatically. What AWS services should be used meet these requirements?
1. Stateless instances for the web and application tier synchronized using Elasticache Memcached in an autoscaimg group monitored with CloudWatch. And RDSwith read replicas.
2. Stateful instances for the web and application tier in an autoscaling group monitored with CloudWatch and RDS with read replicas.
3. Stateful instances for the web and application tier in an autoscaling group monitored with CloudWatch and multi-AZ RDS.
4. Stateless instances for the web and application tier synchronized using ElastiCache Memcached in an autoscaling group monitored with CloudWatch and multi-AZ RDS.
<details>
	<summary>Answer</summary>

	1. Stateless instances for the web and application tier synchronized using Elasticache Memcached in an autoscaimg group monitored with CloudWatch. And RDSwith read replicas.

</details>

### Question 382: In Amazon AWS, which of the following statements is true of key pairs?
1. Key pairs are used only for Amazon SDKs.
2. Key pairs are used only for Amazon EC2 and Amazon CloudFront.
3. Key pairs are used only for Elastic Load Balancing and AWS IA.
4. Key pairs are used for all Amazon services.
<details>
	<summary>Answer</summary>

	2. Key pairs are used only for Amazon EC2 and Amazon CloudFront.

</details>

### Question 383: What does Amazon ElastiCache provide?
1. A service by this name doesn't exist. Perhaps you mean Amazon CloudCache.
2. A virtual server with a huge amount of memory.
3. A managed In-memory cache service.
4. An Amazon EC2 instance with the Memcached software already pre-installed.
<details>
	<summary>Answer</summary>

	3. A managed In-memory cache service.

</details>

### Question 384: What are the two permission types used by AWS?
1. Resource-based and Product-based.
2. Product-based and Service-based.
3. Service-based.
4. User-based and Resource-based.
<details>
	<summary>Answer</summary>

	4. User-based and Resource-based.

</details>

### Question 385: In AWS CloudHSM, in addition to the AWS recommendation that you use two or more HSM appliances in a high-availability configuration to prevent the loss of keys and data, you can also perform a remote backup/restore of a Luna SA partition if you have purchased a:
1. Luna Restore HS.
2. Luna Backup HS.
3. Luna HS.
4. Luna SA HS.
<details>
	<summary>Answer</summary>

	2. Luna Backup HS.

</details>

### Question 386: An organization has a statutory requirement to protect the data at rest for the S3 objects. Which of the below mentioned options need not be enabled by the organization to achieve data security?
1. MFA delete for S3 objects.
2. Client side encryption.
3. Bucket versioning.
4. Data replication.
<details>
	<summary>Answer</summary>

	4. Data replication.

</details>

### Question 387: Your company is in the process of developing a next generation pet collar that collects biometric information to assist families with promoting healthy lifestyles for their pets Each collar will push 30kb of biometric data in JSON format every 2 seconds to a collection platform that will process and analyze the data providing health trending information back to the pet owners and veterinarians via a web portal Management has tasked you to architect the collection platform ensuring the following requirements are met. Provide the ability for real-time analytics of the inbound biometric data. Ensure processing of the biometric data is highly durable. Elastic and parallel. The results of the analytic processing should be persisted for data mining. Which architecture outlined below win meet the initial requirements for the collection platform?
1. Utilize S3 to collect the inbound sensor data analyze the data from S3 with a daily scheduled Data Pipeline and save the results to a Redshift Cluster.
2. Utilize Amazon Kinesis to collect the inbound sensor data, analyze the data with Kinesis clients and save the results to a Red shift cluster using EMR.
3. Utilize SQS to collect the inbound sensor data analyze the data from SQS with Amazon Kinesis and save the results to a Microsoft SQL Server RDS instance.
4. Utilize EMR to collect the inbound sensor data, analyze the data from EUR with Amazon Kinesis and save me results to Dynamo DB.
<details>
	<summary>Answer</summary>

	2. Utilize Amazon Kinesis to collect the inbound sensor data, analyze the data with Kinesis clients and save the results to a Red shift cluster using EMR.

</details>

### Question 388: Which of the following approaches provides the lowest cost for Amazon Elastic Block Store snapshots while giving you the ability to fully restore data?
1. Maintain two snapshots: the original snapshot and the latest incremental snapshot.
2. Maintain a volume snapshot; subsequent snapshots will overwrite one another
3. Maintain a single snapshot the latest snapshot is both Incremental and complete.
4. Maintain the most current snapshot, archive the original and incremental to Amazon Glacier.
<details>
	<summary>Answer</summary>

	1. Maintain two snapshots: the original snapshot and the latest incremental snapshot.

</details>

### Question 389: You have a video transcoding application running on Amazon EC2. Each instance pol ls a queue to find out which video should be transcoded, and then runs a transcoding process. If this process is interrupted, the video will be transcoded by another instance based on the queuing system. You have a large backlog of videos which need to be transcoded and would like to reduce this backlog by adding more instances. You will need these instances only until the backlog is reduced. Which type of Amazon EC2 instances should you use to reduce the backlog in the most cost efficient way?
1. Reserved instances.
2. Spot instances.
3. Dedicated instances.
4. On-demand instances.
<details>
	<summary>Answer</summary>

	2. Spot instances.

</details>

### Question 390: What does the AWS Storage Gateway provide?
1. It allows to integrate on-premises IT environments with Cloud Storage.
2. A direct encrypted connection to Amazon S3.
3. It's a backup solution that provides an on-premises Cloud storage.
4. It provides an encrypted SSL endpoint for backups in the Cloud.
<details>
	<summary>Answer</summary>

	1. It allows to integrate on-premises IT environments with Cloud Storage.

</details>

### Question 391: You have recently joined a startup company building sensors to measure street noise and air quality in urban areas. The company has been running a pilot deployment of around 100 sensors for 3 months each sensor uploads 1KB of sensor data every minute to a backend hosted on AWS. During the pilot, you measured a peak or 10 IOPS on the database, and you stored an average of 3GB of sensor data per month in the database. The current deployment consists of a load-balanced auto scaled Ingestion layer using EC2 instances and a PostgreSQL RDS database with 500GB standard storage. The pilot is considered a success and your CEO has managed to get the attention or some potential investors. The business plan requires a deployment of at least lOOK sensors which needs to be supported by the backend. You also need to store sensor data for at least two years to be able to compare year over year Improvements. To secure funding, you have to make sure that the platform meets these requirements and leaves room for further scaling. Which setup win meet the requirements?
1. Add an SQS queue to the ingestion layer to buffer writes to the RDS instance.
2. Ingest data into a DynamoDB table and move old data to a Redshift cluster.
3. Replace the RDS instance with a 6 node Redshift cluster with 96TB of storage.
4. Keep the current architecture but upgrade RDS storage to 3TB and lOK provisioned IOPS.
<details>
	<summary>Answer</summary>

	3. Replace the RDS instance with a 6 node Redshift cluster with 96TB of storage.

</details>

### Question 392: After a major security breach your manager has requested a report of all users and their credentials in AWS. You discover that in IAM you can generate and download a credential report that lists all users in your account and the status of their various credentials, including passwords, access keys, MFA devices, and signing certificates. Which following statement is incorrect in regards to the use of credential reports?
1. Credential reports are downloaded XML files.
2. You can get a credential report using the AWS Management Console, the AWS CLI, or the IAM API.
3. You can use the report to audit the effects of credential lifecycle requirements, such as password rotation.
4. You can generate a credential report as often as once every four hours.
<details>
	<summary>Answer</summary>

	1. Credential reports are downloaded XML files.

</details>

### Question 393: What is the maximum response time for a Business level Premium Support case?
1. 30 minutes.
2. 1 hour.
3. 12 hours.
4. 10 minutes.
<details>
	<summary>Answer</summary>

	2. 1 hour.

</details>

### Question 394: Per the AWS Acceptable Use Policy, penetration testing of EC2 instances
1. May be performed by AWS, and will be performed by AWS upon customer request.
2. May be performed by AWS, and is periodically performed by AWS.
3. Are expressly prohibited under all circumstances.
4. May be performed by the customer on their own instances with prior authorization from AWS.
5. May be performed by the customer on their own instances, only if performed from EC2 instances.
<details>
	<summary>Answer</summary>

	2. May be performed by AWS, and is periodically performed by AWS.

</details>

### Question 395: Which of the following features are provided by Amazon EC2?
1. Exadata Database Machine, Optimized Storage Management, Flashback Technology, and Data Warehousing.
2. Instances, Amazon Machine Images (AMIs), Key Pairs, Amazon EBS Volumes, Firewall, Elastic IP address, Tags, and Virtual Private Clouds (VPCs).
3. Real Application Clusters (RAC), Elasticache Machine Images (EMIs), Data Warehousing, Flashback Technology, Dynamic IP address.
4. Exadata Database Machine, Real Application Clusters (RAC), Data Guard, Table and Index Partitioning, and Data Pump Compression.
<details>
	<summary>Answer</summary>

	2. Instances, Amazon Machine Images (AMIs), Key Pairs, Amazon EBS Volumes, Firewall, Elastic IP address, Tags, and Virtual Private Clouds (VPCs).

</details>

### Question 396: True or False: If you add a tag that has the same key as an existing tag on a DB Instance, the new value overwrites the old value.
1. True.
2. False.
<details>
	<summary>Answer</summary>

	1. True.

</details>

### Question 397: You decide that you need to create a number of Auto Scaling groups to try and save some money as you have noticed that at certain times most of your EC2 instances are not being used. By default, what is the maximum number of Auto Scaling groups that AWS will allow you to create?
1. 12.
2. Unlimited.
3. 20.
4. 2.
<details>
	<summary>Answer</summary>

	3. 20.

</details>

### Question 398: After moving an E-Commerce website for a client from a dedicated server to AWS you have also set up auto scaling to perform health checks on the instances in your group and replace instances that fail these checks. Your client has come to you with his own health check system that he wants you to use as it has proved to be very useful prior to his site running on AWS. What do you think would be an appropriate response to this given all that you know about auto scaling?
1. It is not possible to implement your own health check system. You need to use AWSs health check system.
2. It is not possible to implement your own health check system due to compatibility issues.
3. It is possible to implement your own health check system and then send the instance's health information directly from your system to Cloud Watch.
4. It is possible to implement your own health check system and then send the instance's health information directly from your system to Cloud Watch but only in the US East (Virginia) region.
<details>
	<summary>Answer</summary>

	3. It is possible to implement your own health check system and then send the instance's health information directly from your system to Cloud Watch.

</details>

### Question 399: You've been brought in as solutions architect to assist an enterprise customer with their migration of an e-commerce platform to Amazon Virtual Private Cloud (VPC) The previous architect has already deployed a 3-tier VPC, The configuration is as follows. VPC: vpc-2f8bc447. IGW: igw-2d8bc445. NACL: ad-208bc448. 5ubnets and Route Tables: Web servers: subnet-258bc44d. Application servers: subnet-248bc44c. Database servers: subnet-9189c6f9. Route Tables: rrb-218bc449, rtb-238bc44b. Associations: subnet-258bc44d: rtb-218bc449, subnet-248bc44c: rtb-238bc44b, subnet-9189c6f9: rtb-238bc44b. You are now ready to begin deploying EC2 instances into the VPC Web servers must have direct access to the internet Application and database servers cannot have direct access to the internet. Which configuration below will allow you the ability to remotely administer your application and database servers, as well as allow these servers to retrieve updates from the Internet?
1. Create a bastion and NAT instance in subnet-258bc44d, and add a route from rtb- 238bc44b to the NAT instance.
2. Add a route from rtb-238bc44b to igw-2d8bc445 and add a bastion and NAT instance within subnet-248bc44c.
3. Create a bastion and NAT instance in subnet-248bc44c, and add a route from rtb- 238bc44b to subnet-258bc44d.
4. Create a bastion and NAT instance in subnet-258bc44d, add a route from rtb-238bc44b to lgw- 2d8bc445, and a new NACL that allows access between subnet-258bc44d and subnet -248bc44c.
<details>
	<summary>Answer</summary>

	1. Create a bastion and NAT instance in subnet-258bc44d, and add a route from rtb- 238bc44b to the NAT instance.

</details>

### Question 400: After deciding that EMR will be useful in analysing vast amounts of data for a gaming website that you are architecting you have just deployed an Amazon EMR Cluster and wish to monitor the cluster performance. Which of the following tools cannot be used to monitor the cluster performance?
1. Kinesis.
2. Ganglia.
3. CloudWatch Metrics.
4. Hadoop Web Interfaces.
<details>
	<summary>Answer</summary>

	1. Kinesis.

</details>

### Question 401: A/An [...] is the concept of allowing (or disallowing) an entity such as a user, group, or role some type of access to one or more resources.
1. user.
2. AWS Account.
3. resource.
4. permission.
<details>
	<summary>Answer</summary>

	2. AWS Account.

</details>

### Question 402: You are running a successful multitier web application on AWS and your marketing department has asked you to add a reporting tier to the application. The reporting tier will aggregate and publish status reports every 30 minutes from user-generated information that is being stored in your web application s database. You are currently running a Multi-AZ RDS MySQL instance for the database tier. You also have implemented Elasticache as a database caching layer between the application tier and database tier. Please select the answer that will allow you to successful ly implement the reporting tier with as little impact as possible to your database.
1. Continually send transaction logs from your master database to an S3 bucket and generate the reports off the S3 bucket using S3 byte range requests.
2. Generate the reports by querying the synchronously replicated standby RDS MySQL instance maintained through Multi-AZ.
3. Launch a RDS Read Replica connected to your Multi-AZ master database and generate reports by querying the Read Replica.
4. Generate the reports by querying the ElastiCache database caching tier.
<details>
	<summary>Answer</summary>

	3. Launch a RDS Read Replica connected to your Multi-AZ master database and generate reports by querying the Read Replica.

</details>

### Question 403: Can I delete a snapshot of the root device of an EBS volume used by a registered AMI?
1. Only via API.
2. Only via Console.
3. Yes.
4. No.
<details>
	<summary>Answer</summary>

	3. Yes.

</details>

### Question 404: MySQL installations default to port [...].
1. 3306.
2. 443.
3. 80.
4. 1158.
<details>
	<summary>Answer</summary>

	1. 3306.

</details>

### Question 405: In the 'Detailed ' monitoring data available for your Amazon EBS volumes, Provisioned IOPS volumes automatically send [...] minute metrics to Amazon CloudWatch.
1. 5.
2. 2.
3. 1.
4. 3.
<details>
	<summary>Answer</summary>

	3. 1.

</details>

### Question 406: A user has deployed an application on his private cloud. The user is using his own monitoring tool. He wants to configure it so that whenever there is an error, the monitoring tool will notify him via SMS. Which of the below mentioned AWS services will help in this scenario?
1. AWS SES.
2. AWS SNS.
3. None because the user infrastructure is in the private cloud.
4. AWS SMS.
<details>
	<summary>Answer</summary>

	2. AWS SNS.

</details>

### Question 407: What does Amazon Route 53 provide?
1. A global Content Delivery Network.
2. None of these.
3. A scalable Domain Name System.
4. An SSH endpoint for Amazon EC2.
<details>
	<summary>Answer</summary>

	3. A scalable Domain Name System.

</details>

### Question 408: The AWS CloudHSM service defines a resource known as a high-availability (HA) [...], which is a virtual partition that represents a group of partitions, typically distributed between several physical HSMs for high-availability.
1. proxy group.
2. partition group.
3. functional group.
4. relational group.
<details>
	<summary>Answer</summary>

	2. partition group.

</details>

### Question 409: In Amazon EC2, partial instance-hours are billed [...].
1. per second used in the hour.
2. per minute used.
3. by combining partial segments into full hours.
4. as full hours.
<details>
	<summary>Answer</summary>

	4. as full hours.

</details>

### Question 410: In Amazon EC2, what is the limit of Reserved Instances per Availability Zone each month?
1. 5.
2. 20.
3. 50.
4. 10.
<details>
	<summary>Answer</summary>

	2. 20.

</details>

### Question 411: True or False: When using IAM to control access to your RDS resources, the key names that can be used are case sensitive. For example, aws: CurrentTime is NOT equivalent to AWS: currenttime.
1. True.
2. False.
<details>
	<summary>Answer</summary>

	1. True.

</details>

### Question 412: You need to create a JSON-formatted text file for AWS CloudFormation. This is your first template and the only thing you know is that the templates include several major sections but there is only one that is required for it to work. What is the only section required?
1. Mappings.
2. Outputs.
3. Resources.
4. Conditions.
<details>
	<summary>Answer</summary>

	3. Resources.

</details>

### Question 413: A user wants to use an EBS-backed Amazon EC2 instance for a temporary job. Based on the input data, the job is most likely to finish within a week. Which of the following steps should be followed to terminate the instance automatically once the job is finished?
1. Configure the EC2 instance with a stop instance to terminate it.
2. Configure the EC2 instance with ELB to terminate the instance when it remains idle.
3. Configure the Cloud Watch alarm on the instance that should perform the termination action once the instance is idle.
4. Configure the Auto Scaling schedule activity that terminates the instance after 7 days.
<details>
	<summary>Answer</summary>

	3. Configure the Cloud Watch alarm on the instance that should perform the termination action once the instance is idle.

</details>

### Question 414: You are building an automated transcription service in which Amazon EC2 worker instances process an uploaded audio file and generate a text file. You must store both of these files in the same durable storage until the text file is retrieved. You do not know what the storage capacity requirements are. Which storage option is both cost-efficient and scalable?
1. Multiple Amazon EBS volume with snapshots.
2. A single Amazon Glacier vault.
3. A single Amazon S3 bucket.
4. Multiple instance stores.
<details>
	<summary>Answer</summary>

	3. A single Amazon S3 bucket.

</details>

### Question 415: Your company has recently extended its datacenter into a VPC on AVVS to add burst computing capacity as needed Members of your Network Operations Center need to be able to go to the AWSManagement Console and administer Amazon EC2 instances as necessary You don't want to create new IAM users for each NOC member and make those users sign in again to the AWS Management Console Which option below will meet the needs for your NOC members?
1. Use OAuth 2 0 to retrieve temporary AWS security credentials to enable your NOC members to sign in to the AVVS Management Console.
2. Use web Identity Federation to retrieve AWS temporary security credentials to enable your NOC members to sign in to the AWS Management Console.
3. Use your on-premises SAML 2.0-compliant identity provider (IOP) to grant the NOC members federated access to the AWS Management Console via the AWS sing le sign-on (550) endpoint.
4. Use your on-premises SAML2.0-compliam identity provider (IOP) to retrieve temporary security credentials to enable NOC members to sign in to the AWS Management Console.
<details>
	<summary>Answer</summary>

	4. Use your on-premises SAML2.0-compliam identity provider (IOP) to retrieve temporary security credentials to enable NOC members to sign in to the AWS Management Console.

</details>

### Question 416: What is the maximum response time for a Business level Premium Support case?
1. 30 minutes.
2. You always get instant responses (within a few seconds).
3. 10 minutes.
4. 1 hour.
<details>
	<summary>Answer</summary>

	4. 1 hour.

</details>

### Question 417: You have just set up your first Elastic Load Balancer (ELB) but it does not seem to be configured properly. You discover that before you start using ELB, you have to configure the listeners for your load balancer. Which protocols does ELB use to support the load balancing of applications?
1. HTTP and HTTPS.
2. HTTP, HTTPS, TCP, SSL and SSH.
3. HTTP, HTTPS, TCP, and SSL.
4. HTTP, HTTPS, TCP, SSL and SFTP.
<details>
	<summary>Answer</summary>

	3. HTTP, HTTPS, TCP, and SSL.

</details>

### Question 418: A t2.medium EC2 instance type must be launched with what type of Amazon Machine Image (AMI)?
1. An Instance store Hardware Virtual Machine AMI.
2. An Instance store Paravirtual AMI.
3. An Amazon EBS-backed Hardware Virtual Machine AMI.
4. An Amazon EBS-backed Paravirtual AMI.
<details>
	<summary>Answer</summary>

	1. An Instance store Hardware Virtual Machine AMI.

</details>

### Question 419: A user has created a subnet in VPC and launched an EC2 instance within it. The user has not selected the option to assign the IP address while launching the instance. The user has 3 elastic IPs and is trying to assign one of the Elastic IPs to the VPC instance from the console. The console does not show any instance in the IP assignment screen. What is a possible reason that the instance is unavailable in the assigned IP console?
1. The IP address may be attached to one of the instances.
2. The IP address belongs to a different zone than the subnet zone.
3. The user has not created an internet gateway.
4. The IP addresses belong to EC2 Classic; so they cannot be assigned to VPC.
<details>
	<summary>Answer</summary>

	4. The IP addresses belong to EC2 Classic; so they cannot be assigned to VPC.

</details>

### Question 420: Will I be alerted when automatic fail over occurs?
1. Only if SNS configured.
2. Yes.
3. No.
4. Only if Cloud watch configured.
<details>
	<summary>Answer</summary>

	2. Yes.

</details>

### Question 421: Amazon EC2 provides a [...]. It is an HTTP or HTTPS request that uses the HTTP verbs GET or POST.
1. web database.
2. .NET framework.
3. Query API.
4. C library.
<details>
	<summary>Answer</summary>

	3. Query API.

</details>

### Question 422: Which of the following requires a custom Cloud Watch metric to monitor?
1. Memory Utilization of an EC2 instance.
2. CPU Utilization of an EC2 instance.
3. Disk usage activity of an EC2 instance.
4. Data transfer of an EC2 instance.
<details>
	<summary>Answer</summary>

	3. Disk usage activity of an EC2 instance.

</details>

### Question 423: An International company has deployed a multi-tier web application that relies on DynamoDB in a single region For regulatory reasons they need disaster recovery capability in a separate region with a Recovery Time Objective of 2 hours and a Recovery Point Objective of 24 hours They should synchronize their data on a regular basis and be able to provision me web application rapidly using CloudFormation. The objective is to minimize changes to the existing web application, control the throughput of DynamoDB used for the synchronization of data and synchronize only the modified elements. Which design would you choose to meet these requirements?
1. Use AWS data Pipeline to schedule a DynamoDB cross region copy once a day. create a Last updated' attribute in your DynamoDB table that would represent the timestamp of the last update and use it as a filter.
2. Use EMR and write a custom script to retrieve data from DynamoDB in the current region using a SCAN operation and push it to Dynamo DB in the second region.
3. Use AWS data Pipeline to schedule an export of the DynamoDB table to S3 in the current region once a day then schedule another task immediately after it that will import data from S3 to DynamoDB in the other region.
4. Send also each Ante into an SQS queue in me second region; use an auto-scaling group behind the SQS queue to replay the write in the second region.
<details>
	<summary>Answer</summary>

	1. Use AWS data Pipeline to schedule a DynamoDB cross region copy once a day. create a Last updated' attribute in your DynamoDB table that would represent the timestamp of the last update and use it as a filter.

</details>

### Question 424: An Elastic IP address (EIP) is a static IP address designed for dynamic cloud computing. With an EIP, you can mask the failure of an instance or software by rapidly remapping the address to another instance in your account. Your EIP is associated with your AWS account, not a particular EC2 instance, and it remains associated with your account until you choose to explicitly release it. By default how many EIPs is each AWS account limited to on a per region basis?
1. 1.
2. 5.
3. Unlimited.
4. 10.
<details>
	<summary>Answer</summary>

	2. 5.

</details>

### Question 425: Which Amazon Storage behaves like raw, unformatted, external block devices that you can attach to your instances?
1. None of these.
2. Amazon Instance Storage
3. Amazon EBS
4. All of these.
<details>
	<summary>Answer</summary>

	3. Amazon EBS

</details>

### Question 426: You currently operate a web application in the AWS US-East region The application runs on an autoscaled layer of EC2 instances and an RDS Multi-AZ database Your IT security compliance officer has tasked you to develop a reliable and durable logging solution to track changes made to your EC2.1AM And RDS resources. The solution must ensure the integrity and confidentiality of your log data. Which of these solutions would you recommend?
1. Create a new CloudTrail trail with one new S3 bucket to store the logs and with the global services option selected Use IAM roles S3 bucket policies and Multi Factor Authentication (MFA) Delete on the S3 bucket that stores your logs.
2. Create a new CloudTrail with one new S3 bucket to store the logs Configure SNS to send log file delivery notifications to your management system Use IAM roles and S3 bucket policies on the S3 bucket mat stores your logs.
3. Create a new CloudTrail trail with an existing S3 bucket to store the logs and with the global services option selected Use S3 ACLs and Multi Factor Authentication (MFA) Delete on the S3 bucket that stores your logs.
4. Create three new CloudTrail trails with three new S3 buckets to store the logs one for the AWS Management console, one for AWS SDKs and one for command line tools Use IAM roles and S3 bucket policies on the S3 buckets that store your logs.
<details>
	<summary>Answer</summary>

	1. Create a new CloudTrail trail with one new S3 bucket to store the logs and with the global services option selected Use IAM roles S3 bucket policies and Multi Factor Authentication (MFA) Delete on the S3 bucket that stores your logs.

</details>

### Question 427: Does DynamoDB support in-place atomic updates?
1. Yes.
2. No.
3. It does support in-place non-atomic updates.
4. It is not defined.
<details>
	<summary>Answer</summary>

	1. Yes.

</details>

### Question 428: Which of the following is true of Amazon EC2 security group?
1. You can modify the outbound rules for EC2-Classic.
2. You can modify the rules for a security group only if the security group controls the traffic for just one instance.
3. You can modify the rules for a security group only when a new instance is created.
4. You can modify the rules for a security group at any time.
<details>
	<summary>Answer</summary>

	4. You can modify the rules for a security group at any time.

</details>

### Question 429: You need to set up security for your VPC and you know that Amazon VPC provides two features that you can use to increase security for your VPC: security groups and network access control lists (ACLs). You have already looked into security groups and you are now trying to understand ACLs. Which statement below is incorrect in relation to ACLs?
1. Supports allow rules and deny rules.
2. Is stateful: Return traffic is automatically allowed, regardless of any rules.
3. Processes rules in number order when deciding whether to allow traffic.
4. Operates at the subnet level (second layer of defense).
<details>
	<summary>Answer</summary>

	2. Is stateful: Return traffic is automatically allowed, regardless of any rules.

</details>

### Question 430: A user is trying to launch a similar EC2 instance from an existing instance with the option 'Launch More like this'. The AMI of the selected instance is deleted. What will happen in this case?
1. AWS does not need an AMI for the 'Launch more like this' option.
2. AWS will launch the instance but will not create a new AMI.
3. AWS will create a new AMI and launch the instance.
4. AWS will throw an error saying that the AMI is deregistered.
<details>
	<summary>Answer</summary>

	4. AWS will throw an error saying that the AMI is deregistered.

</details>

### Question 431: True or False: When you use the AWS Management Console to delete an IAM user, IAM also deletes any signing certificates and any access keys belonging to the user.
1. False.
2. This is configurable.
3. True.
<details>
	<summary>Answer</summary>

	3. True.

</details>

### Question 432: You are working with a customer who is using Chef configuration management in their data center. Which service is designed to let the customer leverage existing Chef recipes in AWS?
1. Amazon Simple Workflow Service.
2. AWS Elastic Beanstalk.
3. AWS CloudFormation.
4. AWS OpsWorks.
<details>
	<summary>Answer</summary>

	4. AWS OpsWorks.

</details>

### Question 433: Does Amazon RDS for SQL Server currently support importing data into the msdb database?
1. Yes.
2. No.
<details>
	<summary>Answer</summary>

	2. No.

</details>

### Question 434: How can an EBS volume that is currently attached to an EC2 instance be migrated from one Availability Zone to another?
1. Detach the volume and attach it to another EC2 instance in the other AZ.
2. Simply create a new volume in the other AZ and specify the original volume as the source.
3. Create a snapshot of the volume, and create a new volume from the snapshot in the other AZ.
4. Detach the volume, then use the ec2-migrate-voiume command to move it to another AZ.
<details>
	<summary>Answer</summary>

	3. Create a snapshot of the volume, and create a new volume from the snapshot in the other AZ.

</details>

### Question 435: Having set up a website to automatically be redirected to a backup website if it fails, you realize that there are different types of failovers that are possible. You need all your resources to be available the majority of the time. Using Amazon Route 53 which configuration would best suit this requirement?
1. Active-active failover.
2. None. Route 53 can't failover.
3. Active-passive failover.
4. Active-active-passive and other mixed configurations.
<details>
	<summary>Answer</summary>

	1. Active-active failover.

</details>

### Question 436: A client application requires operating system privileges on a relational database server. What is an appropriate configuration for a highly available database architecture?
1. A standalone Amazon EC2 instance.
2. Amazon RDS in a Multi-AZ configuration.
3. Amazon EC2 instances in a replication configuration utilizing a single Availability Zone.
4. Amazon EC2 instances in a replication configuration utilizing two different Availability Zones.
<details>
	<summary>Answer</summary>

	4. Amazon EC2 instances in a replication configuration utilizing two different Availability Zones.

</details>

### Question 437: Is decreasing the storage size of a DB Instance permitted?
1. Depends on the ROMS used.
2. Yes.
3. No.
<details>
	<summary>Answer</summary>

	2. Yes.

</details>

### Question 438: Can you encrypt EBS volumes?
1. Yes, you can enable encryption when you create a new EBS volume using the AWS Management Console, API, or CLI.
2. No, you should use a third-party software to perform raw block-level encryption of an EBS volume.
3. Yes, but you must use a third-party API for encrypting data before it's loaded on EBS.
4. Yes, you can encrypt with the special 'ebs_encrypt' command through Amazon APIs.
<details>
	<summary>Answer</summary>

	1. Yes, you can enable encryption when you create a new EBS volume using the AWS Management Console, API, or CLI.

</details>

### Question 439: You must assign each server to at least [...] security group.
1. 3.
2. 2.
3. 4.
4. 1.
<details>
	<summary>Answer</summary>

	1. 3.

</details>

### Question 440: Is the encryption of connections between my application and my DB Instance using SSL for the MySQL server engines available?
1. Yes.
2. Only in VPC.
3. Only in certain regions.
4. No.
<details>
	<summary>Answer</summary>

	1. Yes.

</details>

### Question 441: Your manager has come to you saying that he is very confused about the bills he is receiving from AWS as he is getting different bills for every user and needs you to look into making it more understandable. Which of the following would be the best solution to meet his request?
1. AWS Billing Aggregation.
2. Consolidated Billing.
3. Deferred Billing.
4. Aggregated Billing.
<details>
	<summary>Answer</summary>

	2. Consolidated Billing.

</details>

### Question 442: Regarding Amazon Route 53, if your application is running on Amazon EC2 instances in two or more Amazon EC2 regions and if you have more than one Amazon EC2 instance in one or more regions, you can use [...] to route traffic to the correct region and then use [...] route traffic to instances within the region, based on probabilities that you specify.
1. weighted-based routing; alias resource record sets.
2. latency-based routing; weighted resource record sets.
3. weighted-based routing; weighted resource record sets.
4. latency-based routing; alias resource record sets.
<details>
	<summary>Answer</summary>

	2. latency-based routing; weighted resource record sets.

</details>

### Question 443: If I scale the storage capacity provisioned to my DB Instance by mid of a billing month, how will I be charged?
1. You will be charged for the highest storage capacity you have used.
2. On a proration basis.
<details>
	<summary>Answer</summary>

	2. On a proration basis.

</details>

### Question 444: When using the following AWS services, which should be implemented in multiple Availability Zones for high availability solutions? (Choose 2 answers)
1. Amazon Dynamo DB.
2. Amazon Elastic Compute Cloud (EC2).
3. Amazon Elastic Load Balancing.
4. Amazon Simple Notification Service (SNS).
5. Amazon Simple Storage Service (S3).
<details>
	<summary>Answer</summary>

	2. Amazon Elastic Compute Cloud (EC2).
	3. Amazon Elastic Load Balancing.

</details>

### Question 445: A customer is hosting t heir company website on a cluster of web servers that are behind a public facing load balancer. The customer also uses Amazon Route 53 to manage their public DNS. How should the customer configure the DNS zone apex record to point to the load balancer?
1. Create an A record pointing to the IP address of the load balancer.
2. Create a CNAME record pointing to the load balancer DNS name.
3. Create a CNAME record aliased to the load balancer DNS name.
4. Create an A record aliased to the load balancer DNS name.
<details>
	<summary>Answer</summary>

	3. Create a CNAME record aliased to the load balancer DNS name.

</details>

### Question 446: True or False: REST or Query requests are HTTP or HTTPS requests that use an HTTP verb (such as GET or POST) and a parameter named Action or Operation that specifies the API you are calling.
1. True.
2. False.
<details>
	<summary>Answer</summary>

	2. False.

</details>

### Question 447: Which of the following features ensures even distribution of traffic to Amazon EC2 instances in multiple Availability Zones registered with a load balancer?
1. Elastic Load Balancing request routing.
2. An Amazon Route 53 weighted routing policy.
3. Elastic Load Balancing cross-zone load balancing.
4. An Amazon Route 53 latency routing pol icy.
<details>
	<summary>Answer</summary>

	1. Elastic Load Balancing request routing.

</details>

### Question 448: Groups can't [...].
1. be nested more than 3 levels.
2. be nested at all.
3. be nested more than 4 levels.
4. be nested more than 2 levels.
<details>
	<summary>Answer</summary>

	2. be nested at all.

</details>

### Question 449: You have been using T2 instances as your CPU requirements have not been that intensive. However you now start to think about larger instance types and start looking at M1 and M3 instances. You are a little confused as to the differences between them as they both seem to have the same ratio of CPU and memory. Which statement below is incorrect as to why you would use one over the other?
1. M3 instances are less expensive than M1 instances.
2. M3 instances are configured with more swap memory than M1 instances.
3. M3 instances provide better, more consistent performance that M1 instances for most use-cases.
4. M3 instances also offer SSD-based instance storage that delivers higher I/O performance.
<details>
	<summary>Answer</summary>

	2. M3 instances are configured with more swap memory than M1 instances.

</details>

### Question 450: Do the system resources on the Micro instance meet the recommended configuration for Oracle?
1. Yes, completely.
2. Yes, but only for certain situations.
<details>
	<summary>Answer</summary>

	2. Yes, but only for certain situations.

</details>

### Question 451: Which of the following are t rue regarding AWS CloudTrail? (Choose 3 answers)
1. CloudTrail is enabled globally.
2. CloudTrail is enabled by default.
3. CloudTrail is enabled on a per-region basis.
4. CloudTrail is enabled on a per-service basis.
5. Logs can be delivered to a single Amazon S3 bucket for aggregation.
6. CloudTrail is enabled for all available services within a region.
7. Logs can only be processed and delivered to the region in which they are generated.
<details>
	<summary>Answer</summary>

	3. CloudTrail is enabled on a per-region basis.
	4. CloudTrail is enabled on a per-service basis.
	5. Logs can be delivered to a single Amazon S3 bucket for aggregation.

</details>

### Question 452: If you're unable to connect via SSH to your EC2 instance, which of the following should you check and possibly correct to restore connectivity?
1. Adjust Security Group to permit egress traffic over TCP port 443 from your IP.
2. Configure the JAM role to permit changes to security group settings.
3. Modify the instance security group to allow ingress of ICMP packets from your IP.
4. Adjust the instance's Security Group to permit ingress traffic over port 22 from your IP.
5. Apply the most recently released Operating System security patches.
<details>
	<summary>Answer</summary>

	4. Adjust the instance's Security Group to permit ingress traffic over port 22 from your IP.

</details>

### Question 453: A major finance organisation has engaged your company to set up a large data mining application. Using AWS you decide the best service for this is Amazon Elastic MapReduce (EMR) which you know uses Hadoop. Which of the following statements best describes Hadoop?
1. Hadoop is 3rd Party software which can be installed using AMI.
2. Hadoop is an open source python web framework.
3. Hadoop is an open source Java software framework.
4. Hadoop is an open source javascript framework.
<details>
	<summary>Answer</summary>

	3. Hadoop is an open source Java software framework.

</details>

### Question 454: A customer has established an AWS Direct Connect connection to AWS. The link is up and routes are being advertised from the customer's end, however the customer is unable to connect from EC2 instances inside its VPC to servers residing in its datacenter. Which of the following options provide a viable solution to remedy this situation? (Choose 2 answers)
1. Add a route to the route table with an IPsec VPN connection as the target.
2. Enable route propagation to the virtual pinnate gateway (VGW).
3. Enable route propagation to the customer gateway (CGW).
4. Modify the route table of all Instances using the 'route' command.
5. Modify the Instances VPC subnet route table by adding a route back to the customer's on-premises environment.
<details>
	<summary>Answer</summary>

	2. Enable route propagation to the virtual pinnate gateway (VGW).
	5. Modify the Instances VPC subnet route table by adding a route back to the customer's on-premises environment.

</details>

### Question 455: While creating a network in the VPC, which of the following is true of a NAT device?
1. You have to administer the NAT Gateway Service provided by AW
2. You can choose to use any of the three kinds of NAT devices offered by AWS for special purposes.
3. You can use a NAT device to enable instances in a private subnet to connect to the Internet.
4. You are recommended to use AWS NAT instances over NAT gateways, as the instances provide better availability and bandwidth.
<details>
	<summary>Answer</summary>

	2. You can choose to use any of the three kinds of NAT devices offered by AWS for special purposes.

</details>

### Question 456: Which of the following statements is NOT true about using Elastic IP Address (EIP) in EC2-Classic and EC2-VPC platforms?
1. In the EC2-VPC platform, the Elastic IP Address (EIP) does not remain associated with the instance when you stop it.
2. In the EC2-Classic platform, stopping the instance disassociates the Elastic IP Address (EIP) from it.
3. In the EC2-VPC platform, if you have attached a second network interface to an instance, when you disassociate the Elastic IP Address (EIP) from that instance, a new public IP address is not assigned to the instance automatically; you'll have to associate an EIP with it manually.
4. In the EC2-Classic platform, if you disassociate an Elastic IP Address (EIP) from the instance, the instance is automatically assigned a new public IP address within a few minutes.
<details>
	<summary>Answer</summary>

	1. In the EC2-VPC platform, the Elastic IP Address (EIP) does not remain associated with the instance when you stop it.

</details>

### Question 457: A user has hosted an application on EC2 instances. The EC2 instances are configured with ELB and Auto Scaling. The application server session time out is 2 hours. The user wants to configure connection draining to ensure that all in-flight requests are supported by ELB even though the instance is being deregistered. What time out period should the user specify for connection draining?
1. 1 hour.
2. 30 minutes.
3. 5 minutes.
4. 2 hours.
<details>
	<summary>Answer</summary>

	1. 1 hour.

</details>

### Question 458: What does the following command do with respect to the Amazon EC2 security groups? ec2-create-group CreateSecurityGroup
1. Groups the user created security groups in to a new group for easy access.
2. Creates a new security group for use with your account.
3. Creates a new group inside the security group.
4. Creates a new rule inside the security group.
<details>
	<summary>Answer</summary>

	2. Creates a new security group for use with your account.

</details>

### Question 459: You are in the process of moving your friend's WordPress site onto AWS to try and save him some money, and you have told him that he should probably also move his domain name. He asks why he can't leave his domain name where it is and just have his infrastructure on AWS. What would be an incorrect response to his question?
1. Route 53 offers low query latency for your end users.
2. Route 53 is designed to automatically answer queries from the optimal location depending on network conditions.
3. The globally distributed nature of AWS's DNS servers helps ensure a consistent ability to route your end users to your application.
4. Route 53 supports Domain Name System Security Extensions (DNSSEC).
<details>
	<summary>Answer</summary>

	4. Route 53 supports Domain Name System Security Extensions (DNSSEC).

</details>

### Question 460: Which of the following are characteristics of a reserved instance? (Choose 3 answers)
1. It can be migrated across Availability Zones.
2. It is specific to an Amazon Machine Image (AMI).
3. It can be applied to instances launched by Auto Scaling.
4. It is specific to an instance Type.
5. It can be used to lower Total Cost of Ownership (TCO) of a system.
<details>
	<summary>Answer</summary>

	1. It can be migrated across Availability Zones.
	4. It is specific to an instance Type.
	5. It can be used to lower Total Cost of Ownership (TCO) of a system.

</details>

### Question 461: A user has defined an AutoScaling termination policy to first delete the instance with the nearest billing hour. AutoScaling has launched 3 instances in the US-East-1A region and 2 instances in the US-East-1B region. One of the instances in the US-East-1B region is running nearest to the billing hour. Which instance will AutoScaling terminate first while executing the termination action?
1. Random Instance from US-East-1A.
2. Instance with the nearest billing hour in US-East-1B.
3. Instance with the nearest billing hour in US-East-1A.
4. Random instance from US-East-1B.
<details>
	<summary>Answer</summary>

	3. Instance with the nearest billing hour in US-East-1A.

</details>

### Question 462: You have an environment that consists of a public subnet using Amazon VPC and 3 instances that are running in this subnet. These three instances can successfully communicate with other hosts on the Internet. You launch a fourth instance in the same subnet, using the same AMI and security group configuration you used for the others, but find that this instance cannot be accessed from the internet. What should you do to enable Internet access?
1. Deploy a NAT instance into the public subnet.
2. Assign an Elastic IP address to the fourth instance.
3. Configure a publically routable IP Address in the host OS of the fourth instance.
4. Modify the routing table for the public subnet.
<details>
	<summary>Answer</summary>

	2. Assign an Elastic IP address to the fourth instance.

</details>

### Question 463: What does the 'Server Side Encryption' option on Amazon S3 provide?
1. It provides an encrypted virtual disk in the Cloud.
2. It doesn't exist for Amazon S3, but only for Amazon EC2.
3. It encrypts the files that you send to Amazon S3, on the server side.
4. It allows to upload fi les using an SSL endpoint, for a secure transfer.
<details>
	<summary>Answer</summary>

	1. It provides an encrypted virtual disk in the Cloud.

</details>

### Question 464: What is a placement group?
1. A collection of Auto Scaling groups in the same region.
2. A feature that enables EC2 instances to interact with each other via high bandwidth, low latency connections.
3. A collection of authorized CloudFront edge locations for a distribution.
4. A collection of Elastic Load Balancers in the same Region or Availability Zone.
<details>
	<summary>Answer</summary>

	2. A feature that enables EC2 instances to interact with each other via high bandwidth, low latency connections.

</details>

### Question 465: You are checking the workload on some of your General Purpose (SSD) and Provisioned IOPS (SSD) volumes and it seems that the I/O latency is higher than you require. You should probably check the [...] to make sure that your application is not trying to drive more IOPS than you have provisioned.
1. amount of IOPS that are available.
2. acknowledgement from the storage subsystem.
3. average queue length.
4. time it takes for the I/O operation to complete.
<details>
	<summary>Answer</summary>

	3. average queue length.

</details>

### Question 466: Within the IAM service a GROUP is regarded as a:
1. A collection of AWS accounts.
2. It's the group of EC2 machines that gain t he permissions specified in the GROUP.
3. There's no GROUP in IAM, but only USERS and RESOURCES.
4. A collection of users.
<details>
	<summary>Answer</summary>

	4. A collection of users.

</details>

### Question 467: Doug has created a VPC with CIDR 10.201.0.0/16 in his AWS account. in this VPC he has created a public subnet with CIDR block 10.201.31.0/24. While launching a new EC2 from the console, he is not able to assign the private IP address 10.201.31.6 to this instance. Which is the most likely reason for this issue?
1. Private IP address 10.201.31.6 is blocked via ACLs in Amazon infrastructure as a part of platform security.
2. Private address IP 10.201.31.6 is currently assigned to another interface.
3. Private IP address 10.201.31.6 is not part of the associated subnet's IP address range.
4. Private IP address 10.201.31.6 is reserved by Amazon for IP networking purposes.
<details>
	<summary>Answer</summary>

	2. Private address IP 10.201.31.6 is currently assigned to another interface.

</details>

### Question 468: A user is planning to make a mobile game which can be played online or offline and will be hosted on EC2. The user wants to ensure that if someone breaks the highest score or they achieve some milestone they can inform all their colleagues through email. Which of the below mentioned AWS services helps achieve this goal?
1. AWS Simple Workflow Service.
2. AWS Simple Email Service.
3. Amazon Cognito.
4. AWS Simple Queue Service.
<details>
	<summary>Answer</summary>

	2. AWS Simple Email Service.

</details>

### Question 469: Is creating a Read Replica of another Read Replica supported?
1. Only in VPC.
2. Yes.
3. Only in certain regions.
4. No.
<details>
	<summary>Answer</summary>

	4. No.

</details>

### Question 470: Which of the following is NOT a characteristic of Amazon Elastic Compute Cloud (Amazon EC2)?
1. It can be used to launch as many or as few virtual servers as you need.
2. It increases the need to forecast traffic by providing dynamic IP addresses for static cloud computing.
3. It eliminates your need to invest in hardware up front, so you can develop and deploy applications faster.
4. It offers scalable computing capacity in the Amazon Web Services (AWS) cloud.
<details>
	<summary>Answer</summary>

	2. It increases the need to forecast traffic by providing dynamic IP addresses for static cloud computing.

</details>

### Question 471: A user has launched one EC2 instance in the US East region and one in the US West region. The user has launched an RDS instance in the US East region. How can the user configure access from both the EC2 instances to RDS?
1. It is not possible to access RDS of the US East region from the US West region.
2. Configure the US West region's security group to allow a request from the US East region's instance and configure the RDS security group's ingress rule for the US East EC2 group.
3. Configure the security group of the US East region to allow traffic from the US West region's instance and configure the RDS security group's ingress rule for the US East EC2 group.
4. Configure the security group of both instances in the ingress rule of the RDS security group.
<details>
	<summary>Answer</summary>

	3. Configure the security group of the US East region to allow traffic from the US West region's instance and configure the RDS security group's ingress rule for the US East EC2 group.

</details>

### Question 472: What happens to the 1/0 operations while you take a database snapshot?
1. 1/0 operations to the database are suspended for an hour while the backup is in progress.
2. 1/0 operations to the database are sent to a Replica (if available) for a few minutes while the backup is in progress.
3. 1/0 operations will be functioning normally.
4. 1/0 operations to the database are suspended for a few minutes while the backup is in progress.
<details>
	<summary>Answer</summary>

	4. 1/0 operations to the database are suspended for a few minutes while the backup is in progress.

</details>

### Question 473: When an EC2 EBS-backed (EBS root) instance is stopped, what happens to the data on any ephemeral store volumes?
1. Data is automatically saved in an EBS volume.
2. Data is unavailable until the instance is restarted.
3. Data will be deleted and will no longer be accessible.
4. Data is automatically saved as an EBS snapshot.
<details>
	<summary>Answer</summary>

	2. Data is unavailable until the instance is restarted.

</details>

### Question 474: [...] is a durable, block-level storage volume that you can attach to a single, running Amazon EC2 instance.
1. Amazon S3.
2. Amazon EBS.
3. None of these.
4. All of these.
<details>
	<summary>Answer</summary>

	2. Amazon EBS.

</details>

### Question 475: A favored client needs you to quickly deploy a database that is a relational database service with minimal administration as he wants to spend the least amount of time administering it. Which database would be the best option?
1. Amazon SimpleDB.
2. Your choice of relational AMIs on Amazon EC2 and EB.
3. Amazon RDS.
4. Amazon Redshift.
<details>
	<summary>Answer</summary>

	3. Amazon RDS.

</details>

### Question 476: You have a number of image files to encode. in an Amazon SQS worker queue, you create an Amazon SQS message for each file specifying the command (jpeg-encode) and the location of the file in Amazon S3. Which of the following statements best describes the functionality of Amazon SQS?
1. Amazon SQS is a distributed queuing system that is optimized for horizontal scalability, not for single-threaded sending or receiving speeds.
2. Amazon SQS is for single-threaded sending or receiving speeds.
3. Amazon SQS is a non-distributed queuing system.
4. Amazon SQS is a distributed queuing system that is optimized for vertical scalability and for single-threaded sending or receiving speeds.
<details>
	<summary>Answer</summary>

	1. Amazon SQS is a distributed queuing system that is optimized for horizontal scalability, not for single-threaded sending or receiving speeds.

</details>

### Question 477: While creating an Amazon RDS DB, your first task is to set up a DB [...] that controls what IP addresses or EC2 instances have access to your DB Instance.
1. Security Pool.
2. Secure Zone.
3. Security Token Pool.
4. Security Group.
<details>
	<summary>Answer</summary>

	4. Security Group.

</details>

### Question 478: What happens to the 1/0 operations while you take a database snapshot?
1. 1/0 operations to the database are suspended for a few minutes while the backup is in progress.
2. 1/0 operations to the database are sent to a Replica (if available) for a few minutes while the backup is in progress.
3. 1/0 operations will be functioning normally.
4. 1/0 operations to the database are suspended for an hour while the backup is in progress.
<details>
	<summary>Answer</summary>

	1. 1/0 operations to the database are suspended for a few minutes while the backup is in progress.

</details>

### Question 479: After launching an instance that you intend to serve as a NAT (Network Address Translation) device in a public subnet you modify your route tables to have the NAT device be the target of internet bound traffic of your private subnet. When you try and make an outbound connection to the internet from an instance in the private subnet, you are not successful. Which of the following steps could resolve the issue?
1. Disabling the Source/Destination Check attribute on the NAT instance.
2. Attaching an Elastic IP address to the instance in the private subnet.
3. Attaching a second Elastic Network Interface (EN I) to the NAT instance, and placing it in the private subnet.
4. Attaching a second Elastic Network Interface (ENI) to the instance in the private subnet, and placing it in the public subnet.
<details>
	<summary>Answer</summary>

	1. Disabling the Source/Destination Check attribute on the NAT instance.

</details>

### Question 480: Which of the following would you use to list your AWS Import/Export jobs?
1. Amazon RDS.
2. AWS Import/Export Web Service Tool.
3. Amazon S3 REST API.
4. AWS Elastic Beanstalk.
<details>
	<summary>Answer</summary>

	3. Amazon S3 REST API.

</details>

### Question 481: Company B is launching a new game app for mobile devices. Users will log into the game using their existing social media account to streamline data capture. Company B would like to directly save player data and scoring information from the mobile app to a DynamoDS table named Score Data. When a user saves their game the progress data will be stored to the Game state S3 bucket. What is the best approach for storing data to DynamoDB and S3?
1. Use an EC2 Instance that is launched with an EC2 role providing access to the Score Data DynamoDB table and the GameState S3 bucket that communicates with the mobile app via web services.
2. Use temporary security credentials that assume a role providing access to the Score Data DynamoDB table and the Game State S3 bucket using web identity federation.
3. Use Login with Amazon allowing users to sign in with an Amazon account providing the mobile app with access to the Score Data DynamoDB table and the Game State S3 bucket.
4. Use an IAM user with access credentials assigned a role providing access to the Score Data DynamoDB table and the Game State S3 bucket for distribution with the mobile app.
<details>
	<summary>Answer</summary>

	2. Use temporary security credentials that assume a role providing access to the Score Data DynamoDB table and the Game State S3 bucket using web identity federation.

</details>

### Question 482: If your DB instance runs out of storage space or file system resources, its status will change to [...] and your DB Instance will no longer be available.
1. storage-overflow.
2. storage-full.
3. storage-exceed.
4. storage-overage.
<details>
	<summary>Answer</summary>

	2. storage-full.

</details>

### Question 483: Your application is using an ELB in front of an Auto Scaling group of web/application servers deployed across two AZs and a Multi-AZ RDS Instance for data persistence. The database CPU is often above 80% usage and 90% of 1/0 operations on the database are reads. To improve performance you recently added a single-node Memcached ElastiCache Cluster to cache frequent DB query results. in the next weeks the overall workload is expected to grow by 30%. Do you need to change anything in the architecture to maintain the high availability or the application with the anticipated additional load? Why?
1. Yes, you should deploy two Memcached ElastiCache Clusters in different AZs because the RDS instance will not be able to handle the load if the cache node fails.
2. No, if the cache node fails you can always get the same data from the DB without having any availability impact.
3. No, if the cache node fails the automated ElastiCache node recovery feature will prevent any availability impact.
4. Yes, you should deploy the Memcached ElastiCache Cluster with two nodes in the same AZ as the RDS DB master instance to handle the load if one cache node fails.
<details>
	<summary>Answer</summary>

	1. Yes, you should deploy two Memcached ElastiCache Clusters in different AZs because the RDS instance will not be able to handle the load if the cache node fails.

</details>

### Question 484: How many Elastic IP by default in Amazon Account?
1. 1 Elastic IP.
2. 3 Elastic IP.
3. 5 Elastic IP.
4. 0 Elastic IP.
<details>
	<summary>Answer</summary>

	4. 0 Elastic IP.

</details>

### Question 485: What would be the best way to retrieve the public IP address of your EC2 instance using the CLI?
1. Using tags.
2. Using traceroute.
3. Using ipconfig.
4. Using instance metadata.
<details>
	<summary>Answer</summary>

	4. Using instance metadata.

</details>

### Question 486: A company is building a two-tier web application to serve dynamic transaction-based content. The data tier is leveraging an Online Transactional Processing (OLTP) database. What services should you leverage to enable an elastic and scalable web tier?
1. Elastic Load Balancing, Amazon EC2, and Auto Scaling.
2. Elastic Load Balancing, Amazon RDS with Multi-AZ, and Amazon S3.
3. Amazon RDS with Multi-AZ and Auto Scaling.
4. Amazon EC2, Amazon DynamoDB, and Amazon S3.
<details>
	<summary>Answer</summary>

	1. Elastic Load Balancing, Amazon EC2, and Auto Scaling.

</details>

### Question 487: You are designing a connectivity solution between on-premises infrastructure and Amazon VPC. Your server's on-premises will De communicating with your VPC instances. You will De establishing IPSec tunnels over the internet You will be using VPN gateways and terminating the IPsec tunnels on AWS supported customer gateways. Which of the following objectives would you achieve by implementing an IPSec tunnel as outlined above? (Choose 4 answers)
1. End-to-end protection of data in transit.
2. End-to-end Identity authentication.
3. Data encryption across the Internet.
4. Protection of data in transit over the Internet.
5. Peer identity authentication between VPN gateway and customer gateway.
6. Data integrity protection across the Internet.
<details>
	<summary>Answer</summary>

	3. Data encryption across the Internet.
	4. Protection of data in transit over the Internet.
	5. Peer identity authentication between VPN gateway and customer gateway.
	6. Data integrity protection across the Internet.

</details>

### Question 488: You have been storing massive amounts of data on Amazon Glacier for the past 2 years and now start to wonder if there are any limitations on this. What is the correct answer to your question?
1. The total volume of data is limited but the number of archives you can store are unlimited.
2. The total volume of data is unlimited but the number of archives you can store are limited.
3. The total volume of data and number of archives you can store are unlimited.
4. The total volume of data is limited and the number of archives you can store are limited.
<details>
	<summary>Answer</summary>

	3. The total volume of data and number of archives you can store are unlimited.

</details>

### Question 489: How are the EBS snapshots saved on Amazon S3?
1. Exponentially.
2. Incrementally.
3. EBS snapshots are not stored in the Amazon S3.
4. Decrementally.
<details>
	<summary>Answer</summary>

	2. Incrementally.

</details>

### Question 490: An online gaming site asked you if you can deploy a database that is a fast, highly scalable NoSQL database service in AWS for a new site that he wants to build. Which database should you recommend?
1. Amazon DynamoDB.
2. Amazon RDS.
3. Amazon Redshift.
4. Amazon SimpleDB.
<details>
	<summary>Answer</summary>

	1. Amazon DynamoDB.

</details>

### Question 491: You have three Amazon EC2 instances with Elastic IP addresses in the US East (Virginia) region, and you want to distribute requests across all three IPs evenly for users for whom US East (Virginia) is the appropriate region. How many EC2 instances would be sufficient to distribute requests in other regions?
1. 3.
2. 9.
3. 2.
4. 1.
<details>
	<summary>Answer</summary>

	4. 1.

</details>

### Question 492: You are the new IT architect in a company that operates a mobile sleep tracking application. When activated at night, the mobile app is sending collected data points of 1 kilobyte every 5 minutes to your backend. The backend takes care of authenticating the user and writing the data points into an Amazon DynamoDB table. Every morning, you scan the table to extract and aggregate last night's data on a per user basis, and store the results in Amazon S3. Users are notified via Amazon 5M5 mobile push notifications that new data is available, which is parsed and visualized by The mobile app Currently you have around lOOk users who are mostly based out of North America. You have been tasked to optimize the architecture of the backend system to lower cost what would you recommend? (Choose 2 answers)
1. Create a new Amazon DynamoDB able each day and drop the one for the previous day after its data is on Amazon S3.
2. Have the mobile app access Amazon DynamoDB directly instead of J50N files stored on Amazon S3.
3. Introduce an Amazon SQS queue to buffer writes to the Amazon DynamoDB table and reduce provisioned write throughput.
4. Introduce Amazon Elasticache to cache reads from the Amazon DynamoDB table and reduce provisioned read throughput.
5. Write data directly into an Amazon Redshift cluster replacing both Amazon DynamoDB and Amazon S3.
<details>
	<summary>Answer</summary>

	1. Create a new Amazon DynamoDB able each day and drop the one for the previous day after its data is on Amazon S3.
	3. Introduce an Amazon SQS queue to buffer writes to the Amazon DynamoDB table and reduce provisioned write throughput.

</details>

### Question 493: You are implementing a URL whitelisting system for a company that wants to restrict outbound HTTP'S connections to specific domains from their EC2-hosted applications you deploy a single EC2 instance running proxy software and configure It to accept traffic from all subnets and EC2 instances in the VPC. You configure the proxy to only pass through traffic to domains that you define in its whitelist configuration You have a nightly maintenance window or 10 minutes where all instances fetch new software updates. Each update Is about 200MB in size and there are 500 instances in theVPC that routinely fetch updates After a few days you notice that some machines are failing to successfully download some, but not all of their updates within the maintenance window. The download URLs used for these updates are correctly listed in the proxy's whitelist configuration and you are able to access them manually using a web browser on the instances. What might be happening? (Choose 2 answers)
1. You are running the proxy on an undersized EC2 instance type so network throughput is not sufficient for all instances to download their updates in time.
2. You are running the proxy on a sufficiently-sized EC2 instance in a private subnet and its network throughput is being throttled by a NAT running on an undersized EC2 instance.
3. The route table for the subnets containing the affected EC2 instances is not configured to direct network traffic for the software update locations to the proxy.
4. You have not allocated enough storage to t he EC2 instance running the proxy so the network buffer is filling up, causing some requests to fail.
5. You are running the proxy in a public subnet but have not allocated enough EIPs to support the needed network throughput through the Internet Gateway (IGW).
<details>
	<summary>Answer</summary>

	1. You are running the proxy on an undersized EC2 instance type so network throughput is not sufficient for all instances to download their updates in time.
	2. You are running the proxy on a sufficiently-sized EC2 instance in a private subnet and its network throughput is being throttled by a NAT running on an undersized EC2 instance.

</details>

### Question 494: You are playing around with setting up stacks using JSON templates in CloudFormation to try and understand them a little better. You have set up about 5 or 6 but now start to wonder if you are being charged for these stacks. What is AWS's billing policy regarding stack resources?
1. You are not charged for the stack resources if they are not taking any traffic.
2. You are charged for the stack resources for the time they were operating (even if you deleted the stack right away).
3. You are charged for the stack resources for the time they were operating (but not if you deleted the stack within 60 minutes).
4. You are charged for the stack resources for the time they were operating (but not if you deleted the stack within 30 minutes).
<details>
	<summary>Answer</summary>

	2. You are charged for the stack resources for the time they were operating (even if you deleted the stack right away).

</details>

### Question 495: What does Amazon Cloud Formation provide?
1. The ability to setup Autoscaling for Amazon EC2 instances.
2. None of these.
3. A templated resource creation for Amazon Web Services.
4. A template to map network resources for Amazon Web Services.
<details>
	<summary>Answer</summary>

	4. A template to map network resources for Amazon Web Services.

</details>

### Question 496: You are signed in as root user on your account but there is an Amazon S3 bucket under your account that you cannot access. What is a possible reason for this?
1. An IAM user assigned a bucket policy to an Amazon S3 bucket and didn't specify the root user as a principal
2. The S3 bucket is full.
3. The S3 bucket has reached the maximum number of objects allowed.
4. You are in the wrong Availability Zone.
<details>
	<summary>Answer</summary>

	1. An IAM user assigned a bucket policy to an Amazon S3 bucket and didn't specify the root user as a principal

</details>

### Question 497: When creation of an EBS snapshot is initiated, but not completed, the EBS volume?
1. Can be used while the snapshot is in progress.
2. Cannot be detached or attached to an EC2 instance until the snapshot completes.
3. Can be used in read-only mode while the snapshot is in progress.
4. Cannot be used until the snapshot completes.
<details>
	<summary>Answer</summary>

	4. Cannot be used until the snapshot completes.

</details>

### Question 498: What does Amazon SES stand for?
1. Simple Elastic Server.
2. Simple Email Service.
3. Software Email Solution.
4. Software Enabled Server.
<details>
	<summary>Answer</summary>

	2. Simple Email Service.

</details>

### Question 499: You receive a bill from AWS but are confused because you see you are incurring different costs for the exact same storage size in different regions on Amazon S3. You ask AWS why this is so. What response would you expect to receive from AWS?
1. We charge less in different time zones.
2. We charge less where our costs are less.
3. This will balance out next bill.
4. It must be a mistake.
<details>
	<summary>Answer</summary>

	2. We charge less where our costs are less.

</details>

### Question 500: Disabling automated backups [...] disable the point-in-time recovery.
1. if configured to can.
2. will never.
3. will.
<details>
	<summary>Answer</summary>

	3. will.

</details>

### Question 501: A user has launched a large EBS backed EC2 instance in the US-East-1a region. The user wants to achieve Disaster Recovery (DR) for that instance by creating another small instance in Europe. How can the user achieve DR?
1. Copy the instance from the US East region to the EU region.
2. Use the 'Launch more like this' option to copy the instance from one region to another.
3. Copy the running instance using the 'Instance Copy' command to the EU region.
4. Create an AMI of the instance and copy the AMI to the EU region. Then launch the instance from the EU AMI.
<details>
	<summary>Answer</summary>

	4. Create an AMI of the instance and copy the AMI to the EU region. Then launch the instance from the EU AMI.

</details>

### Question 502: How many relational database engines does RDS currently support?
1. Three: MySQL, Oracle and Microsoft SQL Server.
2. Just two: MySQL and Oracle.
3. Five: MySQL, PostgreSQL, MongoDB, Cassandra and SQLite.
4. Just one: MySQL.
<details>
	<summary>Answer</summary>

	1. Three: MySQL, Oracle and Microsoft SQL Server.

</details>

### Question 503: Are you able to integrate a multi-factor token service with the AWS Platform?
1. Yes, you can integrate private multi-factor token devices to authenticate users to the AWS platform.
2. No, you cannot integrate multi-factor token devices with the AWS platform.
3. Yes, using the AWS multi-factor token devices to authenticate users on the AWS platform.
<details>
	<summary>Answer</summary>

	3. Yes, using the AWS multi-factor token devices to authenticate users on the AWS platform.

</details>

### Question 504: What is the default maximum number of MFA devices in use per AWS account (at the root account level)?
1. 1.
2. 5.
3. 15.
4. 10.
<details>
	<summary>Answer</summary>

	1. 1.

</details>

### Question 505: Select the correct statement: Within Amazon EC2, when using Linux instances, the device name /dev/sda1 is [...].
1. reserved for EBS volumes.
2. recommended for EBS volumes.
3. recommended for instance store volumes.
4. reserved for the root device.
<details>
	<summary>Answer</summary>

	4. reserved for the root device.

</details>

### Question 506: Does Amazon Route 53 support NS Records?
1. Yes, it supports Name Service records.
2. No.
3. It supports only MX records.
4. Yes, it supports Name Server records.
<details>
	<summary>Answer</summary>

	4. Yes, it supports Name Server records.

</details>

### Question 507: Your web application front end consists of multiple EC2 instances behind an Elastic Load Balancer. You configured ELB to perform health checks on these EC2 instances, if an instance fails to pass health checks, which statement will be true?
1. The instance gets terminated automatically by the ELB.
2. The instance gets quarantined by the ELB for root cause analysis.
3. The instance is replaced automatically by the ELB.
4. The ELB stops sending traffic to the instance that failed its health check.
<details>
	<summary>Answer</summary>

	4. The ELB stops sending traffic to the instance that failed its health check.

</details>

### Question 508: George has launched three EC2 instances inside the US-East-1a zone with his AWS account. Ray has launched two EC2 instances in the US-East-1a zone with his AWS account. Which of the below mentioned statements will help George and Ray understand the Availability Zone (AZ) concept better?
1. All the instances of George and Ray can communicate over a private IP with a minimal cost.
2. The US-East-1a region of George and Ray can be different Availability Zones.
3. All the instances of George and Ray can communicate over a private IP without any cost.
4. The instances of George and Ray will be running in the same data centre.
<details>
	<summary>Answer</summary>

	2. The US-East-1a region of George and Ray can be different Availability Zones.

</details>

### Question 509: Once again your customers are concerned about the security of their sensitive data and with their latest enquiry ask about what happens to old storage devices on AWS. What would be the best answer to this question?
1. AWS reformats the disks and uses them again.
2. AWS uses the techniques detailed in DoD 5220.22-M to destroy data as part of the decommissioning process.
3. AWS uses their own proprietary software to destroy data as part of the decommissioning process.
4. AWS uses a 3rd party security organization to destroy data as part of the decommissioning process.
<details>
	<summary>Answer</summary>

	2. AWS uses the techniques detailed in DoD 5220.22-M to destroy data as part of the decommissioning process.

</details>

### Question 510: Which of the following are characteristics of Amazon VPC subnets? (Choose 2 answers)
1. Each subnet spans at least 2 Availability Zones to provide a high-availability environment.
2. Each subnet maps to a single Availability Zone.
3. CIDR block mask of/25 is the smallest range supported.
4. By default, all subnets can route between each other, whether they are private or public.
5. Instances in a private subnet can communicate with the Internet only if they have an Elastic IP.
<details>
	<summary>Answer</summary>

	2. Each subnet maps to a single Availability Zone.
	5. Instances in a private subnet can communicate with the Internet only if they have an Elastic IP.

</details>

### Question 511: Which AWS instance address has the following characteristics? 'If you stop an instance, its Elastic IP address is unmapped, and you must remap it when you restart the instance.'
1. Both A and B.
2. None of these.
3. VPC Addresses.
4. EC2 Addresses.
<details>
	<summary>Answer</summary>

	4. EC2 Addresses.

</details>

### Question 512: You are designing a data leak prevention solution for your VPC environment. You want your VPC Instances to be able to access software depots and distributions on the Internet for product updates. The depots and distributions are accessible via third party CONs by their URLs. You want to explicitly deny any other outbound connections from your VPC instances to hosts on the internet. Which of the following options would you consider?
1. Configure a web proxy server in your VPC and enforce URL-based ru les for outbound access Remove default routes.
2. Implement security groups and configure outbound rules to only permit traffic to software depots.
3. Move all your instances into private VPC subnets remove default routes from all routing tables and add specific routes to the software depots and distributions only.
4. Implement network access control lists to all specific destinations, with an Implicit deny as a rule.
<details>
	<summary>Answer</summary>

	1. Configure a web proxy server in your VPC and enforce URL-based ru les for outbound access Remove default routes.

</details>

### Question 513: What is an isolated database environment running in the cloud (Amazon RDS) called?
1. DB Instance.
2. DB Unit.
3. DB Server.
4. DB Volume.
<details>
	<summary>Answer</summary>

	1. DB Instance.

</details>

### Question 514: A user is sending bulk emails using AWS SES. The emails are not reaching some of the targeted audience because they are not authorized by the ISPs. How can the user ensure that the emails are all delivered?
1. Send an email using DKIM with SE.
2. Send an email using SMTP with SE.
3. Open a ticket with AWS support to get it authorized with the IS.
4. Authorize the ISP by sending emails from the development account.
<details>
	<summary>Answer</summary>

	1. Send an email using DKIM with SE.

</details>

### Question 515: What's an ECU?
1. Extended Cluster User.
2. None of these.
3. Elastic Computer Usage.
4. Elastic Compute Unit.
<details>
	<summary>Answer</summary>

	4. Elastic Compute Unit.

</details>

### Question 516: You would like to create a mirror image of your production environment in another region for disaster recovery purposes. Which of the following AWS resources do not need to be recreated in the second region? (Choose 2 answers)
1. Route 53 Record Sets.
2. IAM Roles.
3. Elastic IP Addresses (EIP).
4. EC2 Key Pairs.
5. Launch configurations.
6. Security Groups.
<details>
	<summary>Answer</summary>

	1. Route 53 Record Sets.
	2. IAM Roles.

</details>

### Question 517: Which procedure for backing up a relational database on EC2 that is using a set of RAIDed EBS volumes for storage minimizes the time during which the database cannot be written to and results in a consistent backup?
1. 1. Detach EBS volumes, 2. Start EBS snapshot of volumes, 3. Re-attach EBS volumes.
2. 1. Stop the EC2 Instance. 2. Snapshot the EBS volumes.
3. 1. Suspend disk 1/0, 2. Create an image of the EC2 Instance, 3. Resume disk 1/0.
4. 1. Suspend disk 1/0, 2. Start EBS snapshot of volumes, 3. Resume disk 1/0.
5. 1. Suspend disk 1/0, 2. Start EBS snapshot of volumes, 3. Wait for snapshots to complete, 4. Resume disk 1/0.
<details>
	<summary>Answer</summary>

	1. 1. Detach EBS volumes, 2. Start EBS snapshot of volumes, 3. Re-attach EBS volumes.

</details>

### Question 518: My Read Replica appears 'stuck' after a Multi-AZ failover and is unable to obtain or apply updates from the source DB Instance. What do I do?
1. You will need to delete the Read Replica and create a new one to rep lace it.
2. You will need to disassociate the DB Engine and re associate it.
3. The instance should be deployed to Single AZ and then moved to Multi-AZ once again.
4. You will need to delete the DB Instance and create a new one to replace it.
<details>
	<summary>Answer</summary>

	1. You will need to delete the Read Replica and create a new one to rep lace it.

</details>

### Question 519: You are setting up some IAM user policies and have also become aware that some services support resource-based permissions, which let you attach policies to the service's resources instead of to IAM users or groups. Which of the below statements is true in regards to resource-level permissions?
1. All services support resource-level permissions for all actions.
2. Resource-level permissions are supported by Amazon CloudFront.
3. All services support resource-level permissions only for some actions.
4. Some services support resource-level permissions only for some actions.
<details>
	<summary>Answer</summary>

	4. Some services support resource-level permissions only for some actions.

</details>

### Question 520: You have some very sensitive data stored on AWS S3 and want to try every possible alternative to keeping it secure in regards to access control. What are the mechanisms available for access control on AWS S3?
1. (IAM) policies, Access Control Lists (ACLs), bucket policies, and query string authentication.
2. (IAM) policies, Access Control Lists (ACLs) and bucket policies.
3. Access Control Lists (ACLs), bucket policies, and query string authentication.
4. (IAM) policies, Access Control Lists (ACLs), bucket policies, query string authentication and encryption.
<details>
	<summary>Answer</summary>

	1. (IAM) policies, Access Control Lists (ACLs), bucket policies, and query string authentication.

</details>

### Question 521: You are implementing AWS Direct Connect. You intend to use AWS public service end points such as Amazon S3, across the AWS Direct Connect link. You want other Internet traffic to use your existing link to an Internet Service Provider. What is the correct way to configure AWS Direct connect for access to services such as Amazon S3?
1. Configure a public Interface on your AWS Direct Connect link. Configure a static route via your AWS Direct Connect link that points to Amazon S3 Advertise a default route to AWS using BGP.
2. Create a private interface on your AWS Direct Connect link. Configure a static route via your AWS Direct connect link that points to Amazon S3 Configure specific routes to your network in your VPC.
3. Create a public interface on your AWS Direct Connect link. Redistribute BGP routes into your existing routing infrastructure; advertise specific routes for your network to AWS.
4. Create a private interface on your AWS Direct connect link. Redistribute BGP routes into your existing routing infrastructure and advertise a default route to AWS.
<details>
	<summary>Answer</summary>

	3. Create a public interface on your AWS Direct Connect link. Redistribute BGP routes into your existing routing infrastructure; advertise specific routes for your network to AWS.

</details>

### Question 522: What is the charge for the data transfer incurred in replicating data between your primary and standby?
1. No charge. It is free.
2. Double the standard data transfer charge.
3. Same as the standard data transfer charge.
4. Half of the standard data transfer charge.
<details>
	<summary>Answer</summary>

	3. Same as the standard data transfer charge.

</details>

### Question 523: You are setting up your first Amazon Virtual Private Cloud (Amazon VPC) network so you decide you should probably use the AWS Management Console and the VPC Wizard. Which of the following is not an option for network architectures after launching the 'Start VPC Wizard' in Amazon VPC page on the AWS Management Console?
1. VPC with a Single Public Subnet Only.
2. VPC with a Public Subnet Only and Hardware VPN Access.
3. VPC with Public and Private Subnets and Hardware VPN Access.
4. VPC with a Private Subnet Only and Hardware VPN Access.
<details>
	<summary>Answer</summary>

	2. VPC with a Public Subnet Only and Hardware VPN Access.

</details>

### Question 524: True or False: A VPC contains multiple subnets, where each subnet can span multiple Availability Zones.
1. This is true only if requested during the set-up of VPC.
2. This is true.
3. This is false.
4. This is true only for US regions.
<details>
	<summary>Answer</summary>

	2. This is true.

</details>

### Question 525: Amazon RDS automated backups and DB Snapshots are currently supported for only the [...] storage engine.
1. InnoDB.
2. MyISAM.
<details>
	<summary>Answer</summary>

	1. InnoDB.

</details>

### Question 526: While signing in REST/ Query requests, for additional security, you should transmit your requests using Secure Sockets Layer (SSL) by using [...].
1. HTTP.
2. Internet Protocol Security (IPsec).
3. TLS (Transport Layer Security).
4. HTTPS.
<details>
	<summary>Answer</summary>

	4. HTTPS.

</details>

### Question 527: Out of the stripping options available for the EBS volumes, which one has the following disadvantage: 'Doubles the amount of 1/0 required from the instance to EBS compared to RAID 0, because you're mirroring all writes to a pair of volumes, limiting how much you can stripe.'?
1. Raid 0.
2. RAID 1+0 (RAID 10).
3. Raid 1.
4. Raid.
<details>
	<summary>Answer</summary>

	2. RAID 1+0 (RAID 10).

</details>

### Question 528: Can I encrypt connections between my application and my DB Instance using SSL?
1. Yes.
2. Only in VPC.
3. Only in certain regions.
<details>
	<summary>Answer</summary>

	1. Yes.

</details>

### Question 529: Which of the following items are required to allow an application deployed on an EC2 instance to write data to a DynamoDB table? Assume that no security keys are allowed to be stored on the EC2 instance. (Choose 3 answers)
1. Create an IAM Role that allows write access to the DynamoDB table.
2. Add an IAM Role to a running EC2 instance.
3. Create an IAM User that al lows write access to the Dynamo DB table.
4. Add an IAM User to a running EC2 instance.
5. Launch an EC2 Instance with the IAM Role included in the launch configuration.
<details>
	<summary>Answer</summary>

	1. Create an IAM Role that allows write access to the DynamoDB table.
	2. Add an IAM Role to a running EC2 instance.
	5. Launch an EC2 Instance with the IAM Role included in the launch configuration.

</details>

### Question 530: Identify a true statement about the On-Demand instances purchasing option provided by Amazon EC2.
1. Pay for the instances that you use by the hour, with no long-term commitments or up-front payments.
2. Make a low, one-time, up-front payment for an instance, reserve it for a one- or three-year term, and pay a significantly lower hourly rate for these instances.
3. Pay for the instances that you use by the hour, with long-term commitments or up-front payments.
4. Make a high, one-time, all-front payment for an instance, reserve it for a one- or three-year term, and pay a significantly higher hourly rate for these instances.
<details>
	<summary>Answer</summary>

	1. Pay for the instances that you use by the hour, with no long-term commitments or up-front payments.

</details>

### Question 531: When will you incur costs with an Elastic IP address (EIP)?
1. When an EIP is allocated.
2. When it is allocated and associated with a running instance.
3. When it is allocated and associated with a stopped instance.
4. Costs are incurred regardless of whether the ElP is associated with a running instance.
<details>
	<summary>Answer</summary>

	4. Costs are incurred regardless of whether the ElP is associated with a running instance.

</details>

### Question 532: IAM provides several policy templates you can use to automatically assign permissions to the groups you create. The [...] policy template gives the Admins group permission to access all account resources, except your AWS account information.
1. Read Only Access.
2. Power User Access.
3. AWS Cloud Formation Read Only Access.
4. Administrator Access.
<details>
	<summary>Answer</summary>

	4. Administrator Access.

</details>

### Question 533: What does RRS stand for when talking about S3?
1. Redundancy Removal System.
2. Relational Rights Storage.
3. Regional Rights Standard.
4. Reduced Redundancy Storage.
<details>
	<summary>Answer</summary>

	4. Reduced Redundancy Storage.

</details>

### Question 534: Can I change the EC2 security groups after an instance is launched in EC2-Classic?
1. Yes, you can change security groups after you launch an instance in EC2-Classic.
2. No, you cannot change security groups after you launch an instance in EC2-Classic.
3. Yes, you can only when you remove rules from a security group.
4. Yes, you can only when you add rules to a security group.
<details>
	<summary>Answer</summary>

	2. No, you cannot change security groups after you launch an instance in EC2-Classic.

</details>

### Question 535: Please select the Amazon EC2 resource which cannot be tagged.
1. Images (AMIs, kernels, RAM disks).
2. Amazon EBS volumes.
3. Elastic IP addresses.
4. VPCs.
<details>
	<summary>Answer</summary>

	3. Elastic IP addresses.

</details>

### Question 536: Does Route 53 support MX Records?
1. Yes.
2. It supports CNAME records, but not MX records.
3. No.
4. Only Primary MX records. Secondary MX records are not supported.
<details>
	<summary>Answer</summary>

	1. Yes.

</details>

### Question 537: Which of the following notification endpoints or clients are supported by Amazon Simple Notification Service? (Choose 2 answers)
1. Email.
2. CloudFront distribution.
3. File Transfer Protocol.
4. Short Message Service.
5. Simple Network Management Protocol.
<details>
	<summary>Answer</summary>

	1. Email.
	4. Short Message Service.

</details>

### Question 538: AWS Identity and Access Management is a web service that enables Amazon Web Services (AWS) customers to manage users and user permissions in AWS. In addition to supporting IAM user policies, some services support resource-based permissions. Which of the following services are supported by resource-based permissions?
1. Amazon SNS, and Amazon SQS and AWS Direct Connect.
2. Amazon S3 and Amazon SQS and Amazon ElastiCache.
3. Amazon S3, Amazon SNS, Amazon SQS, Amazon Glacier and Amazon EB
4. Amazon Glacier, Amazon SNS, and Amazon CloudWatch.
<details>
	<summary>Answer</summary>

	3. Amazon S3, Amazon SNS, Amazon SQS, Amazon Glacier and Amazon EB

</details>

### Question 539: What does the following policy for Amazon EC2 do? `{ 'Statement':[{ 'Effect': 'Allow', 'Action':'ec2: Describe*', 'Resource':'*' }] }`
1. Allow users to use actions that start with 'Describe' over all the EC2 resources.
2. Share an AMI with a partner.
3. Share an AMI within the account.
4. Allow a group to only be able to describe, run, stop, start, and terminate instances.
<details>
	<summary>Answer</summary>

	1. Allow users to use actions that start with 'Describe' over all the EC2 resources.

</details>

### Question 540: Which IAM role do you use to grant AWS Lambda permission to access a DynamoDB Stream?
1. Dynamic role.
2. Invocation role.
3. Execution role.
4. Event Source role.
<details>
	<summary>Answer</summary>

	3. Execution role.

</details>

### Question 541: Can resource record sets in a hosted zone have a different domain suffix (for example, <www.blog>. acme.com and <www.acme.ca>)?
1. Yes, it can have for a maximum of three different TLDs.
2. Yes.
3. Yes, it can have depending on the TL.
4. No.
<details>
	<summary>Answer</summary>

	3. Yes, it can have depending on the TL.

</details>

### Question 542: In Amazon Elastic Compute Cloud, which of the following is used for communication between instances in the same network (EC2-Classic or a VPC)?
1. Private IP addresses.
2. Elastic IP addresses.
3. Static IP addresses.
4. Public IP addresses.
<details>
	<summary>Answer</summary>

	1. Private IP addresses.

</details>

### Question 543: A user is planning to host a mobile game on EC2 which sends notifications to active users on either high score or the addition of new features. The user should get this notification when he is online on his mobile device. Which of the below mentioned AWS services can help achieve this functionality?
1. AWS Simple Notification Service.
2. AWS Simple Email Service.
3. AWS Mobile Communication Service.
4. AWS Simple Queue Service.
<details>
	<summary>Answer</summary>

	1. AWS Simple Notification Service.

</details>

### Question 544: You need to create an Amazon Machine Image (AMI) for a customer for an application which does not appear to be part of the standard AWS AMI template that you can see in the AWS console. What are the alternative possibilities for creating an AMI on AWS?
1. You can purchase an AMIs from a third party but cannot create your own AMI.
2. You can purchase an AMIs from a third party or can create your own AMI.
3. Only AWS can create AMIs and you need to wait till it becomes available.
4. Only AWS can create AMIs and you need to request them to create one for you.
<details>
	<summary>Answer</summary>

	2. You can purchase an AMIs from a third party or can create your own AMI.

</details>

### Question 545: Will I be charged if the DB instance is idle?
1. Yes.
2. Only is running in GovCloud.
3. Only if running in VPC.
<details>
	<summary>Answer</summary>

	1. Yes.

</details>

### Question 546: Your company has been storing a lot of data in Amazon Glacier and has asked for an inventory of what is in there exactly. So you have decided that you need to download a vault inventory. Which of the following statements is incorrect in relation to Vault Operations in Amazon Glacier?
1. You can use Amazon Simple Notification Service (Amazon SNS) notifications to notify you when the job completes.
2. A vault inventory refers to the list of archives in a vault.
3. You can use Amazon Simple Queue Service (Amazon SQS) notifications to notify you when the job completes.
4. Downloading a vault inventory is an asynchronous operation.
<details>
	<summary>Answer</summary>

	3. You can use Amazon Simple Queue Service (Amazon SQS) notifications to notify you when the job completes.

</details>

### Question 547: Your fortune 500 company has under taken a TCO analysis evaluating the use of Amazon S3 versus acquiring more hardware The outcome was that ail employees would be granted access to use Amazon S3 for storage of their personal documents. Which of the following will you need to consider so you can set up a solution that incorporates single sign-on from your corporate AD or LDAP directory and restricts access for each user to a designated user folder in a bucket? (Choose 3 answers)
1. Setting up a federation proxy or identity provider.
2. Using AWS Security Token Service to generate temporary tokens.
3. Tagging each folder in the bucket.
4. Configuring IAM role.
5. Setting up a matching IAM user for every user in your corporate directory that needs access to a folder in the bucket.
<details>
	<summary>Answer</summary>

	1. Setting up a federation proxy or identity provider.
	2. Using AWS Security Token Service to generate temporary tokens.
	4. Configuring IAM role.

</details>

### Question 548: Your company policies require encryption of sensitive data at rest. You are considering the possible options for protecting data while storing it at rest on an EBS data volume, attached to an EC2 instance. Which of these options would allow you to encrypt your data at rest? (Choose 3 answers)
1. Implement third party volume encryption tools.
2. Do nothing as EBS volumes are encrypted by default.
3. Encrypt data inside your applications before storing it on EBS.
4. Encrypt data using native data encryption drivers at the file system level.
5. Implement SSL/TLS for all services running on the server.
<details>
	<summary>Answer</summary>

	1. Implement third party volume encryption tools.
	3. Encrypt data inside your applications before storing it on EBS.
	4. Encrypt data using native data encryption drivers at the file system level.

</details>

### Question 549: A scope has been handed to you to set up a super fast gaming server and you decide that you will use Amazon DynamoDB as your database. For efficient access to data in a table, Amazon DynamoDB creates and maintains indexes for the primary key attributes. A secondary index is a data structure that contains a subset of attributes from a table, along with an alternate key to support Query operations. How many types of secondary indexes does DynamoDB support?
1. 2.
2. 16.
3. 4.
4. As many as you need.
<details>
	<summary>Answer</summary>

	1. 2.

</details>

### Question 550: True or False: in Amazon Route 53, you can create a hosted zone for a top-level domain (TLD).
1. False.
2. False, Amazon Route 53 automatically creates it for you.
3. True, only if you send an XML document with a CreateHostedZoneRequest element for TLD.
4. True.
<details>
	<summary>Answer</summary>

	1. False.

</details>

### Question 551: You want to use AWS Import/Export to send data from your S3 bucket to several of your branch offices. What should you do if you want to send 10 storage units to AWS?
1. Make sure your disks are encrypted prior to shipping.
2. Make sure you format your disks prior to shipping.
3. Make sure your disks are 1TB or more.
4. Make sure you submit a separate job request for each device.
<details>
	<summary>Answer</summary>

	4. Make sure you submit a separate job request for each device.

</details>

### Question 552: You are deploying an application to track GPS coordinates of delivery trucks in the United States. Coordinates are transmitted from each delivery t ruck once every three seconds. You need to design an architecture that will enable real-time processing of these coordinates from multiple consumers. Which service should you use to implement data ingestion?
1. Amazon Kinesis.
2. AWS Data Pipeline.
3. Amazon AppStream.
4. Amazon Simple Queue Service.
<details>
	<summary>Answer</summary>

	1. Amazon Kinesis.

</details>

### Question 553: While performing the volume status checks, if the status is insufficient-data, what does it mean?
1. The checks may still be in progress on the volume.
2. The check has passed.
3. The check has failed.
<details>
	<summary>Answer</summary>

	1. The checks may still be in progress on the volume.

</details>

### Question 554: Can you create IAM security credentials for existing users?
1. Yes, existing users can have security credentials associated with their account.
2. No, IAM requires that all users who have credentials set up are not existing users.
3. No, security credentials are created within GROUPS, and then users are associated to GROUPS at a later time.
4. Yes, but only IAM credentials, not ordinary security credentials.
<details>
	<summary>Answer</summary>

	1. Yes, existing users can have security credentials associated with their account.

</details>

### Question 555: Can I move a Reserved Instance from one Region to another?
1. No.
2. Only if they are moving into GovCloud.
3. Yes.
4. Only if they are moving to US East from another region.
<details>
	<summary>Answer</summary>

	1. No.

</details>

### Question 556: A user has created an ELB with the Availability Zone US-East-1A. The user wants to add more zones to ELB to achieve High Availability. How can the user add more zones to the existing ELB?
1. The user should stop the ELB and add zones and instances as required.
2. The only option is to launch instances in different zones and add to ELB.
3. It is not possible to add more zones to the existing ELB.
4. The user can add zones on the fly from the AWS console.
<details>
	<summary>Answer</summary>

	4. The user can add zones on the fly from the AWS console.

</details>

### Question 557: Amazon SWF is designed to help users …
1. Design graphical user interface interactions.
2. Manage user identification and authorization.
3. Store Web content.
4. Coordinate synchronous and asynchronous tasks which are distributed and fault tolerant.
<details>
	<summary>Answer</summary>

	4. Coordinate synchronous and asynchronous tasks which are distributed and fault tolerant.

</details>

### Question 558: Which technique can be used to integrate AWS IAM (Identity and Access Management) with an on-premise LDAP (Lightweight Directory Access Protocol) directory service?
1. Use an IAM policy that references the LDAP account identifiers and the AWS credentials.
2. Use SAML (Security Assertion Markup Language) to enable single sign-on between AWS and LDAP.
3. Use AWS Security Token Service from an identity broker to issue short-lived AWS credentials.
4. Use IAM roles to automatically rotate the IAM credentials when LDAP credentials are updated.
5. Use the LDAP credentials to restrict a group of users from launching specific EC2 instance types.
<details>
	<summary>Answer</summary>

	2. Use SAML (Security Assertion Markup Language) to enable single sign-on between AWS and LDAP.

</details>

### Question 559: You are building a solution for a customer to extend their on-premises data center to AWS. The customer requires a 50-Mbps dedicated and private connection to their VPC. Which AWS product or feature satisfies this requirement?
1. Amazon VPC peering.
2. Elastic IP Addresses.
3. AWS Direct Connect.
4. Amazon VPC virtual private gateway.
<details>
	<summary>Answer</summary>

	3. AWS Direct Connect.

</details>

### Question 560: A customer wants to leverage Amazon Simple Storage Service (S3) and Amazon Glacier as part of their backup and archive infrastructure. The customer plans to use third-party software to support this integration. Which approach will limit the access of the third party software to only the Amazon S3 bucket named 'company-backup'?
1. A custom bucket policy limited to the Amazon S3 API in the Amazon Glacier archive 'company backup'.
2. A custom bucket policy limited to the Amazon S3 API in 'company-backup'.
3. A custom IAM user policy limited to the Amazon S3 API for the Amazon Glacier archive 'company backup'.
4. A custom IAM user policy limited to the Amazon S3 API in 'company-backup'.
<details>
	<summary>Answer</summary>

	4. A custom IAM user policy limited to the Amazon S3 API in 'company-backup'.

</details>

### Question 561: A user needs to run a batch process which runs for 10 minutes. This will only be run once, or at maximum twice, in the next month, so the processes will be temporary only. The process needs 15 X-Large instances. The process downloads the code from S3 on each instance when it is launched, and then generates a temporary log file. Once the instance is terminated, all the data will be lost. Which of the below mentioned pricing models should the user choose in this case?
1. Spot instance.
2. Reserved instance.
3. On-demand instance.
4. EBS optimized instance.
<details>
	<summary>Answer</summary>

	1. Spot instance.

</details>

### Question 562: You have been doing a lot of testing of your VPC Network by deliberately failing EC2 instances to test whether instances are failing over properly. Your customer who will be paying the AWS bill for all this asks you if he being charged for all these instances. You try to explain to him how the billing works on EC2 instances to the best of your knowledge. What would be an appropriate response to give to the customer in regards to this?
1. Billing commences when Amazon EC2 AMI instance is completely up and billing ends as soon as the instance starts to shutdown.
2. Billing only commences only after 1 hour of uptime and billing ends when the instance terminates.
3. Billing commences when Amazon EC2 initiates the boot sequence of an AMI instance and billing ends when the instance shuts down.
4. Billing commences when Amazon EC2 initiates the boot sequence of an AMI instance and billing ends as soon as the instance starts to shutdown.
<details>
	<summary>Answer</summary>

	3. Billing commences when Amazon EC2 initiates the boot sequence of an AMI instance and billing ends when the instance shuts down.

</details>

### Question 563: Refer to the architecture diagram above of a batch processing solution using Simple Queue Service (SQS) to set up a message queue between EC2 instances which are used as batch processors Cloud Watch monitors the number of Job requests (queued messages) and an Auto Scaling group adds or deletes batch servers automatically based on parameters set in Cloud Watch alarms. You can use this architecture to implement which of the following features in a cost effective and efficient manner? ![Question 563](images/question563.jpg)
1. Reduce the overall lime for executing jobs through parallel processing by allowing a busy EC2 instance that receives a message to pass it to the next instance in a daisy-chain setup.
2. Implement fault tolerance against EC2 instance failure since messages would remain in SQS and worn can continue with recovery of EC2 instances implement fault tolerance against SQS failure by backing up messages to S3.
3. Implement message passing between EC2 instances within a batch by exchanging messages through SQS.
4. Coordinate number of EC2 instances with number of job requests automatically thus Improving cost effectiveness.
5. Handle high priority jobs before lower priority jobs by assigning a priority metadata fie ld to SQS messages.
<details>
	<summary>Answer</summary>

	3. Implement message passing between EC2 instances within a batch by exchanging messages through SQS.

</details>

### Question 564: You are migrating an internal server on your DC to an EC2 instance with EBS volume. Your server disk usage is around 500GB so you just copied all your data to a 2TB disk to be used with AWS Import/Export. Where will the data be imported once it arrives at Amazon?
1. To a 2TB EBS volume.
2. To an S3 bucket with 2 objects of 1TB.
3. To an 500GB EBS volume.
4. To an S3 bucket as a 2TB snapshot.
<details>
	<summary>Answer</summary>

	2. To an S3 bucket with 2 objects of 1TB.

</details>

### Question 565: Is there any way to own a direct connection to Amazon Web Services?
1. You can create an encrypted tunnel to VPC, but you don't own the connection.
2. Yes, it's called Amazon Dedicated Connection.
3. No, AWS only allows access from the public Internet.
4. Yes, it's called Direct Connect.
<details>
	<summary>Answer</summary>

	4. Yes, it's called Direct Connect.

</details>

### Question 566: Which of the following strategies can be used to control access to your Amazon EC2 instances?
1. DB security groups.
2. IAM policies.
3. None of these.
4. EC2 security groups.
<details>
	<summary>Answer</summary>

	4. EC2 security groups.

</details>

### Question 567: A client of yours has a huge amount of data stored on Amazon S3, but is concerned about someone stealing it while it is in transit. You know that all data is encrypted in transit on AWS, but which of the following is wrong when describing server-side encryption on AWS?
1. Amazon S3 server-side encryption employs strong multi-factor encryption.
2. Amazon S3 server-side encryption uses one of the strongest block ciphers available, 256-bit Advanced Encryption Standard (AES-256), to encrypt your data.
3. In server-side encryption, you manage encryption/decryption of your data, the encryption keys, and related tools.
4. Server-side encryption is about data encryption at rest―that is, Amazon S3 encrypts your data as it writes it to disks.
<details>
	<summary>Answer</summary>

	3. In server-side encryption, you manage encryption/decryption of your data, the encryption keys, and related tools.

</details>

### Question 568: When you run a DB Instance as a Multi-AZ deployment, the [...] serves database writes and reads
1. secondary.
2. backup.
3. stand by.
4. primary.
<details>
	<summary>Answer</summary>

	4. primary.

</details>

### Question 569: In Amazon EC2, how many Elastic IP addresses can you have by default?
1. 10.
2. 2.
3. 5.
4. 20.
<details>
	<summary>Answer</summary>

	3. 5.

</details>

### Question 570: A user has created photo editing software and hosted it on EC2. The software accepts requests from the user about the photo format and resolution and sends a message to S3 to enhance the picture accordingly. Which of the below mentioned AWS services will help make a scalable software with the AWS infrastructure in this scenario?
1. AWS Simple Notification Service.
2. AWS Simple Queue Service.
3. AWS Elastic Transcoder.
4. AWS Glacier.
<details>
	<summary>Answer</summary>

	2. AWS Simple Queue Service.

</details>

### Question 571: Using Amazon CloudWatch's Free Tier, what is the frequency of metric updates which you receive?
1. 5 minutes.
2. 500 milliseconds.
3. 30 seconds
4. 1 minute.
<details>
	<summary>Answer</summary>

	1. 5 minutes.

</details>

### Question 572: When you resize the Amazon RDS DB instance, Amazon RDS will perform the upgrade during the next maintenance window. If you want the upgrade to be performed now, rather than waiting for the maintenance window, specify the [...] option.
1. Apply Now.
2. Apply Soon.
3. Apply This.
4. Apply Immediately.
<details>
	<summary>Answer</summary>

	4. Apply Immediately.

</details>

### Question 573: A user is running a webserver on EC2. The user wants to receive the SMS when the EC2 instance utilization is above the threshold limit. Which AWS services should the user configure in this case?
1. AWS CloudWatch + AWS SQS.
2. AWS CloudWatch + AWS SNS.
3. AWS CloudWatch + AWS SES.
4. AWS EC2 + AWS Cloudwatch.
<details>
	<summary>Answer</summary>

	2. AWS CloudWatch + AWS SNS.

</details>

### Question 574: You're running an application on-premises due to its dependency on non-x86 hardware and want to use AWS for data backup. Your backup application is only able to write to POSIX-compatible block based storage. You have 140TB of data and would like to mount it as a single folder on your file server Users must be able to access portions of this data while the backups are taking place. What backup solution would be most appropriate for this use case?
1. Use Storage Gateway and configure it to use Gateway Cached volumes.
2. Configure your backup software to use S3 as the target for your data backups.
3. Configure your backup software to use Glacier as the target for your data backups.
4. Use Storage Gateway and configure it to use Gateway Stored volumes.
<details>
	<summary>Answer</summary>

	1. Use Storage Gateway and configure it to use Gateway Cached volumes.

</details>

### Question 575: What happens to Amazon EBS root device volumes, by default, when an instance terminates?
1. Amazon EBS root device volumes are moved to IA
2. Amazon EBS root device volumes are copied into Amazon RD
3. Amazon EBS root device volumes are automatically deleted.
4. Amazon EBS root device volumes remain in the database until you delete them.
<details>
	<summary>Answer</summary>

	2. Amazon EBS root device volumes are copied into Amazon RD

</details>

### Question 576: You require the ability to analyze a customer's clickstream data on a website so they can do behavioral analysis. Your customer needs to know what sequence of pages and ads their customer clicked on. This data will be used in real time to modify the page layouts as customers click through the site to increase stickiness and advertising click-through. Which option meets the requirements for captioning and analyzing this data?
1. Log clicks in weblogs by URL store to Amazon S3, and then analyze with Elastic MapReduce.
2. Push web clicks by session to Amazon Kinesis and analyze behavior using Kinesis workers.
3. Write click events directly to Amazon Redshift and then analyze with SQL.
4. Publish web clicks by session to an Amazon SQS queue men periodically drain these events to Amazon RDS and analyze with SQL.
<details>
	<summary>Answer</summary>

	2. Push web clicks by session to Amazon Kinesis and analyze behavior using Kinesis workers.

</details>

### Question 577: What happens when you create a topic on Amazon SNS?
1. The topic is created, and it has the name you specified for it.
2. An ARN (Amazon Resource Name) is created.
3. You can create a topic on Amazon SQS, not on Amazon SNS.
4. This question doesn't make sense.
<details>
	<summary>Answer</summary>

	2. An ARN (Amazon Resource Name) is created.

</details>

### Question 578: A company needs to deploy virtual desktops to its customers in a virtual private cloud, leveraging existing security controls. Which set of AWS services and features will meet the company's requirements?
1. Virtual Private Network connection. AWS Directory Services, and Classic link.
2. Virtual Private Network connection. AWS Di rectory Services, and Amazon Workspaces.
3. AWS Directory Service, Amazon Workspaces, and AWS Identity and Access Management.
4. Amazon Elastic Compute Cloud, and AWS Identity and Access Management.
<details>
	<summary>Answer</summary>

	3. AWS Directory Service, Amazon Workspaces, and AWS Identity and Access Management.

</details>

### Question 579: You are designing a multi-platform web application for AWS The application will run on EC2 instances and will be accessed from PCs. tablets and smart phones Supported accessing platforms are Windows, macOS, iOS and Android Separate sticky session and SSL certificate setups are required for different platform types which of the following describes the most cost effective and performance efficient architecture setup?
1. Setup a hybrid architecture to handle session state and SSL certificates on-prem and separate EC2 Instance groups running web applications for different platform types running in a VPC.
2. Set up one ELB for all platforms to distribute load among multiple instance under it Each EC2 instance implements ail functionality for a particular platform.
3. Set up two ELBs The first ELB handles SSL certificates for all platforms and the second ELB handles session stickiness for all platforms for each ELB run separate EC2 instance groups to handle the web application for each platform.
4. Assign multiple ELBS to an EC2 instance or group of EC2 instances running the common components of the web application, one ELB for each platform type Session stickiness and SSLtermination are done at the ELBs.
<details>
	<summary>Answer</summary>

	4. Assign multiple ELBS to an EC2 instance or group of EC2 instances running the common components of the web application, one ELB for each platform type Session stickiness and SSLtermination are done at the ELBs.

</details>

### Question 580: A company is deploying a two-tier, highly available web application to AWS. Which service provides durable storage for static content while utilizing lower Overall CPU resources for the web tier?
1. Amazon EBS volume.
2. Amazon S3.
3. Amazon EC2 instance store.
4. Amazon RD5 instance.
<details>
	<summary>Answer</summary>

	2. Amazon S3.

</details>

### Question 581: Select the incorrect statement.
1. In Amazon EC2, the private IP addresses only returned to Amazon EC2 when the instance is stopped or terminated.
2. In Amazon VPC, an instance retains its private IP addresses when the instance is stopped.
3. In Amazon VPC, an instance does NOT retain its private IP addresses when the instance is stopped.
4. In Amazon EC2, the private IP address is associated exclusive ly with the instance for its lifetime.
<details>
	<summary>Answer</summary>

	3. In Amazon VPC, an instance does NOT retain its private IP addresses when the instance is stopped.

</details>

### Question 582: An organization has a statutory requirement to protect the data at rest for data stored in EBS volumes. Which of the below mentioned options can the organization use to achieve data protection?
1. Data replication.
2. Data encryption.
3. Data snapshot.
4. All the options listed here.
<details>
	<summary>Answer</summary>

	4. All the options listed here.

</details>

### Question 583: A web design company currently runs several FTP servers that their 250 customers use to upload and download large graphic files They wish to move this system to AWS to make it more scalable, butthey wish to maintain customer privacy and Keep costs to a minimum. What AWS architecture would you recommend?
1. Ask their customers to use an S3 client instead of an FTP client. Create a single S3 bucket Create an IAM user for each customer Put the IAM Users in a Group that has an IAM policy that permits access to sub-directories within the bucket via use of the 'username' Policy variable.
2. Create a single S3 bucket with Reduced Redundancy Storage turned on and ask their customers to use an S3 client instead of an FTP client Create a bucket for each customer with a Bucket Policy that permits access only to that one customer.
3. Create an auto-scaling group of FTP servers with a scaling policy to automatically scale-in when minimum network traffic on the auto-scaling group is below a given threshold. Load a central list of ftp users from S3 as part of the user Data startup script on each Instance.
4. Create a single S3 bucket with Requester Pays turned on and ask their customers to use an S3 client instead of an FTP client Create a bucket tor each customer with a Bucket Policy that permits access only to that one customer.
<details>
	<summary>Answer</summary>

	1. Ask their customers to use an S3 client instead of an FTP client. Create a single S3 bucket Create an IAM user for each customer Put the IAM Users in a Group that has an IAM policy that permits access to sub-directories within the bucket via use of the 'username' Policy variable.

</details>

### Question 584: Amazon RDS DB snapshots and automated backups are stored in:
1. Amazon S3.
2. Amazon ECS Volume.
3. Amazon RDS.
4. Amazon EMR.
<details>
	<summary>Answer</summary>

	1. Amazon S3.

</details>

### Question 585: Can Amazon S3 uploads resume on failure or do they need to restart?
1. Restart from beginning.
2. You can resume them, if you flag the 'resume on fai lure' option before uploading.
3. Resume on failure.
4. Depends on the file size.
<details>
	<summary>Answer</summary>

	3. Resume on failure.

</details>

### Question 586: Prior to the introduction of this function, the HA feature provided redundancy and performance, but required that a failed/lost group member be [...] reinstated.
1. automatically.
2. periodically.
3. manually.
4. continuously.
<details>
	<summary>Answer</summary>

	3. manually.

</details>

### Question 587: A company has a workflow that sends video files from their on-premise system to AWS for transcoding. They use EC2 worker instances that pull transcoding jobs from SQS. Why is SQS an appropriate service for this scenario?
1. SQS guarantees the order of the messages.
2. SQS synchronously provides transcoding output.
3. SQS checks the health of the worker instances.
4. SQS helps to facilitate horizontal scaling of encoding tasks.
<details>
	<summary>Answer</summary>

	4. SQS helps to facilitate horizontal scaling of encoding tasks.

</details>

### Question 588: Which statement below best describes what thresholds you can set to trigger a CloudWatch Alarm?
1. Set a target value and choose whether the alarm will trigger when the value is greater than (>), greater than or equal to (>=), less than (<), or less than or equal to (<=) that value.
2. Thresholds need to be set in IAM not CloudWatch.
3. Only default thresholds can be set you can't choose your own thresholds.
4. Set a target value and choose whether the alarm will trigger when the value hits this threshold.
<details>
	<summary>Answer</summary>

	1. Set a target value and choose whether the alarm will trigger when the value is greater than (>), greater than or equal to (>=), less than (<), or less than or equal to (<=) that value.

</details>

### Question 589: You are designing a web application that stores static assets in an Amazon Simple Storage Service (S3) bucket. You expect this bucket to immediately receive over 150 PUT requests per second. What should you do to ensure optimal performance?
1. Use multi-part upload.
2. Add a random prefix to the key names.
3. Amazon S3 will automatically manage performance at this scale.
4. Use a predictable naming scheme, such as sequential numbers or date time sequences, in the key names.
<details>
	<summary>Answer</summary>

	1. Use multi-part upload.

</details>

### Question 590: What does Amazon EC2 provide?
1. Virtual servers in the Cloud.
2. A platform to run code (Java, PHP, Python), paying on an hourly basis.
3. Computer Clusters in the Cloud.
4. Physical servers, remotely managed by the customer.
<details>
	<summary>Answer</summary>

	1. Virtual servers in the Cloud.

</details>

### Question 591: A customer has a single 3-TB volume on-premises that is used to hold a large repository of images and print layout files. This repository is growing at 500 GB a year and must be presented as a single logical volume. The customer is becoming increasingly constrained with their local storage capacity and wants an off-site backup of this data, while maintaining low-latency access to their frequently accessed data. Which AWS Storage Gateway configuration meets the customer requirements?
1. Gateway-Cached volumes with snapshots scheduled to Amazon S3.
2. Gateway-Stored volumes with snapshots scheduled to Amazon S3.
3. Gateway-Virtual Tape Library with snapshots to Amazon S3.
4. Gateway-Virtual Tape Library with snapshots to Amazon Glacier.
<details>
	<summary>Answer</summary>

	4. Gateway-Virtual Tape Library with snapshots to Amazon Glacier.

</details>

### Question 592: You are architecting an auto-scalable batch processing system using video processing pipelines and Amazon Simple Queue Service (Amazon SQS) for a customer. You are unsure of the limitations of SQS and need to find out. What do you think is a correct statement about the limitations of Amazon SQS?
1. It supports an unlimited number of queues but a limited number of messages per queue for each user but automatically deletes messages that have been in the queue for more than 4 weeks.
2. It supports an unlimited number of queues and unlimited number of messages per queue for each user but automatically deletes messages that have been in the queue for more than 4 days.
3. It supports an unlimited number of queues but a limited number of messages per queue for each user but automatically deletes messages that have been in the queue for more than 4 days.
4. It supports an unlimited number of queues and unlimited number of messages per queue for each user but automatically deletes messages that have been in the queue for more than 4 weeks.
<details>
	<summary>Answer</summary>

	2. It supports an unlimited number of queues and unlimited number of messages per queue for each user but automatically deletes messages that have been in the queue for more than 4 days.

</details>

### Question 593: Which Amazon service can I use to define a virtual network that closely resembles a traditional data center?
1. Amazon VPC.
2. Amazon Service Bus.
3. Amazon EMR.
4. Amazon RDS.
<details>
	<summary>Answer</summary>

	1. Amazon VPC.

</details>

### Question 594: Select the correct set of options. These are the initial settings for the default security group:
1. Allow no inbound traffic, Allow all outbound traffic and Allow instances associated with this security group to talk to each other.
2. Allow all inbound traffic, Allow no outbound traffic and Allow instances associated with this security group to talk to each other.
3. Allow no inbound traffic, Allow all outbound traffic and Does NOT allow instances associated with this security group to talk to each other.
4. Al low all inbound traffic, Allow all outbound traffic and Does NOT allow instances associated with this security group to talk to each other.
<details>
	<summary>Answer</summary>

	1. Allow no inbound traffic, Allow all outbound traffic and Allow instances associated with this security group to talk to each other.

</details>

### Question 595: You need to migrate a large amount of data into the cloud that you have stored on a hard disk and you decide that the best way to accomplish this is with AWS Import/Export and you mail the hard disk to AWS. Which of the following statements is incorrect in regards to AWS Import/Export?
1. It can export from Amazon S3.
2. It can Import to Amazon Glacier.
3. It can export from Amazon Glacier.
4. It can Import to Amazon EBS.
<details>
	<summary>Answer</summary>

	3. It can export from Amazon Glacier.

</details>

### Question 596: Can I control if and when MySQL based RDS Instance is upgraded to new supported versions?
1. No.
2. Only in VPC.
3. Yes.
<details>
	<summary>Answer</summary>

	3. Yes.

</details>

### Question 597: If I have multiple Read Replicas for my master DB Instance and I promote one of them, what happens to the rest of the Read Replicas?
1. The remaining Read Replicas will still replicate from the older master DB Instance.
2. The remaining Read Replicas will be deleted.
3. The remaining Read Replicas will be combined to one read replica.
<details>
	<summary>Answer</summary>

	1. The remaining Read Replicas will still replicate from the older master DB Instance.

</details>

### Question 598: A user is running a batch process which runs for 1 hour every day. Which of the below mentioned options is the right instance type and costing model in this case if the user performs the same task for the whole year?
1. EBS backed instance with on-demand instance pricing.
2. EBS backed instance with heavy utilized reserved instance pricing.
3. EBS backed instance with low utilized reserved instance pricing.
4. Instance store backed instance with spot instance pricing.
<details>
	<summary>Answer</summary>

	1. EBS backed instance with on-demand instance pricing.

</details>

### Question 599: You are in the process of building an online gaming site for a client and one of the requirements is that it must be able to process vast amounts of data easily. Which AWS Service would be very helpful in processing all this data?
1. Amazon S3.
2. AWS Data Pipeline.
3. AWS Direct Connect.
4. Amazon EMR.
<details>
	<summary>Answer</summary>

	4. Amazon EMR.

</details>

### Question 600: Your team has a tomcat-based Java application you need to deploy into development, test and production environments. After some research, you opt to use Elastic Beanstalk due to its tight integration with your developer tools and RDS due to its ease of management. Your QA team lead points out that you need to roll a sanitized set of production data into your environment on a nightly basis. Similarly, other software teams in your org want access to that same restored data via their EC2 instances in your VPC. The optimal setup for persistence and security that meets the above requirements would be the following:
1. Create your RDS instance as part of your Elastic Beanstalk definition and alter its security group to allow access to it from hosts in your application subnets.
2. Create your RDS instance separately and add its IP address to your application's DB connection strings in your code Alter its security group to allow access to it from hosts within your VPC's IPaddress block.
3. Create your RDS instance separately and pass its DNS name to your app's DB connection string as an environment variable. Create a security group for client machines and add it as a valid source for DB traffic to the security group of the RDS instance itself.
4. Create your RDS instance separately and pass its DNS name to your's DB connection string as an environment variable Alter its security group to allow access to It from hosts in your application subnets.
<details>
	<summary>Answer</summary>

	1. Create your RDS instance as part of your Elastic Beanstalk definition and alter its security group to allow access to it from hosts in your application subnets.

</details>

### Question 601: What are characteristics of Amazon S3? (Choose 2 answers)
1. Amazon S3 allows you to store objects of virtually unlimited size.
2. Amazon S3 offers Provisioned IOP.
3. Amazon S3 allows you to store unlimited amounts of data.
4. Amazon S3 should be used to host a relational database.
5. Objects are directly accessible via a URL.
<details>
	<summary>Answer</summary>

	3. Amazon S3 allows you to store unlimited amounts of data.
	5. Objects are directly accessible via a URL.

</details>

### Question 602: You need to set up a complex network infrastructure for your organization that will be reasonably easy to deploy, replicate, control, and track changes on. Which AWS service would be best to use to help you accomplish this?
1. AWS Import/Export.
2. AWS CloudFormation.
3. Amazon Route 53.
4. Amazon CloudWatch.
<details>
	<summary>Answer</summary>

	2. AWS CloudFormation.

</details>

### Question 603: How should the application use AWS credentials to access the S3 bucket securely?
1. Use the AWS account access Keys the application retrieves the credentials from the source code of the application.
2. Create an IAM user for the application with permissions that allow list access to the S3 bucket launch the instance as the IAM user and retrieve the IAM user's credentials from the EC2 instance user data.
3. Create an IAM role for EC2 that allows list access to objects in the S3 bucket. Launch the instance with the role, and retrieve the role's credentials from the EC2 Instance metadata.
4. Create an IAM user for the application with permissions that allow list access to the S3 bucket. The application retrieves the IAM user credentials from a temporary directory with permissions that allow read access only to the application user.
<details>
	<summary>Answer</summary>

	3. Create an IAM role for EC2 that allows list access to objects in the S3 bucket. Launch the instance with the role, and retrieve the role's credentials from the EC2 Instance metadata.

</details>

### Question 604: You are setting up a VPC and you need to set up a public subnet within that VPC. Which following requirement must be met for this subnet to be considered a public subnet?
1. Subnet's traffic is not routed to an internet gateway but has its traffic routed to a virtual private gateway.
2. Subnet's traffic is routed to an internet gateway.
3. Subnet's traffic is not routed to an internet gateway.
4. None of these answers can be considered a public subnet.
<details>
	<summary>Answer</summary>

	2. Subnet's traffic is routed to an internet gateway.

</details>

### Question 605: Is it possible to access your EBS snapshots?
1. Yes, through the Amazon S3 APIs.
2. Yes, through the Amazon EC2 APIs.
3. No, EBS snapshots cannot be accessed; they can only be used to create a new EBS volume.
4. EBS doesn't provide snapshots.
<details>
	<summary>Answer</summary>

	2. Yes, through the Amazon EC2 APIs.

</details>

### Question 606: How many types of block devices does Amazon EC2 support?
1. 4.
2. 5.
3. 2.
4. 1.
<details>
	<summary>Answer</summary>

	3. 2.

</details>

### Question 607: SQL Server [...] store log ins and passwords in the master database.
1. can be configured to but by default does not.
2. doesn't.
3. does.
<details>
	<summary>Answer</summary>

	3. does.

</details>

### Question 608: You are using an m1.small EC2 Instance with one 300GB EBS volume to host a relational database. You determined that write throughput to the database needs to be increased. Which of the following approaches can help achieve this? (Choose 2 answers)
1. Use an array of EBS volumes.
2. Enable Multi-AZ mode.
3. Place the instance in an Auto Scaling Groups.
4. Add an EBS volume and place into RAID 5.
5. Increase the size of the EC2 Instance.
6. Put the database behind an Elastic Load Balancer.
<details>
	<summary>Answer</summary>

	1. Use an array of EBS volumes.
	5. Increase the size of the EC2 Instance.

</details>

### Question 609: A user is hosting a website in the US West-1 region. The website has the highest client base from the Asia-Pacific (Singapore / Japan) region. The application is accessing data from S3 before serving it to client. Which of the below mentioned regions gives a better performance for S3 objects?
1. Japan.
2. Singapore.
3. US East.
4. US West-1.
<details>
	<summary>Answer</summary>

	4. US West-1.

</details>

### Question 610: You need to set up security for your VPC and you know that Amazon VPC provides two features that you can use to increase security for your VPC: Security groups and network access control lists (ACLs). You start to look into security groups first. Which statement below is incorrect in relation to security groups?
1. Are stateful: Return traffic is automatically allowed, regardless of any rules.
2. Evaluate all rules before deciding whether to allow traffic.
3. Support allow rules and deny rules.
4. Operate at the instance level (first layer of defense).
<details>
	<summary>Answer</summary>

	3. Support allow rules and deny rules.

</details>

### Question 611: Can a single EBS volume be attached to multiple EC2 instances at the same time?
1. Yes.
2. No.
3. Only for high-performance EBS volumes.
4. Only when the instances are located in the US regions.
<details>
	<summary>Answer</summary>

	2. No.

</details>

### Question 612: You are planning and configuring some EBS volumes for an application. in order to get the most performance out of your EBS volumes, you should attach them to an instance with enough [...] to support your volumes.
1. redundancy.
2. storage.
3. bandwidth.
4. memory.
<details>
	<summary>Answer</summary>

	3. bandwidth.

</details>

### Question 613: An organization has three separate AWS accounts, one each for development, testing, and production. The organization wants the testing team to have access to certain AWS resources in the production account. How can the organization achieve this?
1. It is not possible to access resources of one account with another account.
2. Create the IAM roles with cross account access.
3. Create the IAM user in a test account, and allow it access to the production environment with the IAM policy.
4. Create the IAM users with cross account access.
<details>
	<summary>Answer</summary>

	2. Create the IAM roles with cross account access.

</details>

### Question 614: A benefits enrollment company is hosting a 3-tier web application running in a VPC on AWS which includes a NAT (Network Address Translation) instance in the public Web tier. There is enough provisioned capacity for the expected workload tor the new fiscal year benefit enrollment period plus some extra overhead Enrollment proceeds nicely for two days and then the web tier becomes unresponsive, upon investigation using CloudWatch and other monitoring tools it is discovered that there is an extremely large and unanticipated amount of inbound traffic coming from a set of 15specific IP addresses over port 80 from a country where the benefits company has no customers. The web tier instances are so overloaded that benefit enrollment administrators cannot even SSH into them. Which activity would be useful in defending against this attack?
1. Create a custom route table associated with the web tier and block the attacking IP addresses from the IGW (Internet Gateway).
2. Change the EIP (Elastic IP Address) of the NAT instance in the web tier subnet and update the Main Route Table with the new EIP.
3. Create 15 Security Group rules to block the attacking IP addresses over port 80.
4. Create an inbound NACL (Network Access control list) associated with the web tier subnet with deny rules to block the attacking IP addresses.
<details>
	<summary>Answer</summary>

	4. Create an inbound NACL (Network Access control list) associated with the web tier subnet with deny rules to block the attacking IP addresses.

</details>

### Question 615: You launch an Amazon EC2 instance without an assigned AVVS identity and Access Management (IAM) role. Later, you decide that the instance should be running with an IAM role. Which action must you take in order to have a running Amazon EC2 instance with an IAM role assigned to it?
1. Create an image of the instance, and register the image with an IAM role assigned and an Amazon EBS volume mapping.
2. Create a new IAM role with the same permissions as an existing IAM role, and assign it to the running instance.
3. Create an image of the instance, add a new IAM role with the same permissions as the desired IAM role, and deregister the image with the new role assigned.
4. Create an image of the instance, and use this image to launch a new instance with the desired Lam role assigned.
<details>
	<summary>Answer</summary>

	4. Create an image of the instance, and use this image to launch a new instance with the desired Lam role assigned.

</details>

### Question 616: Does AWS Direct Connect allow you access to all Availabilities Zones within a Region?
1. Depends on the type of connection.
2. Yes.
3. No.
4. Only when there's just one Availability Zone in a region. If there are more than one, only one availability zone can be accessed directly.
<details>
	<summary>Answer</summary>

	1. Depends on the type of connection.

</details>

### Question 617: What is the durability of S3 RRS?
1. 99.99%.
2. 99.95%.
3. 99.995%.
4. 99.999999999%.
<details>
	<summary>Answer</summary>

	1. 99.99%.

</details>

### Question 618: Your organization is in the business of architecting complex transactional databases. For a variety of reasons, this has been done on EBS. What is AWS's recommendation for customers who have architected databases using EBS for backups?
1. Backups to Amazon S3 be performed through the database management system.
2. Backups to AWS Storage Gateway be performed through the database management system.
3. If you take regular snapshots no further backups are required.
4. Backups to Amazon Glacier be performed through the database management system.
<details>
	<summary>Answer</summary>

	1. Backups to Amazon S3 be performed through the database management system.

</details>

### Question 619: You need to create a load balancer in a VPC network that you are building. You can make your load balancer internal (private) or internet-facing (public). When you make your load balancer internal, a DNS name will be created, and it will contain the private IP address of the load balancer. An internal load balancer is not exposed to the internet. When you make your load balancer internet-facing, a DNS name will be created with the public IP address. If you want the Internet-facing load balancer to be connected to the Internet, where must this load balancer reside?
1. The load balancer must reside in a subnet that is connected to the internet using the internet gateway.
2. The load balancer must reside in a subnet that is not connected to the internet.
3. The load balancer must not reside in a subnet that is connected to the internet.
4. The load balancer must be completely outside of your IP.
<details>
	<summary>Answer</summary>

	1. The load balancer must reside in a subnet that is connected to the internet using the internet gateway.

</details>

### Question 620: In the Amazon CloudWatch, which metric should I be checking to ensure that your DB Instance has enough free storage space?
1. Free Storage.
2. Free Storage Space.
3. Free Storage Volume.
4. Free DB Storage Space.
<details>
	<summary>Answer</summary>

	2. Free Storage Space.

</details>

### Question 621: A web-startup runs its very successful social news application on Amazon EC2 with an Elastic Load Balancer, an Auto-Scaling group of Java/Tomcat application-servers, and DynamoDB as data store. The main web-application best runs on m2 x large instances since it is highly memory- bound Each new deployment requires semi-automated creation and testing of a new AMI for the application servers which takes quite a while ana is therefore only done once per week. Recently, a new chat feature has been implemented in nodejs and wails to be integrated in the architecture. First tests show that the new component is CPU bound Because the company has some experience with using Chef, they decided to streamline the deployment process and use AWS OpsWorks as an application life cycle tool to simplify management of the application and reduce the deployment cycles. What configuration in AWS OpsWorks is necessary to integrate the new chat module in the most cost-efficient and flexible way?
1. Create one AWS OpsWorks stack, create one AWS OpsWorks layer, create one custom recipe.
2. Create one AWS OpsWorks stack create two AWS OpsWorks layers create one custom recipe.
3. Create two AWS OpsWorks stacks create two AWS OpsWorks layers create one custom recipe.
4. Create two AWS OpsWorks stacks create two AWS OpsWorks layers create two custom recipe.
<details>
	<summary>Answer</summary>

	3. Create two AWS OpsWorks stacks create two AWS OpsWorks layers create one custom recipe.

</details>

### Question 622: A client needs you to import some existing infrastructure from a dedicated hosting provider to AWS to try and save on the cost of running his current website. He also needs an automated process that manages backups, software patching, automatic failure detection, and recovery. You are aware that his existing set up currently uses an Oracle database. Which of the following AWS databases would be best for accomplishing this task?
1. Amazon RDS.
2. Amazon Redshift.
3. Amazon SimpleDB.
4. Amazon ElastiCache.
<details>
	<summary>Answer</summary>

	1. Amazon RDS.

</details>

### Question 623: A user is currently building a website which will require a large number of instances in six months, when a demonstration of the new site will be given upon launch. Which of the below mentioned options allows the user to procure the resources beforehand so that they need not worry about infrastructure availability during the demonstration?
1. Procure all the instances as reserved instances beforehand.
2. Launch all the instances as part of the cluster group to ensure resource availability.
3. Pre-warm all the instances one month prior to ensure resource availability.
4. Ask AWS now to procure the dedicated instances in 6 months.
### Question 624: Amazon RDS creates an SSL certificate and installs the certificate on the DB Instance when Amazon RDS provisions the instance. These certificates are signed by a certificate authority. The [...] is stored at <https://rds.amazonaws.com/doc/rds-ssl-ca-cert.pem>.
5. private key.
6. foreign key.
7. public key.
8. protected key.
<details>
	<summary>Answer</summary>

	1. Procure all the instances as reserved instances beforehand.
	5. private key.

</details>

### Question 625: What happens to data on an ephemeral volume of an EBS-backed EC2 instance if it is terminated or if it fails?
1. Data is automatically copied to another volume.
2. The volume snapshot is saved in S3.
3. Data persists.
4. Data is deleted.
<details>
	<summary>Answer</summary>

	4. Data is deleted.

</details>

### Question 626: You manually launch a NAT AMI in a public subnet. The network is properly configured. Security groups and network access control lists are property configured. Instances in a private subnet can access the NAT. The NAT can access the Internet. However, private instances cannot access the Internet. What additional step is required to allow access from the private instances?
1. Enable Source/Destination Check on the private Instances.
2. Enable Source/Destination Check on the NAT instance.
3. Disable Source/Destination Check on the private instances.
4. Disable Source/Destination Check on the NAT instance.
<details>
	<summary>Answer</summary>

	2. Enable Source/Destination Check on the NAT instance.

</details>

### Question 627: You have just discovered that you can upload your objects to Amazon S3 using Multipart Upload API. You start to test it out but are unsure of the benefits that it would provide. Which of the following is not a benefit of using multipart uploads?
1. You can begin an upload before you know the final object size.
2. Quick recovery from any network issues.
3. Pause and resume object uploads.
4. It's more secure than normal upload.
<details>
	<summary>Answer</summary>

	4. It's more secure than normal upload.

</details>

### Question 628: To help you manage your Amazon EC2 instances, images, and other Amazon EC2 resources, you can assign your own metadata to each resource in the form of [...].
1. special filters.
2. functions.
3. tags.
4. wildcards.
<details>
	<summary>Answer</summary>

	3. tags.

</details>

### Question 629: Are you able to integrate a multi-factor token service with the AWS Platform?
1. Yes, using the AWS multi-factor token devices to authenticate users on the AWS platform.
2. No, you cannot integrate multi-factor token devices with the AWS platform.
3. Yes, you can integrate private multi-factor token devices to authenticate users to the AWS platform.
<details>
	<summary>Answer</summary>

	1. Yes, using the AWS multi-factor token devices to authenticate users on the AWS platform.

</details>

### Question 630: Do the Amazon EBS volumes persist independently from the running life of an Amazon EC2 instance?
1. No.
2. Only if instructed to when created.
3. Yes.
<details>
	<summary>Answer</summary>

	3. Yes.

</details>

### Question 631: If I write the below command, what does it do? ec2-run ami-e3a5408a -n 20 -g appserver
1. Start twenty instances as members of appserver group.
2. Creates 20 rules in the security group named appserver.
3. Terminate twenty instances as members of appserver group.
4. Start 20 security groups.
<details>
	<summary>Answer</summary>

	1. Start twenty instances as members of appserver group.

</details>

### Question 632: A company is deploying a new two-tier web application in AWS. The company has limited staff and requires high availability, and the application requires complex queries and table joins. Which configuration provides the solution for the company's requirements?
1. MySQL Installed on two Amazon EC2 Instances in a single Availability Zone.
2. Amazon RDS for MySQL with Multi-AZ.
3. Amazon ElastiCache
4. Amazon DynamoDB.
<details>
	<summary>Answer</summary>

	4. Amazon DynamoDB.

</details>

### Question 633: Is creating a Read Replica of another Read Replica supported?
1. Only in certain regions.
2. Only with MSSQL based RDS.
3. Only for Oracle RDS types.
4. No.
<details>
	<summary>Answer</summary>

	4. No.

</details>

### Question 634: In order to optimize performance for a compute cluster that requires low inter-node latency, which of the following feature should you use?
1. Multiple Availability Zones.
2. AWS Direct Connect.
3. EC2 Dedicated Instances.
4. Placement Groups.
5. VPC private subnets.
<details>
	<summary>Answer</summary>

	4. Placement Groups.

</details>

### Question 635: Regarding the attaching of ENI to an instance, what does 'warm attach' refer to?
1. Attaching an ENI to an instance when it is stopped.
2. This question doesn't make sense.
3. Attaching an ENI to an instance when it is running.
4. Attaching an ENI to an instance during the launch process.
<details>
	<summary>Answer</summary>

	1. Attaching an ENI to an instance when it is stopped.

</details>

### Question 636: Can I attach more than one policy to a particular entity?
1. Yes always.
2. Only if within GovCloud.
3. No.
4. Only if within VPC.
<details>
	<summary>Answer</summary>

	1. Yes always.

</details>

### Question 637: By default, when an EBS volume is attached to a Windows instance, it may show up as any drive letter on the instance. You can change the settings of the [...] Service to set the drive letters of the EBS volumes per your specifications.
1. EBS Config Service.
2. AMI Config Service.
3. EC2 Config Service.
4. EC2-AMI Config Service.
<details>
	<summary>Answer</summary>

	3. EC2 Config Service.

</details>

### Question 638: Select the correct set of steps for exposing the snapshot only to specific AWS accounts.
1. Select public for all the accounts and check mark t hose accounts with whom you want to expose the snapshots and cl ick save.
2. Select Private, enter the IDs of t hose AWS accounts, and click Save.
3. Select Public, enter the IDs of those AWS accounts, and click Save.
4. Select Public, mark the IDs of those AWS accounts as private, and click Save.
<details>
	<summary>Answer</summary>

	3. Select Public, enter the IDs of those AWS accounts, and click Save.

</details>

### Question 639: How can you apply more than 100 rules to an Amazon EC2-Classic?
1. By adding more security groups.
2. You need to create a default security group specifying your required rules if you need to use more than 100 rules per security group.
3. By default the Amazon EC2 security groups support 500 rules.
4. You can't add more than 100 rules to security groups for an Amazon EC2 instance.
<details>
	<summary>Answer</summary>

	4. You can't add more than 100 rules to security groups for an Amazon EC2 instance.

</details>

### Question 640: A user has created an ELB with Auto Scaling. Which of the below mentioned offerings from ELB helps the user to stop sending new requests traffic from the load balancer to the EC2 instance when the instance is being deregistered while continuing in-flight requests?
1. ELB sticky session.
2. ELB deregistration check.
3. ELB auto registration Off.
4. ELB connection draining.
<details>
	<summary>Answer</summary>

	4. ELB connection draining.

</details>

### Question 641: What can I access by visiting the URL: http://status.aws.amazon.com/?
1. Amazon Cloud Watch.
2. Status of the Amazon RDS DB.
3. AWS Service Health Dashboard.
4. AWS Cloud Monitor.
<details>
	<summary>Answer</summary>

	3. AWS Service Health Dashboard.

</details>

### Question 642: In Route 53, what does a Hosted Zone refer to?
1. A hosted zone is a collection of geographical load balancing rules for Route 53.
2. A hosted zone is a collection of resource record sets hosted by Route 53.
3. A hosted zone is a selection of specific resource record sets hosted by CloudFront for distribution to Route 53.
4. A hosted zone is the Edge Location that hosts the Route 53 records for a user.
<details>
	<summary>Answer</summary>

	2. A hosted zone is a collection of resource record sets hosted by Route 53.

</details>

### Question 643: A user is launching an EC2 instance in the US East region. Which of the below mentioned options is recommended by AWS with respect to the selection of the Availability Zone?
1. Always select the AZ while launching an instance.
2. Always select the US-East-1-a zone for HA.
3. Do not select the AZ; instead let AWS select the AZ.
4. The user can never select the Availability Zone while launching an instance.
<details>
	<summary>Answer</summary>

	3. Do not select the AZ; instead let AWS select the AZ.

</details>

### Question 644: ec2-revoke RevokeSecurityGroup Ingress
1. Removes one or more security groups from a rule.
2. Removes one or more security groups from an Amazon EC2 instance.
3. Removes one or more rules from a security group.
4. Removes a security group from our account.
<details>
	<summary>Answer</summary>

	3. Removes one or more rules from a security group.

</details>

### Question 645: Select the correct statement
1. You don't need not specify the resource identifier while stopping a resource.
2. You can terminate, stop, or delete a resource based solely on its tags.
3. You can't terminate, stop, or delete a resource based solely on its tags.
4. You don't need to specify the resource identifier while terminating a resource.
<details>
	<summary>Answer</summary>

	3. You can't terminate, stop, or delete a resource based solely on its tags.

</details>

### Question 646: What is the time period with which metric data is sent to CloudWatch when detailed monitoring is enabled on an Amazon EC2 instance?
1. 15 minutes.
2. 5 minutes.
3. 1 minute.
4. 45 seconds.
<details>
	<summary>Answer</summary>

	3. 1 minute.

</details>

### Question 647: A large real -estate brokerage is exploring the option of adding a cost-effective location based alert to their existing mobile application The application backend infrastructure currently runs on AWS Users who opt in to this service will receive alerts on their mobile device regarding real-estate otters in proximity to their location. For the alerts to be relevant delivery time needs to be in the low minute count the existing mobile app has 5 million users across the us. Which one of the following architectural suggestions would you make to the customer?
1. The mobile application will submit its location to a web service endpoint utilizing Elastic Load Balancing and EC2 instances: DynamoDB will be used to store and retrieve relevant otters EC2 instances will communicate with mobile earners/device providers to push alerts back to mobile application.
2. Use AWS DirectConnect or VPN to establish connectivity with mobile carriers EC2 instances will receive the mobile applications' location through carrier connection: ROS will be used to store and relevant relevant offers EC2 instances will communicate with mobile carriers to push alerts back to the mobile application.
3. The mobile application will send device location using SQS.
4. EC2 instances will retrieve the re levant others from DynamoDB AWS Mobile Push will be used to send offers to the mobile application to push alerts back to the mobile application.
5. The mobile application will send device location using AWS Mobile Push EC2 instances will retrieve the relevant offers from DynamoDB EC2 instances will communicate with mobile carriers/device providers to push alerts back to the mobile application.
<details>
	<summary>Answer</summary>

	1. The mobile application will submit its location to a web service endpoint utilizing Elastic Load Balancing and EC2 instances: DynamoDB will be used to store and retrieve relevant otters EC2 instances will communicate with mobile earners/device providers to push alerts back to mobile application.

</details>

### Question 648: You are running PostgreSQL on Amazon RDS and it seems to be all running smoothly deployed in one Availability Zone. A database administrator asks you if DB instances running PostgreSQL support Multi-AZ deployments. What would be a correct response to this question?
1. Yes.
2. Yes but only for small db instances.
3. No.
4. Yes but you need to request the service from AWS.
<details>
	<summary>Answer</summary>

	1. Yes.

</details>

### Question 649: What is the data model of DynamoDB?
1. Since DynamoDB is schema-less, there is no data model.
2. 'Items', with Keys and one or more Attribute; and 'Attribute', with Name and Value.
3. 'Table', a collection of Items; 'Items', with Keys and one or more Attribute; and 'Attribute', with Name and Value.
4. 'Database', which is a set of 'Tables', which is a set of 'Items', which is a set of 'Attributes'.
<details>
	<summary>Answer</summary>

	3. 'Table', a collection of Items; 'Items', with Keys and one or more Attribute; and 'Attribute', with Name and Value.

</details>

### Question 650: What is a placement group in Amazon EC2?
1. It is a group of EC2 instances within a single Availability Zone.
2. It the edge location of your web content.
3. It is the AWS region where you run the EC2 instance of your web content.
4. It is a group used to span multiple Availability Zones.
<details>
	<summary>Answer</summary>

	1. It is a group of EC2 instances within a single Availability Zone.

</details>

