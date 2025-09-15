# CLOUD-STORAGE-CREATION-S3-AND-LAUNCHING-AN-EC2-INSTANCE-IN-AWS-
## Name: S.NAVINKUMAR
## Reg.no:212224110041
# Aim:
To create a Simple Storage Service (S3) in AWS and to launch an EC2 instance in Assure.
# Procedure:
Step 1: Create a Simple Storage Service (S3) Bucket in AWS
1.	Login to your AWS Management Console → https://console.aws.amazon.com.
2.	In the search bar, type S3 and open Amazon S3 service.
3.	Click Create bucket.
4.	Fill in:
o	Bucket name (must be unique globally, e.g., myproject-bucket-navin).
o	AWS Region → choose the region where you want to store data.
5.	Bucket settings:
o	Uncheck Block all public access if you want it to be public (otherwise leave it checked).
o	Enable/disable Versioning depending on use.
o	Choose Encryption (default is fine).
6.	Click Create bucket.
7.	Your bucket is created → you can now upload files, create folders, or manage permissions.
   
Step 2: Launch an EC2 Instance in AWS
1.	Login to AWS Console.
2.	In search bar, type EC2 and open EC2 Dashboard.
3.	Click Launch instance.
4.	Configure instance details:
o	Name → e.g., MyEC2Server.
o	Application and OS Images (AMI) → Select (e.g., Amazon Linux 2, Ubuntu, or Windows Server).
o	Instance type → e.g., t2.micro (Free tier eligible).
5.	Key pair (login):
o	Create a new key pair → download .pem file (for SSH access).
o	Or choose existing one if you already have.
6.	Network settings:
o	Choose default VPC.
o	Allow SSH (22) for Linux or RDP (3389) for Windows.
o	Allow HTTP (80) or HTTPS (443) if you plan to host a website.
7.	Storage:
o	Default 8GB EBS volume (can increase if needed).
8.	Click Launch instance.
9.	Once launched → Go to EC2 Dashboard → Instances → select your instance.
o	Copy Public IPv4 address.
o	Use SSH (for Linux):
Eg: ssh -i your-key.pem ec2-user@<public-ip>
o	For Windows: Download RDP file → login with admin credentials.
# Output:
# Result:

