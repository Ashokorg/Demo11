#!/usr/bin/env groovy
properties([
   [$class: 'GithubProjectProperty',
   displayName: '',
   projectUrlStr: 'https://github.com/Ashokorg/Demo11/'],
   pipelineTriggers([githubPush()])])

node {
stage 'build'
echo 'hello world'
stage 'test'
echo 'hello veridic'
stage 'Deploy'
echo 'hello Atlanta'
}
