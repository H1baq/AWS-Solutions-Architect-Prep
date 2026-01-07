# AWS-Solutions-Architect-
A summary of all my AWS Solution architect resource for examination preparation.


AWS Solutions Architect - Fundamentals of Architecting on AWS
MODULE 1: Foundations of AWS Solution Design
- Solution Architect Roles
- Cloud Architecting
- AWS Well-Architected-Tools
- Best Practices

**Solution Architect Roles**

- Architects are responsible for designing, implementing, and managing an organization's cloud computing infrastructure. Solutions Architects serve as the bridge between complex business requirements and technical cloud solutions.

  **Key Responsibilities**
  
-Cloud strategy development
  Create the organization's cloud adoption roadmap and architecture vision.
  
-Solution Design
  Design scalable, cost-effective, and secure cloud infrastructure.
  
-Technology Solution
  Evaluate and select appropriate cloud providers and services.
  
-Migration Planning

  Develop strategies to transition from on-premises to cloud environments.
  
-Security & Compliance
  Ensure cloud implementations meet security standards and regulatory requirements.
  
-Cost Optimization
  Balance performance needs with budget constraints.
  
-Mentorship
 Guide development teams on cloud best practices.


**Tools and Technologies**

AWS Solutions Architects employ various tools and technologies to design effective cloud infrastructures. These tools are combined based on specific project requirements and organizational preferences.

<img width="763" height="359" alt="Screenshot from 2026-01-07 18-08-44" src="https://github.com/user-attachments/assets/f61b1028-6350-4b36-bbe2-1e6a6e717f1a" />

<img width="763" height="359" alt="Screenshot from 2026-01-07 18-08-38" src="https://github.com/user-attachments/assets/9b425d2f-9caf-4200-9e56-75c16fa3401e" />

<img width="763" height="359" alt="Screenshot from 2026-01-07 18-08-32" src="https://github.com/user-attachments/assets/02745ea4-c2f8-48f5-a4a4-f68495ae0f49" />

<img width="763" height="359" alt="Screenshot from 2026-01-07 18-08-12" src="https://github.com/user-attachments/assets/07a36317-9315-45e0-900f-0ab26bd18a4e" />


**AWS Well-Architected Framework**

The AWS Well-Architected Framework documents a set of foundational questions that allow you to understand if a specific architecture aligns well with cloud best practices. The framework provides a consistent approach to evaluating systems against the qualities you expect from modern cloud-based systems, and the remediation that would be required to achieve those qualities.

Why use the AWS Well-Architected Framework?


Build and deploy faster: By reducing emergency response and capacity management and by using automation, you can experiment and release value more often.


Lower or mitigate risks: Understand where you have risks in your architecture, and address them before they impact your business and distract your team.


Make informed decisions: Ensure that you have made active architectural decisions that highlight how they might impact your business outcomes.


Learn AWS best practices: Make sure your teams are aware of best practices that we have learned through reviewing thousands of architectures on AWS.

AWS Well-Architected is a risk quantification tool. Use it to learn, measure, and improve your cloud architectures over time.

The AWS Well-Architected Framework provides mechanisms to evaluate your architectures, and provides guidance to implement designs that scale with your application needs.

**Six Pillars**

The six pillars of the AWS Well-Architected Framework are:

Operational Excellence
The ability to run and monitor systems to deliver business value and continually improve supporting processes and procedures.

Reliability
The ability of a workload to perform its intended function correctly and consistently when it’s expected to. Reliable systems should:

• Recover from infrastructure or service disruptions.

Security
The ability to protect information, systems, and assets while delivering business value through risk assessments and mitigation strategies.

Performance Efficiency
The ability to use computing resources efficiently to meet system requirements and the ability to maintain that efficiency as demand changes and technologies evolve.

Cost Optimization
The ability to run systems to deliver business value at the lowest price point.

Sustainability
The ability to continually improve sustainability impacts by reducing energy consumption and increasing efficiency across all components of a workload.

Maximize the benefits from the provisioned resources and minimize the total resources required.

These pillars are based on design principles and best practices to help you build cloud systems that deliver on your expectations and requirements.


**AWS Well-Architected Tool**

The AWS Well-Architected Tool (AWS WA Tool) is a self-service tool that helps you review and measure the state of your workloads in comparison to the latest AWS architectural best practices.

<img width="482" height="190" alt="Screenshot from 2026-01-07 18-22-10" src="https://github.com/user-attachments/assets/4353e00d-afea-42c7-86e9-5eff0003a301" />

**AWS Well-Architected Tool Features**

The AWS Well-Architected Tool provides several features to help apply architectural best practices, identify risks, and implement improvements to cloud workloads in a structured manner.

Workload
A workload identifies a set of components that deliver business value. Examples of workloads include marketing websites, ecommerce websites, the backend for a mobile app, and analytic platforms.

Workloads vary in their level of architectural complexity. They can be simple (such as a static website) or complex (such as microservices architectures with multiple data stores and many components).

Within a workload, you identify elements such as Review Owner, Environment, Regions, and Account IDs.

<img width="1438" height="258" alt="image" src="https://github.com/user-attachments/assets/2634d141-fc57-414d-a97d-bacdd255a8f0" />


