# Hello Orb [![CircleCI Build Status](https://circleci.com/gh/CircleCI-Public/hello-orb.svg?style=shield "CircleCI Build Status")](https://circleci.com/gh/CircleCI-Public/hello-orb) [![CircleCI Orb Version](https://img.shields.io/badge/endpoint.svg?url=https://badges.circleci.io/orb/circleci/hello-build)](https://circleci.com/orbs/registry/orb/circleci/hello-build) [![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](https://raw.githubusercontent.com/CircleCI-Public/hello-orb/master/LICENSE) [![CircleCI Community](https://img.shields.io/badge/community-CircleCI%20Discuss-343434.svg)](https://discuss.circleci.com/c/ecosystem/orbs)

A simple orb published to help get you down the road.

## Usage

To use this orb, try:

```
version: 2.1

orbs:
    hello: circleci/hello-build@volatile

workflows:
    "Hello Workflow":
        jobs:
          - hello/hello-build
```
