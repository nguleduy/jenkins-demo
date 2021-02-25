# jenkins-demo
###How to start:
1. gradlew docker
2. gradlew dockerRun
3. create a job - freestyle project (seed)
- select git, add repository URL
- build > add build step > process job DSLs > Look on FileSystem : createJobs.groovy
- save
4. docker cp {***_container_id}:/var/jenkins_home/jobs/seed/config.xml seedJob.xml
5. createJobs.groovy
6. create pipelineJob.groovy

