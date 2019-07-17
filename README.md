# Udacity Cloud DevOps Engineer
## Project 2 - Infrastructure as Code

The main purpose of this project is to have a first contact with IaC in AWS by using cloudFormation.

In this repo you will find the following:

* **Architecture.png**: Showing the architecture that has been implemented.
* **HA-webapp.yml**: YAML file with cloudFormation code.
* **HA-webapp-params.json**: External file with stack parameters.
* **create.sh & update.sh**: Helper files for deploying the stack.
* **index.html**: File used as landing page for the web app. Stored in an S3 bucket.
* **screenshot.png**: Expected output of the project.

You can deploy the stack by running:
```bash
sh create.sh udacity-iac-project HA-webapp.yml HA-webapp-params.json
```

As an important point, the LoadBalancer DNS is used as an Output value to easily reach the web application.