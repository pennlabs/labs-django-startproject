# Labs Django Startproject

This repo contains a Django template with all of Penn Labs' suggested configuration.

## Usage

We recommend using our [Django template](https://github.com/pennlabs/template-django) which contains additional configuration for things like CircleCI, Docker, and Kubernetes.

However, if you only want the django configuration defined in this repo you can create a new project using this command: `django-admin startproject --template=https://github.com/pennlabs/labs-django-startproject/archive/master.zip --extension=py,cfg --name=Dockerfile ProjectName`
