#!/usr/bin/env groovy
properties([
    [$class: 'GithubProjectProperty',
    displayName: 'shivakumar',
    projectUrlStr: 'https://github.com/My-NewOrganization/NewHampshire/'],
    pipelineTriggers([githubPush()])])

node {
  stage 'build'
  echo 'hello world'
  stage 'test'
  echo 'hello veridic'
  stage 'Deploy'
  echo 'hello Georgia'
 }
