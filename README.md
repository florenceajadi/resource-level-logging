<h4>Resource Level Logging</h4>
<p>I'll be tracking and recording activities and changes made to this. It'll provide operations like creating, updating, and/or deleting resources. Performance metrics and health data spefic to each resource.
Security on access and modifying logs to monitor security-related events.</p>
<p>
  <img src="https://github.com/user-attachments/assets/d510e371-23b0-4769-b5e4-f7b2cfee62da" height="80%" width="80%" />
</p>
<p>
I was able to create a new diagnostic setting in my storage account that'll allow me to collect, route, and store logs and metrics from my resources so i'm able to monitor, analyze, and troubleshoot. 
I checked the logs in the category which would allow me to  tracks changes made to resouces like creating or deleting, log security events like access attempts and policy violations
  monitor Azure service status and availability, capture triggered alerts based on set conditions, log optimization suggestions from Azure Advisor, track policy enforcement and compliance checks.
 log actions taken by Azure's autoscale feature, and monitor the health of individual resources.</p>
  <p>
  <img src="https://github.com/user-attachments/assets/20bd3302-318c-4587-aec2-c54246191144" height="80%" width="80%" />
</p>
<p>
I created a Key Vault called CyberCat-KV-01. Which is going to securely store and manage sensitive information like secrets (sensitive data like pswds & API keys), and encryption keys for securing data, and certificates like SSL/TLS.
  This will help with access control, auditing, and compliance, ensuring that critical data is protected and managed securely.
</p>
    <img src="!https://github.com/user-attachments/assets/39dc29da-b667-44f7-9459-e3bdbe4cd66e" height="80%" width="80%" />
     <img src="https://github.com/user-attachments/assets/d1d60ffe-ba6d-41ea-a8ed-b17635683020" height="80%" width="80%" />
       <img src="https://github.com/user-attachments/assets/22470f0d-bdef-4657-88b7-2473132659e7" height="80%" width="80%" />
<p>I was able to create two Secrets in the new key vault which are confidential pieces of info like pswds, API keys, or connection strings. Creating a new diagnostic setting within my Key vaults to collect logs. </p>
<br />
<p>
searching for AzureActivity logs for anything related to resource groups that starts with "criticial-infrastructure-", which resulted to 5 resource groups.  It also shows the result by the time
  the activity occurred, which helps me track any operations like deletion on any of the critical resource groups. This is good for monitoring and ensuring the security and integrity of infrastructure.
</p>
 <img src="https://github.com/user-attachments/assets/3f3f9094-6bb7-4702-b73e-f3260ba105f9" height="80%" width="80%" />
 <img src="https://github.com/user-attachments/assets/23a9d878-cde8-4729-89f3-12c09d36ba72" height="80%" width="80%" />
<p>
 I created a new container so that I can organize and store blob files in my storage account. I'm going to upload the cybercat.txt into the Cybertest container.
</p>
<br />
  <img src="https://github.com/user-attachments/assets/b61b2964-2a3b-4c76-ab58-db6fa15668f7" height="80%" width="80%" />
   <img src="https://github.com/user-attachments/assets/b4675861-d298-403b-a26b-6e98c1cde9c2" height="80%" width="80%" />
<p>I was able to retrieve logs for authorization errors filtering entries that ends with Error and Statustext that end with NotFound in the earliest order. This helps show authorization errors due to missing blobs in my storage account.</p>
  
