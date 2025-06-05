# AWS-Mini-Project
AWS mini project for beginners



Project Name: Addition Made Easy!
AWS Services: AWS Amplify, API Gateway, Lambda, DynamoDB

![image alt](https://github.com/merina-poudyal/Addition-Made-Easy-/blob/main/Images/User%20interface%20.jpg?raw=true)
![image alt](https://github.com/merina-poudyal/Addition-Made-Easy-/blob/main/Images/writing%20to%20dynamodb.jpg?raw=true)

Diagramming Tool: Eraser.io

![image alt](https://github.com/merina-poudyal/Addition-Made-Easy-/blob/main/Images/Overall%20architecture.jpg?raw=true)


1.	DynamoDB
        a.	Partition Key: “Name” (String)
        b.	Table_Name
        c.	ARN of DynamoDB (For permission)

 ![image alt](https://github.com/merina-poudyal/Addition-Made-Easy-/blob/main/Images/Dynamodb%20setting.jpg?raw=true)

 
3.	Lambda Function 
        a.	Code Provided
        b.	Modify your Table name, Partition Key
 ![image alt](![function overview](https://github.com/user-attachments/assets/b347a3e1-8127-462d-8911-b024d063bf2f)
 ![image alt](https://github.com/merina-poudyal/Addition-Made-Easy-/blob/main/Images/Lambda%20code.jpg?raw=true)
  
   
5.	Permission for Lambda function
        a.	Execution Role (created by default)
        b.	Least Privilege Permission: Read and Write to DynamoDB (JSON Policy is also provided)

  	 ![image alt](https://github.com/merina-poudyal/Addition-Made-Easy-/blob/main/Images/lambda%20permission.jpg?raw=true)
 
7.	API gateway
        a.	POST method
        b.	API gateway Endpoint (Invoked URL) is provided to API calls

  	 ![image alt](https://github.com/merina-poudyal/Addition-Made-Easy-/blob/main/Images/API%20Gateway%20Post%20Method.jpg?raw=true)

        ![image alt](https://github.com/merina-poudyal/Addition-Made-Easy-/blob/main/Images/invoked%20URL.jpg?raw=true)

   
9.	AWS Amplify
        a.	Used for hosting website: Updating and deploying website is easy with AWS Amplify
        b.	Use zipped html file while uploading
        c.	index.html file is provided
 ![image alt](https://github.com/merina-poudyal/Addition-Made-Easy-/blob/main/Images/Amplify%20URL%20deployment%20.jpg?raw=true)
  	

 

