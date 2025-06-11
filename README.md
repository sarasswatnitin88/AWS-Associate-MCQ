9# AWS-Associate-MCQ

AWS Associate & Security Scenario: Investigating a Security Incident

You are an AWS Certified Solutions Architect Associate with security expertise, working for an e-commerce company. A security alert is triggered due to unusual outbound traffic from an EC2 instance.

Investigation:
CloudTrail & GuardDuty detect unauthorized API calls from an IAM user.
IAM logs show multiple failed login attempts.
AWS Config reveals an open SSH port (22) to the public internet.

Mitigation & Response:
Disable compromised IAM user and rotate credentials.
Isolate the EC2 instance using VPC Security Groups.
Take snapshots for forensic analysis.
Implement MFA for all IAM users and enforce strict access control.
Use AWS Systems Manager Session Manager instead of SSH.
Update AWS WAF rules to block suspicious IPs.

Post-Incident Security Enhancements:
Enable AWS Security Hub for centralized security management.
Automate security responses using AWS Lambda (e.g., disabling compromised accounts).
Monitor continuously with Amazon GuardDuty and CloudWatch.



1. What type of storage does Amazon S3 provide?
   
Answer:  Object Storage

Hint: S3 is designed to store objects like images, backups, and logs.

3. What AWS service allows you to run serverless code?
   
Answer:  Lambda

Hint: It runs code without managing servers.

5. Which AWS service provides a fully managed relational database?
   
Answer:  RDS

Hint: Managed databases like MySQL and PostgreSQL.

7. What is the primary use of Amazon CloudFront?

Answer:  Content Delivery Network (CDN)

Hint: It speeds up content delivery globally.

5. Which service enables private connections between VPCs and AWS services?
   
Answer: AWS PrivateLink

Hint: Securely connects services inside AWS.

7. What AWS service is used for DNS and domain name management?

Answer:  Route 53

Hint: Named after a common network port.

7. Which storage service is ideal for structured NoSQL databases?
   
Answer:  DynamoDB

Hint: Managed NoSQL database service.

9. What AWS service is used for monitoring resources and logs?
    
Answer: CloudWatch

Hint: Watches metrics and logs.

11. Which AWS storage class is best for long-term archival storage?

Answer: S3 Glacier

Hint: Cold storage with retrieval delays.

13. What AWS service is used to automate application deployments?
    
Answer:  CodeDeploy

Hint: Helps deploy applications automatically.

15. Which database service is best for petabyte-scale analytics?
    
Answer: Redshift

Hint: AWS’s data warehouse service.

17. What service helps protect against DDoS attacks?
    
Answer:  Shield

Hint: Specialized in DDoS mitigation.

19. What AWS service offers a managed Kubernetes solution?
    
Answer:  EKS

Hint: Managed Kubernetes on AWS.

21. Which AWS service is used for Infrastructure as Code (IaC)?
    
Answer: CloudFormation

Hint: Manages AWS resources using templates.

23. Which storage service is designed for file-based workloads?
    
Answer:  EFS

Hint: Elastic file system for Linux.

25. What AWS service is used to create a virtual private cloud?
    
Answer:  VPC

Hint: Allows network isolation in AWS.

27. What AWS service can be used to manage encryption keys?
    
Answer:  KMS

Hint: Manages encryption keys securely.

29. Which AWS service is used for server migration?
    
Answer:  SMS

Hint: Stands for Server Migration Service.

31. What AWS service provides virtual desktops?
    
Answer:  WorkSpaces

Hint: Cloud-based desktop solution.

33. Which AWS service is used to stream real-time data?
    
Answer:  Kinesis

Hint: Processes large data streams.

35. What AWS service provides compliance auditing and governance?
    
Answer:  Config

Hint: Tracks AWS resource configurations.

37. Which service is used for batch processing workloads?

Answer:  AWS Batch

Hint: Runs batch jobs efficiently.

39. What AWS service provides a pay-per-use API Gateway?

Answer: API Gateway

Hint: Manages REST and WebSocket APIs.

24. What AWS service provides distributed denial-of-service (DDoS) protection?
    
Answer:  Shield

Hint: AWS’s DDoS protection service.

26. Which AWS service is used to automatically distribute traffic across multiple targets?
    
Answer:  ELB

Hint: Stands for Elastic Load Balancer.

28. What service allows you to run containers without managing servers?
    
Answer:  Fargate

Hint: Serverless container management.

30. What AWS tool is used to create and manage access policies?
    
Answer:  IAM

Hint: Identity and Access Management.

32. What AWS service helps manage machine learning models?
    
Answer:  SageMaker

Hint: Helps train and deploy ML models.

34. What service helps migrate databases to AWS?
    
Answer:  DMS

Hint: Stands for Database Migration Service.

36. Which AWS service allows you to securely store credentials and API keys?

Answer:  Secrets Manager

Hint: Manages sensitive application secrets.

38. What AWS service provides identity and access management?
    
Answer: IAM

Hint: Manages users, roles, and policies.

40. What AWS service helps detect security anomalies in your AWS account?

Answer: GuardDuty

Hint: Uses machine learning to detect threats.

42. Which AWS service is used to encrypt stored data?
    
Answer: KMS

Hint: Manages encryption keys securely.

44. What AWS service logs all API calls made in an AWS account?
    
Answer: CloudTrail

Hint: Tracks AWS API activity.

46. What AWS service helps protect applications from SQL injection and XSS attacks?
    
Answer: WAF

Hint: Web Application Firewall.

48. What AWS service protects against DDoS attacks?
    
Answer: Shield

Hint: AWS’s DDoS protection service.

50. What AWS service scans your EC2 instances for vulnerabilities?
    
