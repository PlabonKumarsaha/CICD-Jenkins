# CICD-Jenkins
Download the war file from : https://www.jenkins.io/download/

Steps:
download the war file from the mentioned link
cmd : `java -jar C:\Users\pkuma\Downloads\jenkins.war --httpPort=9090`
  -- A key will be generated : `312e163e20c549fa9d20be1e20ea27a7`
 ` C:\Users\pkuma\.jenkins\secrets\initialAdminPassword`
  
  -Run in localhost:9090 port
  -then setup an admin : pks, era123




## My Setup

port : 9090

## In localhost:9090 the following admin pannel can be found
![image](https://user-images.githubusercontent.com/46686524/148693517-c31d2dae-6f3d-493c-bb6b-510655ab8e4a.png)

- The auto gernated password must be added here
- Then the system asks for insatlling plugins. I have chosen the suggested plugins which automatically installs some popular plugins such as git,pipeline, ant, grade etc

Then the following panel is shown. It asks to create the first admin
![image](https://user-images.githubusercontent.com/46686524/148693859-7bff92e7-4a9e-464a-8a04-cdde87b38a09.png)

Then this jenkins url is asked such the following image
![image](https://user-images.githubusercontent.com/46686524/148693916-5d126016-3544-4d85-a505-30b49520d9aa.png)

Jenkins is then ready to use! congrats!

## adding a maven project in jenkins
- from the dashboard choose manage jenkins
![image](https://user-images.githubusercontent.com/46686524/148694126-cbe46798-6d93-4ccb-84e9-c52329889215.png)

-Then select manage plugins >> available >> [find maven plugin]>> insatll the maven ingetration plugin for deploying maven projects

## deploy new item
- from the dash baord choose new item
![image](https://user-images.githubusercontent.com/46686524/148694310-dc057821-be2e-43c0-8cde-331655ddfbde.png)

- enter a name like the above picture and choose Maven project . Press okay on the left below

We are directed to the following page
![image](https://user-images.githubusercontent.com/46686524/148694362-b3fd6e14-113d-49df-9a03-127eea79a28f.png)

- from the source code manager the git option must be selected and then the git project URL needs to be pasted
![image](https://user-images.githubusercontent.com/46686524/148694395-4b6ad48f-9c1e-4949-88b3-6d069bb57f06.png)

https://www.youtube.com/watch?v=GlQHS7FdVGM&list=PL6flErFppaj35spJjPy41-lruDjw2kRV-&index=8&ab_channel=Mukeshotwani

