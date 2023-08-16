# Welcome to My Yelp
***

## Task
Deploy an application built in ReactJS into Amplify (AWS) using authentification.

## Description
Understanding the concept of authentification
Authentication:
    Amplify Authentication provides a backend authentication service with Amazon Cognito, frontend libraries, and a drop-in Authenticator UI component. Authentication is a process to validate who you are - features include user sign up, user sign in, multi-factor authentication, user sign-out, and passwordless sign-in. You can also authenticate users by integrating with federated identity providers such as Amazon, Google, and Facebook. Amplify Authentication integrates seamlessly with other Amplify categories such as API, analytics, and storage so you can define authorization rules for unauthenticated and authenticated users.
GraphQL API with AWS AppSync:
    The Amplify API category provides a managed GraphQL service with AWS AppSync, and a REST API service with Amazon API Gateway to build a serverless backend for your web or mobile app. With AppSync, you can build scalable applications, including those requiring real-time updates, on a range of data sources such as NoSQL data stores, relational databases, HTTP APIs, and your custom data sources. The Amplify CLI has a GraphQL Transform that helps you define your application's data model in hirearchial structures.
Hosting
Working with multiple environments and 
Removing services

## Installation
To get started, we first need to create a React project using the create-react-app boilerplate:
npx create-react-app amplify-app --typescript

Let’s now install the AWS Amplify and AWS Amplify React bindings and try running the application:
npm install --save aws-amplify aws-amplify-react

To install the CLI:
npm install -g @aws-amplify/cli

Now we need to configure the CLI with our credentials:
amplify configure



## Usage
Run "npm start" on the terminal:
On every update, or mutation action such as creating of restaurant the page has to reload to reflect the changes

Run "amplify status" on the terminal:
This will show you the services you've added already & if it's locally configured or deployed.

Run "amplify add <category>" on the terminal:
This will allow you to add features like Authentication, API etc.

Run "amplify push" on the terminal:
The command above helps you build all your local backend resources and provision it in the cloud.

Run "amplify console" on the terminal:
The command helps you open the amplify console on Amazon Web Services to view your project status.

Run "amplify publish" on the terminal:
This command will build all your local backend and frontend resources (if you have hosting category added) & provision it in the cloud.
```
./my_yelp
```

### The Core Team
The project involve just an individual hence:
Author: Habeeb Suleiman

<span><i>Made at <a href='https://qwasar.io'>Qwasar SV -- Software Engineering School</a></i></span>
<span><img alt='Qwasar SV -- Software Engineering School's Logo' src='https://storage.googleapis.com/qwasar-public/qwasar-logo_50x50.png' width='20px'></span>
