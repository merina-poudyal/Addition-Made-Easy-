# AWS-Mini-Project
AWS mini project for beginners



Project Name: Addition Made Easy!



AWS Services: AWS Amplify, API Gateway, Lambda, DynamoDB

https://github.com/merina-poudyal/Addition-Made-Easy-/blob/f26895517761a16daaa537cb19a0681bfee2a6c3/Images/User%20interface%20.jpg

https://github.com/merina-poudyal/Addition-Made-Easy-/blob/main/Images/writing%20to%20dynamodb.jpg


Diagramming Tool: Eraser.io

https://github.com/merina-poudyal/Addition-Made-Easy-/blob/main/Images/Overall%20architecture.jpg

1.	DynamoDB
        a.	Partition Key: “Name” (String)
        b.	Table_Name
        c.	ARN of DynamoDB (For permission)

https://github.com/merina-poudyal/Addition-Made-Easy-/blob/main/Images/Dynamodb%20setting.jpg
  
3.	Lambda Function 
        a.	Code Provided
        b.	Modify your Table name, Partition Key

   https://github.com/merina-poudyal/Addition-Made-Easy-/blob/main/Images/function%20overview.png
   https://github.com/merina-poudyal/Addition-Made-Easy-/blob/main/Images/Lambda%20code.jpg
 
   
5.	Permission for Lambda function
        a.	Execution Role (created by default)
        b.	Least Privilege Permission: Read and Write to DynamoDB (JSON Policy is also provided)

  	 https://github.com/merina-poudyal/Addition-Made-Easy-/blob/main/Images/lambda%20permission.jpg

 
7.	API gateway
        a.	POST method
        b.	API gateway Endpoint (Invoked URL) is provided to API calls

  	https://github.com/merina-poudyal/Addition-Made-Easy-/blob/main/Images/API%20Gateway%20Post%20Method.jpg
   https://github.com/merina-poudyal/Addition-Made-Easy-/blob/main/Images/invoked%20URL.jpg
 

9.	AWS Amplify
        a.	Used for hosting website: Updating and deploying website is easy with AWS Amplify
        b.	Use zipped html file while uploading
        c.	index.html file is provided

  	https://github.com/merina-poudyal/Addition-Made-Easy-/blob/main/Images/Amplify%20URL%20deployment%20.jpg
   

 

