[![Build Status](https://semaphoreci.com/api/v1/projects/efa3c4aa-c017-4fd9-8d82-d0d47de87e2c/576264/badge.svg)](https://semaphoreci.com/doctavian/simpletomcatwebapp)
# SimpleTomcatWebApp

This simple example shows you how to deploy a simple tomcat war file using Distelli.

Steps:

1. Set your username in the manifest file

 Change <username> to your username

2. create the app

  distelli create &lt;username&gt;/SimpleTomcatWebApp

3. package using maven

  mvn package

4. push

  distelli push -m "Initial release of SimpleTomcatWebApp"

4. deploy

  deploy using the web UI.
