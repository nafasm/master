agent {
    kubernetes {
        label podlabel
        yaml """
kind: Pod
metadata:
  name: jenkins-slave
spec:
  containers:
  - name: kaniko
    image: tomcat:latest
    imagePullPolicy: Always
"""
   }
