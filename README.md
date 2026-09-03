\# Personal Finance Tracker



A simple web-based Personal Finance Tracker that helps users record and manage their daily expenses.



\## Features



\* Add new expenses

\* Enter amount, category, and description

\* View saved transactions

\* Update existing expenses

\* Delete expenses

\* Unique transaction IDs

\* Cloud-based backend using AWS



\## Technologies Used



\* HTML

\* CSS

\* JavaScript

\* AWS Lambda

\* Amazon API Gateway

\* Amazon DynamoDB

\* Amazon S3



\## Project Architecture



```text

User

&#x20; ↓

S3 Static Website

&#x20; ↓

API Gateway

&#x20; ↓

AWS Lambda

&#x20; ↓

Amazon DynamoDB

```



\## How It Works



1\. The user enters an expense in the web application.

2\. The frontend sends the data to API Gateway.

3\. AWS Lambda processes the request.

4\. The expense is stored in DynamoDB.

5\. The application retrieves and displays the stored expenses.



\## Project Status



Completed and deployed as an AWS-based Personal Finance Tracker.



\## Author



\*\*Saidaiah Ratala\*\*



