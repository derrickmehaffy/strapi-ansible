# strapi-ansible

Spinning up Strapi servers either from scratch or from a repo using Terraform and Ansible

## Status

This is currently a WIP and is not considered an officially supported Strapi project, script, ect. We working on this in our spare time to make it easier for Strapi users.

## Terraform

Terraform is used within this project for dealing with setups of cloud resources, we will do our best to include as many clouds as we can but we are always welcome to pull requests.

## Ansible

Ansible is used for the actual setup of depends and the deployment/creation of the Strapi project and initial configuration. There will be multiple template files to handle creation of various types of projects. Again we may not cover every use-case but we will accept PRs. **Please note at this time we are not entertaining support for Windows automation, PRs sent trying to add Windows will be closed**

## Expectations

While these scripts will certainly help newer users to both Terraform and Ansible, we do expect at least a little familiarity working with Linux and it's various shells, structure, ect. Bug reports will expect you properly follow the templates and issues opened that do not follow the templates will be closed.