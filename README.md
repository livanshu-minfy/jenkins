# jenkins
-- EASY ASSIGNMENT --

deliverables of the assignment are:
1. Screenshot of your Jenkins dashboard
2. Screenshot of your pipeline's successful execution (Stage View)
3. Screenshot of the console output from one of your builds
4. Brief summary (3-5 sentences) describing what you learned about Jenkins navigation


First, I installed jenkins via docker using the below mentioned command:
docker run -p 8080:8080 -p 50000:50000 -d -v jenkins_home:/var/jenkins_home jenkins/jenkins:lts

-- screenshot of my jenkins dansboard -->

![Screenshot 2025-05-20 101548](https://github.com/user-attachments/assets/1bac2f13-96c7-4ed8-98ba-e7e3499db3c9)

-- screenshot of my pipeline's successful execution -->

![image](https://github.com/user-attachments/assets/76e066f6-e3a7-4fe2-bb68-73308f2f586b)

-- screenshot of the console output from my build -->

![Screenshot 2025-05-20 100440](https://github.com/user-attachments/assets/ddf99e7d-9a28-4ecb-8fac-a48727ff4c8a)

-- adding a new stage in the pipeline (cleanup) and successful execution -->

![Screenshot 2025-05-20 101240](https://github.com/user-attachments/assets/d5888497-1b4f-4d22-b110-059854e37eeb)
![Screenshot 2025-05-20 101431](https://github.com/user-attachments/assets/2dcb9f73-492d-4074-85a0-3fb9fd719ff8)
![Screenshot 2025-05-20 101520](https://github.com/user-attachments/assets/1da5ad95-f87d-4714-9526-65a432c4467f)


throught this assignment i have learned how to navigate jenkins dahboard . I created a basic pipleline which have 3 stages those are build, test and deploy and after that I made changes in pipeline and added another stage that is cleanup and tried to build the pipleline again, the build was successful. I also installed a plugin from the plugins section to view stage view of a pipeline
