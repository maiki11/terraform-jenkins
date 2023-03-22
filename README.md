# terraform-jenkins

### run the commands:
``terraform init``
``terraform plan``
``terraform apply``


- If you have some troubles with some file that we copy to the server you need to change some paths on the main.tf files.
Before you run terraform init you see this main.tf files inside the folder .terraform/modules/jenkins/jenkins-controller and .terraform/modules/jenkins/jenkins-agent
in those files you need to replace "~/" to "/home/your_user/" everywhere.
- Once that you change that run the terraform plan and terraform apply and then you can have jenkins running correctly.
