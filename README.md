# AWS Serverless Data Management Project  




📌 Project Overview

This project demonstrates a serverless data management architecture using AWS services.
It integrates relational and NoSQL databases with AWS Lambda for scalable, event-driven data operations.

🛠️ AWS Services Used

AWS RDS (Relational Database Service)

AWS DynamoDB

AWS Lambda

AWS IAM



🏗️ Architecture

The system uses AWS Lambda to interact with:

RDS for structured relational data

DynamoDB for fast NoSQL operations

This design enables scalable data processing without managing servers.

## 💡 Why This Project Matters

This project demonstrates how modern cloud applications can:
- Use serverless compute for scalability
- Combine relational and NoSQL databases
- Reduce infrastructure management overhead
- Enable event-driven data workflows

These patterns are widely used in real-world cloud and DevOps environments.




⚙️ Implementation Steps

Created an RDS instance with a managed database engine

Created a DynamoDB table with a primary key

Configured an IAM role with permissions for Lambda to access RDS and DynamoDB

Created an AWS Lambda function to:

Insert data

Fetch data

Interact with both RDS and DynamoDB

Tested Lambda functions using the AWS Management Console






## 📸 Screenshots
Screenshots of the AWS resources and outputs are included in the repository.

### 📸 Screenshots

1. **DynamoDB Table Items**  
![DynamoDB Table Items](screenshots/dynamodb-table-items.png)

2. **Lambda Function Code Logic**  
![Lambda Function Code Logic](screenshots/lambda-code-logic.png)

3. **Lambda Test Response**  
![Lambda Test Response](screenshots/lambda-test-response.png)

4. **MySQL Query Validation**  
![MySQL Query Validation](screenshots/mysql-query-validation.png)

5. **RDS Connection Success**  
![RDS Connection Success](screenshots/rds-connection-success.png)

6. **RDS Metrics Summary**  
![RDS Metrics Summary](screenshots/rds-metrics-summary.png)





📈 Learning Outcome

Understanding of serverless architecture

Hands-on experience with AWS relational and NoSQL databases

Lambda integration with multiple data sources

IAM role and permission management


---

🚀 Future Improvements

API Gateway integration for RESTful endpoints

Infrastructure as Code (IaC) using Terraform

CI/CD automation for deployment

---

**Author: Hina Atif**

