# Docker_jenkins_erlang
docker file base of jenkins but with erlang

# jenkins base
jenkins docker file from [michaelneale/jenkins-ci](https://github.com/michaelneale/jenkins-ci.org-docker.git)

# how to use
copy Dockerfile and init.groovy into dir like /data/jenkins  
run "docker build -t jenkins-erlang:latest" or may  
"docker build -t jenkins-erlang:$your_version"

# update erlang?
modify "FROM erlang:18.3" in dockerfile   
like FROM erlang:20.0