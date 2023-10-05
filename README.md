# myresumefromstaticwebsite
Accessing my resume from AWS static website

# What it does
This is a repository of a static website, showing my resume with a picture. Any information can be projected in place of my resume. The website file is hosted on AWS S3 Bucket by enabling the static website and allowing the URL generated fetch image from S3 to be viewed on the internet. Then deployed Cloudfront to add security and fast accessibility via the edge locations and SSL to the website. I also used AWS Route53 to host a domain name with A record, this allowed a hosted user-friendly name to be used to access the URL.

# Things I learned
* AWS S3 Static Website
* AWA Permissions
* AWS Cloudfront 
* AWS Route 53
* DNS- A-record.


# How to run?
* Create an S3 bucket and upload the HTML files for the static website
* Create Cloudfront and configuration
* Create Route53 and necessary configurations
* Save and run with the hosted domain name.
