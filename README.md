# Hello Orb ![CircleCI status](https://circleci.com/gh/CircleCI-Public/hello-orb.svg "CircleCI status")
A simple orb published to help get you down the road.

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
