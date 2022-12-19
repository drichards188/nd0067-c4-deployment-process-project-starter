# Pipeline

![](/home/david/WebstormProjects/nd0067-c4-deployment-process-project-starter/assets/pipelineDiagram.png)

1. push code to Git in a branch watched by circleCi
2. this pipeline has a build, hold and deploy sections
3. the push to Git will cause the build scripts to run
4. this creates, configures the environment then installs the software
5. these are npm scripts in package.json
6. if the build phase completes the user needs to manually approve deploying
7. the build phase then executes which ends in the new code deploying to AWS