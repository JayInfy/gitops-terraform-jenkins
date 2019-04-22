# gitops-terraform-jenkins

## Overview

This repository will demonstrate an example GitOps workflow with Terraform and Jenkins.

The configuration in this repository was run using `Terraform v0.11.13`.

## Requirements

* Terraform installed on Jenkins
* GitHub access token
* SSH Key configured on Jenkins to clone repositories

## Plugins Required

* [Workspace Cleanup Plugin](https://wiki.jenkins.io/display/JENKINS/Workspace+Cleanup+Plugin)
* [Credentials Binding Plugin](https://wiki.jenkins.io/display/JENKINS/Credentials+Binding+Plugin)
* [AnsiColor Plugin](https://wiki.jenkins.io/display/JENKINS/AnsiColor+Plugin)
* [GitHub Plugin](https://wiki.jenkins.io/display/JENKINS/GitHub+Plugin)
* [Pipeline Plugin](https://wiki.jenkins.io/display/JENKINS/Pipeline+Plugin)
* [CloudBees AWS Credentials Plugin](https://wiki.jenkins.io/display/JENKINS/CloudBees+AWS+Credentials+Plugin)

## Questions?

Open an issue.
