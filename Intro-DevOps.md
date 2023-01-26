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
