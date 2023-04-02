Jenkins Training - Duration 8 hours (2 days)
-----------------------------------------
Break 1: 10 mins 08:30 IST / 11:00 am EST
Break 2: 30 mins 09:30 IST / 12:00 pm EST
Break 3: 10 mins 11:00 IST / 01:30 pm EST


DevOps Methodology

Git -> Version ControlSystem
Jenkis -> CI -CD Tool
Docker -> Deployment Tool
Ant,Maven  -> Build Tool


Jenkins from scratch

  - java web application default port :8080
  - used for continuous integration and continuous delivery
  - Prerequisite - java must be installed on your system
  - Easier way of Installation of Jenkins
  

Set up/Install Jenkins Environment
----------------------------------

Step 1: Create Account in Docker Hub

          https://hub.docker.com/
   
           username /Email : pradeepch82@gmail.com
           password        : ########  


Step 2: Login to lbasplay with above credentials

        https://labs.play-with-docker.com/

        
Step 3: Click Add New Node 
  

Step 4: Use below command to start Jenkins as container


        docker run -p 8080:8080 -p 50000:50000 jenkins/jenkins



       Copy password from console to login jenkins 


      Open port :8080
      
     use password copied to launch jenkins
 
     Install suggested plugin

     Create First Amin User

     Start Jenkins to use.
    

10 mins break.

  

1.Load Source Code From Github

   echo "Clone pvc-git-material repsitory";

   git clone https://github.com/pvc2021/pvc-git-material.git

   echo "Cloning pvc-git-material repsitory is done";



2. 
------------------------------------------------------------------
   S.N 	Job Title   Description               script
------------------------------------------------------------------
    1.	 Dev        Devlop a Java Code         echo "Java Source code developed successfully";
    2. 	 Build      Devlop a Java Code         echo"Java Source code built successfully"; 	              
    3.   Test       Test a Java Code           echo "Java Source code tested successfully";
    4.   Stage      Stage a Java Code 	      echo "Java Source code staged successfully";
    5.   Deploy     Deploye a Java Code        echo "Java Source code deployed successfully";







 Refernce doc :  https://hub.docker.com/_/jenkins




    Shortcuts used in lab

        Ctrl   +  Insert => Copy
        Shift  +  Insert => Paste




git clone https://github.com/pvc2021/pvc-git-material.git




