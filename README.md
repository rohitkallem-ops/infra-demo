# Infrastructure Repository Consolidation Demo

## Objective

This repository demonstrates how multiple environment-specific repositories can be consolidated into a single repository structure.

## Current Approach

infra-module-stage

infra-module-prod

## Proposed Approach

infra-module

├── environments
│   ├── stage
│   └── prod
│
└── modules

## Benefits

- Reduced repository duplication
- Easier maintenance
- Centralized infrastructure management
- Better consistency across environments
- Improved scalability

## Repository Structure

environments/
- stage
- prod

modules/
- reusable infrastructure modules
