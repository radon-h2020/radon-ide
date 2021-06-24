# radon-menu README

This plugin provides a RADON menu with custom RADON commands.

## Features

- RADON command to open the RADON Help Page
- RADON command to open the RADON Monitoring Page
- RADON command to open the RADON Show Deployment Page 

## Requirements


## Extension Settings


## Known Issues


## Release Notes

### 0.0.1

Initial release

The deployment process of a CSAR is managed by a Jenkins job. The job is triggered when a CSAR is uploaded on the temporary repository "radon-csar" available here https://github.com/radon-h2020/radon-csars

### 0.0.2

The CI process of a CSAR is managed by a Jenkins job. The user can upload the CSAR on the Template Library and trigger a Jenkins job which will manage the deployment process of the CSAR interacting with the Orchestrator.

### 0.0.3

The plugin has been updated to configure and trigger CI/CD pipelines on a Jenkins platform using a configuration file (i.e., a yaml file) generated from a CSAR.

### 0.0.4

In the final relase of this plugin (v0.0.4) the CI/CD capabilities have been moved to another plugin (i.e., radon-cicd-plugin).

