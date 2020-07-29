# Launching Website on the top of Docker

Project Aim:-
1.Create Docker file which will install jenkins.

2. As soon we run this docker image (docker file) it should install jenkins.

3. With the help of Job chaining , Now we have to create Jobs in Jenkins.

4. Job1 : Pull the Github repo automatically when some developers push repo to Github.

5. Job2 : By looking at the code or program file, Jenkins should automatically start the respective language interpreter install image container to deploy code ( eg. If code is of PHP, then Jenkins should start the container that has PHP already installed ).

6. Job3 : Test your webpage if it is working or not.

7. Job4 : if app is not working , then send email to developer with error messages.

8. job5 for monitor : If container where app is running. fails due to any reason then this job should automatically start the container again.

Complete Solution :-
 Please refer to my LinkedIn Article :- https://www.linkedin.com/pulse/task-2-automation-using-docker-filejenkinsgithub-ankita-singh/
