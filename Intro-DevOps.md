# DevOps Introduction

## Understand SDLC

## DevOps Lifecycle
* __Code:__ Developers commit code
* __Code Build:__ Deployable software aka Artifact
* __Code Test:__ Unit & Integration test
* __Code Anaysis:__ Vulnerabilty and build practices
* __Delivery:__ Deploy changes to staging
* __DB/Sec Changes:__ Every other ops changes
* __Software Testing:__ QA/ Functional, load, performance test
* __Deploy to Prod:__ :)
* __Go Live:__ User traffic diverted to new changes
* __User Approval:__ User feedback
* __Monitoring:__ Monitor DevOps Lifecycle

Continuous Integration is an automated process in DevOps which generates software and its feature quickly and efficiently.

It's an ideal practice to store all thsi code in a centralized place anad this centralized repository is called as version control system like github.

This code will be moved to build server. This code will be built, tested and evaluated which generates software or artifact which will be stored in its repository.
Artifact or Software is an archive of files generated from the build process based on the porgramming language. This artifact will be packaged in a specific format.

Artifact packaging format could be war or jar in java. DLL/EXE/MSI in Windows. From repo to server for further testing. On testing team apporval, it can be moved to production servers. 

The goal of CI is to detect errors and bugs at a very early stage so it's not compunded. That's why we automate it in such a way, when the DEVs commit a code, it is fetched for testing and evaluation and any errors is notified to the DEVs for immediate fix. In this way, we can reduce wait time as well as compunded errors.

## CI Automation tools:
* __IDE:__ ECLIPSE, VSCODE, ATOM, PYCHARM
* __VCS:__ GIT, SVN,TFS, PERFORCE
* __Build tools:__ MAVEN, ANT, GRADLE, MSBUILD, VISUAL BUILD, IBM URBAN CODE, MAKE, GRUNT  
* __Software Repo:__ SONATYPE NEXUS, JFROG ARTIFACTORY, ARCHIVA, CLOUDSMITH PACKAGE, GRUNT
* __CI Tools:__ JENKINS, CIRCLECI, TEAMCITY, BAMBOO CI, CRUISE CONTROL

Continuous Delivery is an automated process of delivering code changes to servers quickly and efficiently.
After continuous integration is good, the artifact generated will be stored in software repositories. 

*Note: A deployment could mean server provisioning, installing dependencies on servers, configuration changes, network or firewall changes, deploying the artifact and many more.

## CD Automation tools:
* __System Automation:__ ANSIBLE, PUPPET, CHEF
* __Cloud Infra Automation:__ TERRAFORM, CLOUDFORMATION
* __CI/CD Autoamtion:__ JENKINS, OCTOPUS DEPLOY
* __Others:__ HELM CHARTS, CODE DEPLOY

Software testing has to be automated which includes functional, load, performance, DB, Network and Security.


## Continuous Delivery
* __Code:__ Developers commit code
* __Code Build:__ Deployable software aka Artifact
* __Code Test:__ Unit & Integration test
* __Code Anaysis:__ Vulnerabilty and build practices
* __Delivery:__ Deploy changes to staging
* __DB/Sec Changes:__ Every other ops changes
* __Software Testing:__ QA/ Functional, load, performance test
* __Deploy to Prod:__ :)


More to be continued...
