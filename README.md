# Artifact Repository Manager with Nexus and Maven

This project uses a premade application to showcase how to manage artifacts with a locally deployed instance of Nexus and an application using Maven package manager.

## Purpose and Tasks

Apply DevOps Skills to properly manage artifacts with Nexus.

## Requirements

## Build and copy file to remote

## Start Application


Adding "&"  to the command will run the application in the background

## Stop or Kill application

[ctrl + c] will stop the application, but if you decided to run the application in the background with "&", there are some extra steps.

Locate only running java apps
```bash
ps aux | grep java
```

Take the PID column of the running application(process)
```bash
kill <pid of your app>
```