Milestones
Milestones mark key changes in your architecture as it evolves throughout the product lifecycle (design, testing, go live, and production).

<img width="820" height="330" alt="image" src="https://github.com/user-attachments/assets/5672a24a-d5da-4b3a-9fe3-63162a19b325" />

Lenses
Lenses provide a way for you to consistently measure your architectures against best practices and identify areas for improvement.              

In addition to the lenses provided by AWS, which use the Well-Architected Framework pillars, you can also create and use your own custom lenses, or use lenses that others have shared with you.

If a question does not apply to a specific workload, choose to disable this question.

<img width="910" height="720" alt="image" src="https://github.com/user-attachments/assets/b8164305-6921-4739-a47f-65a9ae62dcd5" />



High-risk issues
High-risk issues (HRIs) are architectural and operational choices that AWS has found might result in significant negative impact to a business. These HRIs might affect organizational operations, assets, and individuals.

<img width="1454" height="631" alt="image" src="https://github.com/user-attachments/assets/fcb60577-32f0-4265-acc7-47c76ce8c212" />



Medium-risk issues
Medium-risk issues (MRIs) are architectural and operational choices that AWS has found might negatively impact business, but to a lesser extent than HRIs.

<img width="1454" height="631" alt="image" src="https://github.com/user-attachments/assets/dcdcb74d-6c15-46c0-afae-f99d27888a5c" />


**Best Practices**

AWS Architectural Best Practices

AWS architectural best practices are organized around the six key pillars from the AWS Well-Architected Framework. These best practices guide you in building secure, high-performing, resilient, and efficient infrastructures.

Well-Architected Pillars

Security
Defense in Depth: Implement multiple security controls at different layers.

Identity and Access Management: Use AWS IAM with least privilege principle.

Data Protection: Encrypt data at rest and in transit using KMS, CloudHSM.

Network Security: Implement Security Groups, NACLs, WAF, and Shield.

Compliance and Auditing: Utilize AWS Config and Security Hub.

Cost optimization
Appropriate Resource Sizing: Use right-sized resources for your workload

Reserved Instances/Savings Plans: Commit to usage for significant discounts

Spot Instances: Use for non-critical, interruptible workloads

Cost Monitoring: Implement AWS Cost Explorer and Budgets

Storage Lifecycle Policies: Automate data migration to lower-cost tiers

Reliability
Fault Isolation: Use multiple Availability Zones and Regions

Scaling: Implement Auto Scaling for dynamic workloads

Recovery Planning: Design for automatic recovery with minimal data loss

Testing Recovery Procedures: Regularly conduct disaster recovery testing

Loose Coupling: Design services to reduce interdependencies

Performance efficiency
Right-Sizing Resources: Select appropriate instance types for your workload

Leveraging Managed Services: Use AWS services instead of managing infrastructure

Caching: Implement ElastiCache or CloudFront to improve performance

Data Storage Optimization: Choose the right storage service (S3, EBS, EFS)

Serverless Architecture: Consider AWS Lambda for event-driven workloads

Operational excellence
Infrastructure as Code: Consider using AWS CloudFormation to automate deployments

Monitoring and Observability: Implement AWS CloudWatch, X-Ray, and CloudTrail

Continuous Integration/Continuous Delivery: Leverage AWS CodePipeline, CodeBuild, and CodeDeploy

Runbooks and Playbooks: Document procedures for routine operations and incident response

Sustainability
Resource Utilization: Maximize efficiency to minimize environmental impact

Region Selection: Choose regions with more sustainable energy sources when possible

Managed Services: Leverage AWS's economies of scale for better sustainability

Workload Optimization: Improve code efficiency to reduce compute needs

** These best practices should be continuously evaluated and applied throughout the lifecycle of your AWS-based applications and infrastructure to ensure optimal performance, security, and cost-effectiveness.

Planning

Planning is not only the initial step in architecting, it is a critical step. A planning framework provides a structured approach to architecting while ensuring all critical aspects are considered.

1. Start with Business Requirements

2. Design for Failure

3. Implement Security at Every Layer

4. Automate Where Possible

5. Use Managed Services

6. Monitor and Measure

7. Stay Current


The AWS Architecture Center provides a comprehensive collection of resources to help you build well-architected systems and applications on AWS. Offerings include reference architectures, documentation, and ready to deploy solutions.


**Functional vs. Non-functional Requirements**

Functional requirements - define what a product/system must do and what its features and functions are.

Functional requirements are the primary way that a customer communicates their requirements to the project team.

Functional requirements help to keep project team going in the right direction.

<img width="701" height="458" alt="Screenshot from 2026-01-07 18-41-24" src="https://github.com/user-attachments/assets/bf81d864-db2d-4777-8f00-e46ce0de9ee1" />


**Non-functional requirements**  - describe the general properties of a system.

Typically, a customer has both needs and wants:

After seeing the cost estimate, they may ask to reduce the scope (Usually removing some of the non-functional requirements reduces the scope).

A lot of non-functional requirements can quickly drive up the cost.

Insufficient non-functional requirements may lead to bad user experience.

<img width="702" height="455" alt="Screenshot from 2026-01-07 18-42-00" src="https://github.com/user-attachments/assets/adf27d6e-f191-4ce9-83b7-5a957380f025" />







