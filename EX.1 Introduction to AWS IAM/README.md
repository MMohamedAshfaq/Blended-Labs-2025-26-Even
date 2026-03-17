Lab 1 - Introduction to AWS Identity and Access Management (IAM)
Title
Introduction to AWS Identity and Access Management (IAM)

Objective
The objective of this lab is to understand how AWS Identity and Access Management (IAM) controls authentication and authorization in AWS. The lab focuses on exploring IAM users and groups, analyzing attached policies, assigning users to appropriate groups based on organizational roles, and validating permissions by testing service access.

Prerequisites
Basic understanding of cloud computing concepts
AWS Academy Lab access
Web browser with internet connectivity
Tools Used
AWS Management Console
AWS Identity and Access Management (IAM)
Amazon EC2
Amazon S3
Tasks Performed
Task 1: Explore IAM Users and Groups
Reviewed pre-created IAM users: user-1, user-2, user-3
Explored IAM groups: EC2-Admin, EC2-Support, S3-Support
Inspected managed and inline policies attached to groups
Screenshot: image
<img width="1726" height="826" alt="image" src="https://github.com/user-attachments/assets/429d27e7-e37e-41bc-a251-de7553514ff5" />


Task 2: Add Users to Groups
Added user-1 to the S3-Support group
Added user-2 to the EC2-Support group
Added user-3 to the EC2-Admin group
Screenshot: image
<img width="1726" height="818" alt="image" src="https://github.com/user-attachments/assets/7063da03-62f1-4816-a63d-1e7a52a90d8f" />


Task 3: Test IAM User Permissions
Logged in using IAM sign-in URL
Verified S3 access for user-1
Verified EC2 read-only access for user-2
Verified EC2 administrative access for user-3
Screenshot: 
<img width="2528" height="1434" alt="cc3" src="https://github.com/user-attachments/assets/9e4a3dfe-d06a-4d03-abdf-f2d112ae8505" />

Workflow
Accessed IAM console and reviewed users and groups.
Inspected policy permissions attached to groups.
Assigned users to groups based on their roles.
Logged in as each IAM user using the sign-in URL.
Validated permissions by accessing AWS services.
Learning Outcomes
Understood the role of IAM in AWS security.
Learned how IAM users, groups, and policies interact.
Gained practical experience implementing role-based access control.
Verified permission enforcement through real-time service testing.
Conclusion
This lab provided hands-on experience with AWS IAM by demonstrating how organizations manage secure access to cloud resources. Assigning users to groups with predefined policies simplified permission management and ensured role-based access control across AWS services.

Author
Name: M.Mohamed Ashfaq
and (Reg No) 212224240090
Course: Introduction to Cloud Computing
