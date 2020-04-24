Deploy Static Website on AWS

In this project, you will deploy a static website to AWS using S3, CloudFront, and IAM.

The files included are: 

index.html - The Index document for the website.
/img - The background image file for the website.
/vendor - Bootssrap CSS framework, Font, and JavaScript libraries needed for the website to function.
/css - CSS files for the website.


Cloud Fundamentals Project
The cloud is perfect for hosting static websites that only include HTML, CSS, and JavaScript files that require no server-side processing. In this project, you will deploy a static website to AWS. First, you will create a S3 bucket and upload the website files to your bucket. Next, you will configure the bucket for website hosting and secure it using IAM policies. Next, you will speed up content delivery using AWS’ content distribution network service, CloudFront. Lastly, you will access your website in a browser using the unique CloudFront endpoint.

Topics Covered:
S3 bucket creation
S3 bucket configuration
Website distribution via CloudFront
Access website via web browser

Dependencies
Cloud Services

Amazon Web Services S3 - Resource hosting and deployments
AWS CloudFront - CDN for SPA
AWS EKS - Backend API
AWS DynamoDB - Persistent Datastore
AWS Cognito - User Authentication

Performance Tracking and DevOps Tools:
AWS CloudWatch - Performance and Health checks
Sentry - Bug Reporting

Alternates:
TBD
Google Analytics - Usage Reporting

Alternates:
Mixpanel
Travis (CI/CD)

Frameworks:
Ionic (Javascript) (Frontend)
Node.js (Javascript) (Backend)