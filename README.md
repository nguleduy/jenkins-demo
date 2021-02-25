# jenkins-demo
###How to start:
1. gradlew docker
2. gradlew dockerRun
3. create a job - freestyle project (seed)
- select git, add repository URL
- build > add build step > process job DSLs > Look on FileSystem : createJobs.groovy
- save
