# devops-ansible
Jenkins CI/CD Pipeline - Ansible, Docker, Github Webhooks on AWS

![conception](https://github.com/ahmed252023/devops-ansible/assets/131555266/c0678fe4-6f0c-4cf9-b9a7-1aa0569aa7e2)

1- Create 2 AWS instance 

![instances](https://github.com/ahmed252023/devops-ansible/assets/131555266/4d780afe-47f2-49ae-bbfe-c59cdb62d93c)

2- Create freestyle project in jenkins

![jenkinsconf1](https://github.com/ahmed252023/devops-ansible/assets/131555266/58e7d555-6918-4e4b-9670-f99cc25030d9)

![jenkinsconf2](https://github.com/ahmed252023/devops-ansible/assets/131555266/ff47e3fa-ce79-4734-ae23-b7be8679d722)

![jenkinsconf3](https://github.com/ahmed252023/devops-ansible/assets/131555266/3211d8fc-14c6-43a1-a689-9b4d459e1a14)

3- Install docker and ansible 

4- Create keygen and bind the 2 instance with id_rsa.pub

![id_rsa](https://github.com/ahmed252023/devops-ansible/assets/131555266/9f278fe3-4eb7-4831-adc9-f1f2f94a3537)

![auth](https://github.com/ahmed252023/devops-ansible/assets/131555266/6ecaa1cd-f1f8-4b1f-9308-773cfe5780d5)

5- Added public ip of docker instance to the hosts of jenkins instance 

![hosts](https://github.com/ahmed252023/devops-ansible/assets/131555266/6bc0e1b4-02b4-4932-b958-5bfe0665f612)

![hosts 2](https://github.com/ahmed252023/devops-ansible/assets/131555266/f98856bf-5d86-4197-9365-e099408bca70)

6- Create file deployment.yaml


![deployment 1](https://github.com/ahmed252023/devops-ansible/assets/131555266/375cc116-46c0-4dfe-97fe-458dc5a27b8b)

7- Webhooks configuration  

![webhook](https://github.com/ahmed252023/devops-ansible/assets/131555266/d6728603-af8c-42f0-adb2-9b3e68c9d18e)

8- execution de project in jenkins 

![jenkins execution](https://github.com/ahmed252023/devops-ansible/assets/131555266/c5b66960-cc2c-43aa-8b4d-6b8b6b7cebb8)



