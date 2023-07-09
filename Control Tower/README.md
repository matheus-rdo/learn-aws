# Control Tower

Control Tower is a extension of AWS Organizations, designed to set up and govern a secure, multi-account AWS environment.

- Multi-account architecture
- Initial security baseline
- Automate creation of AWS accounts
- Enforce best practices and regulatory requirements
- Logging

## Landing Zone

Landing Zone is a enterprise-wide container that holds all of your Organizational Units (OU), accounts, users, and resources that requires compliance and security regulations.  

You have **two different ways** to delivery a Landing Zone
- AWS Control Tower: AWS Managed service w/ Framework of known best practices
- Custom-built landing zone: Customer or Partner managed orchestrations

### Landing Zone provided by AWS Control Tower
![Landing Zone Resources](/Control%20Tower/imgs/aws-control-tower.png "Landing Zone Resources")  
  
**Benefits over Custom-built solution:**

- AWS-provided guardrails and compliance policies applied **by default**
- Central dashboard for monitoring and compliance status
- Account factory for provisioning new accounts 
- Centralized Logging

### Custom-built landing zone

- Implement your own customized landing zone