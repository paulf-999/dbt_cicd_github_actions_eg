# dbt_github_actions_demo

Demo of using DBT tests as a basis for CI/CD, where GitHub actions have been used as the CI/CD technology.

---

## Contents

1. High-level summary
2. Getting started
    * Prerequisites
    * Installation
    * How-to run

---

## 1. High-level summary

This demo makes use of DBT tests as a basis for integration testing for CI/CD, where GitHub actions have been used as the CI/CD technology.

##### Technologies used
* GitHub actions for CI / CD
* DBT for integrating CI unit testing

---

## 2. Getting started

### Prerequisites

To make use of the example unit tests used for GitHub actions integration testing, the following Git secrets must be created against the repo:

* `SNOWFLAKE_ACCOUNT`
* `SNOWFLAKE_USER`
* `SNOWFLAKE_PASS`
* `SNOWFLAKE_ROLE`

## For reference:

For an example of how to use GitHub actions to run DBT, see: https://gist.github.com/troyharvey/d61ebe704395c925bf9448183e99af3e
For an overview of GitHub secrets (for GitHub actions), see: https://docs.github.com/en/actions/reference/encrypted-secrets#creating-encrypted-secrets-for-a-repository
