# tkn-cheat-sheets
The goal of this repository is list the useful  tkn commands


# Tekton CLI(tkn) Cheat Sheet: 

## Resources:
Inspect created resources:
```shell script
    tkn res ls
```
Describe specific resource:
```shell script
    tkn res describe <resource_name>
```
## Task:
Verify the task
```shell script
    tkn task ls
```
Describe the task
```shell script
    tkn task describe <task_name>
```
## TaskRun:
List the TaskRun:
```shell script
    tkn tr ls
```

Check Logs
```shell script
tkn tr logs -f -a build-app-run-tsqrf
```
    
## Pipeline:
Start Pipeline
```shell script
tkn pipeline start svc-deploy
```
