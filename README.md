# Duo-AWS
Used to document some basic Duo and AWS setup to enforce MFA for applications and utilize SSO

These light projects were made to showcase some technical ability in setting up Cisco Duo for a technical portion of an interview process. I had already been studying AWS and pursuing an AWS certification when this oppurtunity came across so I decided the focus would be around AWS and Duo implementation. I setup Duo Single Sign-On For AWS using Duo Hosted SSO (one of the use cases required by the interview). Inside of the AWS enviroment I launced a Linux EC2 instance and protected all SSH logins to it with DUO MFA. I made the EC2 instance accessible from anywhere over SSH for ease of demonstration. Lastly, I configured the AWS Client VPN to also utilize Duo SSO to enable protected access to the sole VPC in the AWS account. The SSO authentication source was from my HomeLab Active Directory, basically a repurposed Lenovo tower running xcp-ng to spin up VMs for messing around with things like this. All in all it was a fun set of projects to get my feet wet with Duo and some AWS configurations that did involve some good amounts of troubleshooting. Mostly used Duo's documentation but Google also pulled a lot of weight in getting this all setup and working to showcase.
