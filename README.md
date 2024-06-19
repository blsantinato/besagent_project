# How to use BigFix Report and Remove installation packages - Linux / AIX 
 BigFix Report and Remove Installed package if needed
## **Goal**

This playbook was created to check if BigFix agent was installed in Linux and AIX Operational System. 
This documentation improve your knowledge how you can execute this report and receive it thru mail.

Below describe how to use it on Ansible Automation Tool. 

!!! tip

-This playbook works with AIX and Linux Operational System 

-There is two roles inside this Project, please <strong>PAY ATTENTION!</strong>

-First role generate a report informing if tbe BigFix is installed or not installed

-Second role remove and generate a report informing what servers removed this installation if exist.

## **Runbook**

###Using this automation on AAP

Login on AAP and open the [automation](https://cio-ansible-automation.ibm.com/#/templates/job_template/3832/)

Click on launch button :arrow_down:
![launch](https://github.ibm.com/Bruno-Santinato/besagent_project/blob/main/images/step1-besagent_project.jpg)

Select your inventory and click on next button:
![inventory](https://github.ibm.com/Bruno-Santinato/besagent_project/blob/main/images/step2-besagent_project.jpg)

Select your credential accordinally with your Squad: 
![credential](https://github.ibm.com/Bruno-Santinato/besagent_project/blob/main/images/step3-besagent_project.jpg)

Answer the SURVEY:
<strong> IMPORTANT!</strong>

> Server can used all or specific host

> Option survey have two that can be used : besagent_check and besagent_remove

![important-note](https://github.ibm.com/Bruno-Santinato/besagent_project/blob/main/images/important-note.jpg)

![survey](https://github.ibm.com/Bruno-Santinato/besagent_project/blob/main/images/step4-besagent_project.jpg)

Check Preview section until execute the playbook:

![Preview](https://github.ibm.com/Bruno-Santinato/besagent_project/blob/main/images/step5-besagent-project.jpg)

After finish JOB, check your email to see report attached like example below :

![Result](https://github.ibm.com/Bruno-Santinato/besagent_project/blob/main/images/step6-besagent-project.jpg)

![mail_example](https://github.ibm.com/Bruno-Santinato/besagent_project/blob/main/images/step7-besagent_project.jpg)