Answer: Inspector

Hint: Automated security assessments.

52. Which AWS security service continuously monitors AWS configurations?
    
Answer: Config

Hint: Helps with compliance and audits.

54. Which AWS service enables secure secrets management?

Answer: Secrets Manager

Hint: Stores and rotates API keys securely.

56. What AWS service automatically detects and prevents fraud and abuse?
Answer: Fraud Detector
Hint: Machine learning for fraud prevention.

57. What AWS service helps classify sensitive data in S3?
Answer: Macie
Hint: Uses AI to detect sensitive data.

58. What AWS security tool provides hardware security modules (HSMs)?
Answer: CloudHSM
Hint: Dedicated encryption hardware.

59. What AWS service provides single sign-on (SSO) access?
Answer: AWS SSO
Hint: Centralized login management.

60. What AWS service provides multi-factor authentication (MFA)?
Answer: IAM
Hint: Adds extra login security.

61. What AWS service allows federated access to AWS accounts?
Answer: Cognito
Hint: Identity provider for apps.

62. What AWS service scans S3 buckets for security risks?
Answer: Macie
Hint: AI-powered sensitive data detection.

63. Which AWS security tool allows private network connections to AWS services?
Answer: PrivateLink
Hint: Secure VPC-to-service connections.

64. Which service helps you securely manage and rotate encryption keys?
Answer: KMS
Hint: Secure key management.

65. Which AWS service automatically remediates security compliance violations?
Answer: Config
Hint: Ensures compliance with security rules.

66. What AWS service is used for real-time security monitoring?
Answer: GuardDuty
Hint: Detects AWS account threats.

67. What AWS feature allows organizations to enforce security policies across accounts?
Answer: AWS Organizations
Hint: Centralized security governance.

68. What AWS service is designed for security analytics and threat detection?
Answer: Security Hub
Hint: Centralized security management.

69. What AWS tool provides compliance reports and certifications?
Answer: Artifact
Hint: Download compliance reports.

70. Which AWS service helps enforce security best practices across AWS resources?
Answer: Security Hub
Hint: Monitors compliance at scale.

71. Which AWS service blocks malicious IPs automatically?
Answer: WAF
Hint: Web security firewall.

72. What AWS service prevents brute-force attacks on AWS accounts?
Answer: GuardDuty
Hint: Monitors for suspicious activities.

73. What AWS feature allows restricting access based on conditions?
Answer: IAM Policies
Hint: Access control rules.

74. What AWS tool allows for cross-account security auditing?
Answer: CloudTrail
Hint: Tracks AWS API calls.

75. What AWS service provides real-time alerts for suspicious activities?
Answer: GuardDuty
Hint: AI-driven threat detection.

76. What AWS tool allows enforcing fine-grained permissions?
Answer: IAM
Hint: Controls access to AWS resources.

61.Your security team wants to track all API calls in your AWS account. Which service should you use?
Answer: CloudTrail
Hint: Logs AWS API activity.

62.A developer stores API keys in plain text in an S3 bucket. Which service can detect and alert on this?
Answer: Macie
Hint: Detects sensitive data in S3.

63.A company wants to allow temporary AWS console access to an external auditor. Which method should they use?
Answer: IAM Role
Hint: Best for temporary permissions.

64.A developer accidentally makes an S3 bucket public. Which AWS service can detect this?
Answer: AWS Config
Hint: Tracks resource configuration changes.

65.Your company wants to detect unusual login attempts to your AWS account. Which service should you use?
Answer: GuardDuty
Hint: Monitors AWS for threats.

66.You need to scan EC2 instances for security vulnerabilities. Which AWS service should you use?
Answer: Inspector
Hint: Automated security assessments.

67Your company wants to centrally manage security findings across multiple AWS accounts. What should they use?
Answer: Security Hub
Hint: Centralized security management.

68.Your security team wants to restrict outbound traffic from EC2 instances. What should they use?
Answer: NACLs
Hint: Network-level traffic filtering.

69.Your team wants to block IP addresses associated with malicious activity. What should they use?
Answer: WAF
Hint: Can block IPs at the network level.

70.Your security team wants to ensure that data is encrypted before being sent to S3. What should they do?
Answer: Use Server-Side Encryption
Hint: Ensures S3 data is encrypted.

80.Which AWS service provides DDoS protection?

Shield  
(Hint: Protects against DDoS)

81.Which AWS service helps detect security threats?

GuardDuty 
(Hint: Monitors for threats)

82.Which AWS service manages encryption keys?

KMS 
(Hint: Manages keys)

83.Which AWS feature allows setting security rules at the subnet level?

NACL 
(Hint: Network level rules)

84.Which AWS service helps classify and protect sensitive data?

Macie 
(Hint: Finds PII)

85.Which AWS service provides centralized logging?

CloudTrail 
(Hint: Tracks API activity)

86.Which AWS service scans for vulnerabilities in EC2 instances?

Inspector 
(Hint: Security assessment)

87.Which AWS feature controls user access permissions?

IAM 
(Hint: Manages identities)

88.Which AWS service provides a Web Application Firewall?
WAF 
(Hint: Protects web apps)

89.Which AWS feature acts as a firewall for EC2 instances?

Security Group 
(Hint: Instance-level protection)

90.Which AWS service helps securely store and retrieve credentials?

Secrets Manager
(Hint: Stores secrets)

91.Which AWS service provides hardware-based key storage?

CloudHSM 
(Hint: Dedicated hardware security)

92.Which AWS security service continuously monitors compliance?

Config 
(Hint: Tracks resource changes)




new ctf 15.txt
Displaying new ctf 15.txt.
