Abort Parent test project
=======================

This project helps to test Abort Parent property of ReUsable sub-process in KIE Business Central.

## How to use
* Import project and deploy project
* Start **AbortParentReusableSubProcess** process (see image below)
* By default nothing will be printed to the server log
* Open **AbortParentReusableSubProcess** and set Abort Parent to _false_
* Redeploy project and start **AbortParentReusableSubProcess** again
* In server log you will see "Hello world", it menas parent process wasn't aborted on error in callable process

![](src/main/resources/com/myspace/abortparent/AbortParent.AbortParentReusableSubProcess-svg.svg)
