# AWS Single-Tier Web Architecture
(Terraform | VPC | EC2 | Nginx)

 User 
   |
 Internet 
   |
 Internet Gateway (IGW) 
   |
 AWS VPC 
   └──  Public Subnet 
         └── EC2 Instance (Nginx) 
               └──  Security Group: HTTP/HTTPS 

