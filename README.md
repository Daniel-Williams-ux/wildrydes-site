# wildrydes-site

## Introduction: Build a Serverless Web Application

### Prerequisites

1.  AWS account, 
2. An account with ArcGIS to add mapping to your app, 
3. Text editor, and a web browser.

### Application architecture

The application architecture uses AWS Lambda, Amazon API Gateway, Amazon DynamoDB, Amazon Cognito, and AWS Amplify Console.
Amplify Console provides continuous deployment and hosting of static web resources including HTML, CSS, JavaScript, and image files loaded in the user's browser. 
JavaScript executed in the browser sends and receives data from a public backend API built using Lambda and API Gateway. 
Amazon Cognito provides user management and authentication functions to secure the backend API. 
Finally, DynamoDB provides a persistence layer where the API's Lambda function can store data.

 ### Contents

1. Host a Static Website: Configure AWS Amplify to host the static resources for the web application with continuous deployment built-in
2. Manage Users: Create an Amazon Cognito user pool to manage users' accounts
3. Build a Serverless Backend: Build a backend process for handling requests for your web application
4. Deploy a RESTful API: Use Amazon API Gateway to expose the Lambda function built as a RESTful API
 
