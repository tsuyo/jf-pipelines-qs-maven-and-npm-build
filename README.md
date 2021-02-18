# JFrog Pipelines Quickstart: Npm Build

Sources for [Pipeline Example: Npm Build](https://www.jfrog.com/confluence/display/JFROG/Pipeline+Example%3A+Npm+Build)

## Prerequisites

- Integrations
  - tsuyo_github: GitHub
  - artifactory: Artifactory
- Repos
  - npm-local (npm/local)
  - npm-remote (npm/remote)
    - URL: https://registry.npmjs.org
  - npm (npm/virtual)
    - includes: npm-local, npm-remote