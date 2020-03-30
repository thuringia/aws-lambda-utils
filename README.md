# aws-lambda-utils

![](https://github.com/thuringia/aws-lambda-utils/workflows/Deploy%20helpers/badge.svg?branch=master)
[![Known Vulnerabilities](https://snyk.io/test/github/thuringia/aws-lambda-utils/badge.svg)](https://snyk.io/test/github/thuringia/aws-lambda-utils)

A collection of helpful lambda functions

## `addSecurityHeaders`

Upload addSecurityHeaders into aws lambda

Node.js 12 handlers:

- [`addSecurityHeaders`](./addSecurityHeaders.js)

IMPORTANT: Use "US East (N. Virginia)" as Region for the lambda function!!!

The ARN is in the top-right of the aws-modify-lambda function screen. You need the ARN + a version to use in the playbook. Use "Action" -> "Publish a new version" to create a new version.

IMPORTANT: Version \$LATEST doesn't work, it's a limitation of AWS. Use the actual version number instead.
