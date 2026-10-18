# This file is to document what I have done on 17-10-2026

## Installation and setting up environment
- installed java version 21 on my machine.
- installed jenkins 2.586 on my machine and configured, installed the necessary plugins.
- installed the docker plugins in my machine to make the jenkins use docker containers for pipelines.

## Project initialization and hands-on
- Created two projects `/jenkins` and `/multi-stage-build`
- <img width="1187" alt="Jenkins-projects-dashboard" src="docs/images/jenkins-project.png">
- `docs/images/jenkins-project.png`
### first project
- Tried the sample jenkins project to test the jenkinsfile
- The first project got success after getting few errors. Resolved it and the proofs are attached below.
- Build history is in the below location.
  `docs/images/jenkins-project.png`

### Second project - multi stage jenkins build.

- Created a muti-stage-jenkins project
- Peform two stage jenkins build, fron-end-deployment and back-end-deployment.
- issues faced
    - faced issue with github private repository ( made the repo to public and git checkout worked properly)
    - Issue image version, docker couldn't able to pull the image properly and it has been fixed after updating correct image version.
    - Few typo issues in the jenkins groovy syntax
- build history
    - `docs/images/jenkins-project.png`
- Still there is with github triggering the pipeline automatically, working on it.