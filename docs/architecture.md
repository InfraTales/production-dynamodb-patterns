# Architecture Notes

## Overview

Lambda + DynamoDB + API Gateway with Cognito auth across 3 environments.

## Key Decisions

- Higher CDK complexity vs raw CloudFormation
- DynamoDB cost at scale