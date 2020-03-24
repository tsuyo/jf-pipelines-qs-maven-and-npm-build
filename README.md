# JFrog Pipelines Quickstart: Maven and Npm Build

A real repo for [Pipeline Example: Maven and Npm Build](https://www.jfrog.com/confluence/display/JFROG/Pipeline+Example%3A+Maven+and+Npm+Build)

Source codes are based on https://github.com/sdemo/

# Prerequisites

- Pipelines/Integration: myGitHub
  - https://github.com/tsuyo/jf-pipelines-qs-maven-and-npm-build (for pipeline.yml)
  - https://github.com/tsuyo/jf-pipelines-qs-java-backend (for java backend)
  - https://github.com/tsuyo/jf-pipelines-qs-vue-frontend (for vue frontend)
- Pipelines/Integration: myArtifactory
  - libs-snapshot (maven/virtual)
  - libs-release (maven/virtual)
  - libs-snapshot-local (maven/local)
  - libs-release-local (maven/local)
  - npm (npm/virtual)
  - npm-local (npm/local)
  - docker-local (docker/local)
  - demo-pipelines (docker/local)
- On Platform UI | Administration | Security | Settings | check "Allow Anonymous Access"
