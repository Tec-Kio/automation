# Ecrazye Automation

Global reusable automation workflows for Ecrazye repositories.

## Consumer workflow

Each project should create:

.github/workflows/global-ci.yml

and call:

Ecrazye/automation/.github/workflows/reusable-ci.yml@main

## Scope

This repository centralizes CI, repository health checks, Python checks, Node checks, and secret scanning.

It does not deploy production systems or mutate infrastructure.
