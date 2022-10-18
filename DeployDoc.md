# How to get started with Anonos Offer?

## Overview

Data Embassy® by Anonos® is the only technology that eliminates the tradeoff between data protection and utility, providing secure data processing in untrusted environments with cleartext utility and speed for faster insights to reach enterprise goals. The patented platform uniquely combines the best of data privacy and security techniques for the broadest spectrum of protection for data in use anywhere. Streamlined approvals and workflows mean more data can be approved more quickly for more use cases, including advanced analytics, artificial intelligence, machine learning, data sharing and data transfer. Data Embassy’s capabilities ensure the highest level of compliance for Schrems II, GDPR or any other global data privacy and security regulation and they include: 
•	Statutory pseudonymization 
•	Synthetic data 
•	Customizable risk-scoring profile
•	Centralized controls for decentralized data processing 
•	Protected, use-case-specific outputs called Variant Twins®
•	Privacy-impact assessment using k-anonymity
•	Controlled relinking to source data



## Tasks Included

1. How to access the offer?

2. How do deploy Offer?

3. What are the next steps after successful deployment of Anonos Offer?


## Pre-requisites

Before getting started with offer, user must fulfill below requirements-

The minimum hardware requirements for a single server are provided below. However, users can select any preferred size from the dropdown as per their requirement.

* **16Gb RAM**
* **30Gb Disk (SSD preferred) + Variant Twin Storage Capacity**
* **2 Processor minimum. Multiple cores recommended, particularly for higher data throughput**

**Note**: Keypairs must be precreated


### 1. How to access the offer?

1. Navigate to AWS Marketplace Homepage using link- https://aws.amazon.com/marketplace

2. You will be able to see Search Bar in top. 

3. Search for the offer using name "Data Embassy", you will get list of offers listed down.

4. For accurate search result, you can refine results using filters-

    |Setting|Value|
    |---|---|
    |Delivery Methods |**Cloudformation Template**|
    |Publisher|**Anonos Inc.**|
    |Pricing Model|**BYOL**|
    |Operating System|**All Linux/Unix, Ubuntu**|
    
5. Now, click on offer, you will be redirected to offer homepage
 
6. Go through Offer overview page, and click on **Continue to Subscribe**

7. In **Subscribe to this software** page, accept terms and conditions by clicking on **Accept Terms**

8. Wait for the completion of subscription process.

   **Note**: **After confirmation of this process, you will be able to view "Effective date" and "Expiration date" against product details**
            
9. Click on "Continue to Configuration" button

10. On **Configure this Software** page, fulfil all details and click on **Continue to launch** button.

11. Scroll to the bottom of the page and under **Choose action** seelct **Launch Cloudformation** and click on **Launch** button.

12. Now, the launch process would start and you would be able to see Instance launched.


### 2. How to deploy the offer?

1. To deploy offer, select the **Deployment type** as **CloudFormation Template** and click on **Launch Configuration**.

2. You will be redirected to Stack Configuration page. 

3. Configure the Parameters-

    **Instance Setup**

      |Setting|Value|
      |---|---|
      |DataEmbassy EC2 instance type |**Select the preferable size from dropdown**|
      |Key Pair Name|**Please use your own keypair**|
    
    
    **DataEmbassy Configuration**

      |Setting|Value|
      |---|---|
      |Provide the DNS to be mapped to the DataEmbassy Instance |**Enter DNS name**|
      |License Key Name|**Please enter your License key**|
    
    **Note**: If you do not have license key, please contact your Anonos representative for assistance. 
              Please refer to http://solutions.anonos.com for details on support; please email solutions@anonos.com
    
    
    **Network Configuration**

      |Setting|Value|
      |---|---|
      |Provide the IP Address range of the VPC|**Enter IP adress range of VPC**|
      |Provide the IP Address range of the Subnet|**Enter IP adress range of Subnet**|
      |Provide the IP Address range for SSH Access|**Enter IP adress range for SSH access**|
    
    
 4. Now Click on **Next**
   
 5. On **Configure Stack options**, click on **Next**

 6. On **Review page**, Click on **Create Stack**

 7. Stack would be created in few minutes. 

 8. Click on **Outputs** section to access the Data Embassy URLs.


### 3. What are the next steps after successful deployment of Anonos Offer?

1. Navigate to the EC2 instance and copy the Public IP, you would require this.

2. SSH to the account using your Public IP. 

3. Now, you will be asked for username.

   **Note**: By default username is **Ubuntu**
   
4. Now, your deployment setup is ready. You can proceed with your tasks. 


