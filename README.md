# E-Commerce Web Application
This is an e-commerce web application that allows customers to order clothing and get notifications after completing payment. This was implemented using Draw.io for architectural design, Django framework, Python, SQLite, and AWS Cloud9 for development, S3, Code Commit, Code Pipeline, Code Deploy, and Elastic Beanstalk for build and deployment.


<img width="482" alt="archit-image" src="https://github.com/Enemini/djangoapp/assets/40358115/8236b6d5-6101-4348-b1f6-0411381bdf0d">

## Analysis of Architectural Design Technology 
In this section, we will be having an in-depth look at the architecture along with an analysis of the different technologies utilized. 

A. Cloud9 AWS Cloud9 was used to write, run, and test the code. This is a browser-based IDE that runs on an AWS-managed EC2 instance. It allows you to code with just a browser and provides direct terminal access to AWS. 

B. GitHub version control was used as part of the Continuous Integration (CI) process to keep track of changes and allows provision for a reversal to the previous version in case something breaks. 

C. Code Pipeline is an AWS fully managed continuous delivery service, Code Pipeline, was used to automate code deployment. 

D. Elastic Beanstalk provides a platform for quickly and easily deploying, managing, and scaling web applications. Its' range of features such as health monitoring, auto-scaling, and deployment automation was used to make the process of web application hassle-free.

E. S3 was used to store and serve files and images.


## Summary
In this project, an online shopping web application was built and deployed using several cloud technologies. The application simulated an online shop where customers can search for products, add them to their cart, and eventually checkout. The code was written, tested and debugged using AWS Cloud9 browser-based IDE which has a terminal that allows git push and other commands. I tested the use of the CI/CD method by pushing the code to GitHub and routing through AWS CodePipeline. Automated provisioning of the environment was achieved through AWS Elastic Beanstalk, which configures the required resources (EC2 instances, S3 storage, database) The project attempts to assist the student to understand and develop the requisite skills needed to fit into an engineering team from requirement elicitation, design, implementation, deployment, and testing. I was able to critically analyze the advantages offered by current Cloud Technologies and the abounding challenges. Within the constraints of time and resources available, I was able to develop appreciable competency in several CI/CD and programming tools including Django, and Python libraries in addition to the Cloud Technologies listed above. The simple e-commerce website incorporated a personally developed Python Library and a code deployment pipeline was configured within AWS Cloud. As typical with most programming projects, several bugs and issues were encountered along the way. Many of them were dutifully addressed after long troubleshooting hours and some, due to time constraints, had to be accepted for now within the application. Overall, I was able to appreciate the significant effort required of DevOps Engineers and the several alternatives at their disposal. The advantages and Disadvantages of the different cloud-based technologies were also critically analyzed including best practices for continuous integration. 

## Functional and Non-Functional Requirement

### FUNCTIONAL REQUIREMENTS 
1) Capability to create products: The application should have the ability to add new product items. When a product item is to be created the description field is required. 
2) Capability to set prices: Each product item should have an associated cost. 
3) Capability to add product items to the cart: A customer should be able to add a product item to the cart for further processing 
4) Capability to capture sales instances: All transaction records should persist. 
5) Capability to generate invoices: The application should be able to print evidence of a transaction
 6) Merchant onboarding: Merchants should be able to register and do legitimate transactions on the platform.
7) Password encryption: All passwords should be encrypted in other to ensure maximum security 
8) Payment gateway integration: Payment gateway to facilitate online completion of transactions 

### NON-FUNCTIONAL REQUIREMENTS 
1) Performance/Availability: This ensures efficient and effective operation of the website as features such as page loading speed, secure files, and timely updates are implemented.
2) Reliability: This always ensures the availability and accessibility of the site through measures such as Backup for redundancy and application monitoring. 
3) Security: Using firewalls, secure authentication, encryption, and malware scanning the application is protected against attacks. 
4) Scalability: With the use of Amazon cloud services such as load balancer with autoscaling group, application scalability is adequately implemented.


