# Rietta Application Deployment Guide

We support a number of client projects in a variety of deployment environments. 
This guide aims to centralize the setup and operational steps required for each type of deployment environment we use.

## Elastic Beanstalk (AKA EB)

Fill this in ASAP

## Heroku

## Capistrano (targeting Linode, Rackspace, etc)

Generally this requires having your ssh public key distributed to the servers in question, which might also involve an entry in your local `~/.ssh/config` file. After that, it should be automatic or interactively guided by running `$YOUR_PROJECT_ROOT/bin/deploy`
