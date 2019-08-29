---
title: 'Review GitHub Actions'
author: '[frank.jung@marlo.com.au](mailto:frank.jung@marlo.com.au)'
date: '29 August 2019'
output:
  html_document: default
---

## Introduction

Evaluation of features:

* Triggers for pipeline execution
   * On-commit job execution
   * Scheduled job execution
* Per-branch job execution
* Using Docker image(s) for build
* Publishing test / pipeline results to somewhere
* Variables
* Secrets
* Integration to third party services: Kubernetes

## GitHub

GitHub Actions (Beta) https://help.github.com/en/articles/about-github-actions

Where are actions documented?

* https://github.com/actions
 
Where are pipelines reported?

* Under actions:


## Triggers

Triggered pipeline execution:

### Event restrictions

### Webhook events

### Scheduled events

### External events

## Docker

https://developer.github.com/actions/creating-github-actions/creating-a-docker-container/

## Publishing

https://help.github.com/en#github-pages-basics

Using action: 

* https://github.com/peaceiris/actions-gh-pages
* https://github.com/marketplace/actions/deploy-to-github-pages-for-static-site-generator

## Variables

https://help.github.com/en/articles/virtual-environments-for-github-actions#environment-variables

## Secrets

## Summary

How this benefits Marlo's DevOps practice.
