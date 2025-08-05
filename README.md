# Task-2_05-08-2025
Set up a basic Jenkins pipeline to automate the process of building and deploying an application.

1. Installed Jenkins on my personal laptop.
2. Created a Jenkinsfile with a demo pipeline adding build, test and deploy stage.
3. Created a New Pipiline item in Jenkins.
4. In advanced project option, selected "Pipeline script from SCM" and gave the repo url.
5. Selected main branch in "Branches to build section".
6. Added Jenkinsfile in script path section.
7. Configured Jenkins to trigger the pipeline on each code commit.
8. To do the trigger, checked the "Github hook trigger for GITScm polling" option in "Build Trigger section".
9. Now in the repo setting, I created a webhook and saved.
10. Pipeline is giving success message in Jenkins dashboard on every code commit.




