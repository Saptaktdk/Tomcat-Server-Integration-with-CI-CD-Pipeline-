
## Project Goal:

To integrate a Tomcat server with the CI/CD pipeline and deploy artifacts into the server.

![](Tomcat_plan.jpg)
## Source Code:

The source code is taken from https://github.com/Saptaktdk/hello-world
## Setting up the Tomcat Server:

* First, an ec2 instance is created for the tomcat server:

![](./Tomcat_%20Instance.png)

* Used MobaXterm to create a remote session.

![](./MobaXterm.png)

* Tomcat Installation guide: https://github.com/yankils/Simple-DevOps-Project/blob/master/Tomcat/tomcat_installation.MD

* To start the Tomcat services do startup.sh.

![](./Step1.png)

![](./Step2.png)

![](./Step3.png)

![](./Tomcat_Server.png)
## Integrating Tomcat with Jenkins:

* Installed Deploy to container pluggin.

![](./Deploy_to_Container.png)

* Made a maven project that can make the build and deployment on Tomcat Server.

![](./Maven_Project.png)

* Opening the Tomcat Server:

![](./Tomcat_Page.png)



## Automating the build and deploy using Poll SCM:

![](./Build_Trigger.png)

![](./Console_Output.png)