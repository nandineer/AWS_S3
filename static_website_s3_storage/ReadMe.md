# AWS_StaticWebSite_S3

![image](https://github.com/nandineer/AWS/assets/22636122/c4585c8c-eaaa-43fb-b5c8-a8d7633a32b0)


**Step #1: Design Your Website Step **

**Step #2: Set Up Amazon S3 Bucket **

    •	Go to the AWS Management Console and open the Amazon S3 console.
    •	Click "Create bucket" and enter a unique name for your bucket. 
    •	In the "Properties" section, enable "Static website hosting." Upload your website files to the bucket.  
    •	Set the bucket permissions to allow public access. 

**Step #3: Purchase a Custom Domain through Amazon Route 53 **

    •	Open the Amazon Route 53 console. 
    •	Choose "Domain registration" and then "Register domain." 
    •	 Follow the prompts to purchase your custom domain. 
    •	 In the "Route 53 hosted zones," create a new record set. 
    •	Enter your S3 bucket's endpoint as the alias target.


