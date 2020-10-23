# Platform-challenge

### Overview
This project describes a situation that you may face in your day-to-day work at Everlywell. The goal of this project is to give you the opportunity to demonstrate your ability to solve problems, support your conclusions and communicate to stakeholders.

### Requirements
* Spend no more than 3 hours on the project
* Fork this project and work in your repo
* The tools you use to accomplish the project are your choosing
* You would need access to compute and storage resources to execute this project
* You would be required to speak to your process and decisions in carrying out this project

### Scenario
#### Part 1
Imagine that you joined Everlywell at the early stages of modernizing their application. Currently, they have a Rails application that uses postgres database that is hosted on a virtual machine.

Deployments are a manual which involves signing into the virtual machine, pulling down the most recent deployment branch and restarting the web server. 

This workflow is slow and cumbersome, and the company wants you to come up with a way to deploy the api on Kubernetes to take advantage of its many benefits. 

A copy of the rails app is located in this repo in the folder `rails_app`.

#### Part 2
Design a pipeline to deploy the rails app to your kubernetes cluster when the master branch is updated. You can use your choice of CI/CD tools for example Gitlab and Github Actions.

#### Submission
Submission for this project should be on an actual kubernetes cluster with the app deployed on it using the pipeline you created. At the time of presentation, we should be able to view the app by entering an IP or a DNS name. All supporting code should be checked into your forked repo including your pipeline yaml.

You should be able to show the final product and delve hands-on into the tools you used in real-time.
