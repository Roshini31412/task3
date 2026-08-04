# Jenkins Git Integration Demo

This repository demonstrates how Jenkins integrates with GitHub using webhooks.

## Features
- Declarative Jenkins pipeline (`Jenkinsfile`)
- Automatic build trigger on Git push
- Simple Build → Test → Deploy stages

## Setup
1. Configure Jenkins with the Git plugin.
2. Add a webhook in your GitHub repo pointing to:
   `http://<jenkins-server>:8080/github-webhook/`
3. Push a commit to trigger the pipeline automatically.
