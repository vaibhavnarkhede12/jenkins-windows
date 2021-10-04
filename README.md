# jenkins-windows
***************************************************************************************************
This repository indicates use of jenkins on a windows machine . 
***************************************************************************************************

Download the jenkins installer from , this document refers the instllation for version 2.314 windows ,
https://www.jenkins.io/download/ 

1.  installation pth -  C:\Program Files\Jenkins\
2.  I am running service as a local system 
3.  I am using port number 9090 , but anyone can be used .

4.    This Insatalltion requires java , since jenkins is a JAVA based application

    It will ask for the java path in your system ,
    this is my java home directory path 
    C:\Program Files\Java\jdk1.8.0_281\
   

5.  it will ask for a firewall exception 

    `select : Entire feature will be installed on local hard drive`

6.    next -> Install and it will automatically open up in your default browser 

    it wil require admin password which you will get in this file 
    C:\Windows\System32\config\systemprofile\AppData\Local\Jenkins\.jenkins\secrets\initialAdminPassword
    ( you can also get the password here :  ‪C:\Program Files\Jenkins\jenkins.err.log)

7.  install the suggested plugins by jenkins 
    
      `once installed it will ask for creating user , create user else you will need to use the password from above step each time and username as "admin"`


***************************************************************************************************

1. dashboard new item - > create folder ( jenkins_pipeline ) -> new item -> multibranch pipeline ( golang_demo_pipeline )
2. 




