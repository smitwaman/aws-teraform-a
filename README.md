# aws-infra-using-terraform
Guide for building infrastructure using terraform

This will build your cutom VPC, EC2 instance, S3 backend, and you can also install app using install.sh file   

1. Configure and install aws libraries and terraform in system terraform.sh and aws-config.sh

2. Clone git repo in system as 
   
  $ git clone https://github.com/smitwaman/aws-terraform.git

3. Navigate to the folder

  $ cd aws-terraform

4. Run following terraform commands

  $ terraform init

  $ terraform validate

  $ terraform apply

 5. After use over dont forget to destroy.
  
  $ terraform destroy
